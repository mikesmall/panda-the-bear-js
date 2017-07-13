1.
# Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead.
# PROTIP: use the inspector to learn the dimensions of the current profile image and use a placeholder image service such as Place Bear to get an image of the same size.

    var profileImage = document.querySelector( '.profile-image' );

    profileImage.src = 'http://i.imgur.com/bJ9obIc.jpg';

________________________________________________________________________________________________
1.
# Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing.

    var skyImage = document.querySelector( 'img[title="Man Walking on Ice"]' );

    skyImage.src = 'http://i.imgur.com/V0BKDRg.jpg';

________________________________________________________________________________________________
2.
# Select the heading that says "Panda the Bear" and change it to your own name.

    var pageTitle = document.querySelector( 'h1[class="highlight"]' );

    pageTitle.innerText = 'Mike Small';

________________________________________________________________________________________________
3.  
# Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector)

    var employmentTitle = document.querySelector( '#employment h3.info-title' );

    employmentTitle.innerText = 'Something Else'

________________________________________________________________________________________________
4.  
# Change the colour of the body.

    document.body.style.background = '#223322';

________________________________________________________________________________________________
5.  
# Change the colour used by the highlight class.

    var highlight = document.querySelectorAll( '.highlight' );

    highlight.forEach( function(newColour) { newColour.style.background = '#111222' } );

________________________________________________________________________________________________
6.  
# Change the font family of the h1 to 'monospace'.

    title = document.querySelector( 'h1' )

    title.style.fontFamily = 'monospace'

________________________________________________________________________________________________
7.  
# Find a way to select the round icons in the sidebar and then change their colour.

    var roundIcons = document.querySelectorAll( '.action-icon-bg' );

    for (var i=0; i < roundIcons.length; i++) {
      roundIcons[i].style.backgroundColor = '#111222'
    }

________________________________________________________________________________________________
8.  
# Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself".

    var nameField = document.querySelector( 'input#name.contact-info' );

    nameField.placeholder = 'Identify Thyself'

________________________________________________________________________________________________
9.  
# Change the placeholder attribute of the message field to "state your business".

________________________________________________________________________________________________
10.  
# Give the name field a "value" attribute of "your nemesis".
#     Reference: http://www.w3schools.com/tags/att_input_value.asp

________________________________________________________________________________________________
11.  
# Change the value attribute of the email field to "koalathebear@gmail.com".

________________________________________________________________________________________________
12.  
# Change the value of the submit button on the contact form to "En garde!".

________________________________________________________________________________________________
13.  
# We should stop Koala from sending an email to Panda that they might regret! Find a way to disable the submit button (hint: familiarize yourself with the disabled attribute).
#     Reference: http://www.w3schools.com/tags/att_input_disabled.asp

________________________________________________________________________________________________
14.  
# We should help Panda protect their privacy by clearing their personal details from the sidebar. You can use reset() to do this.
#     Reference: https://developer.mozilla.org/en-US/docs/Web/API/HTMLFormElement/reset
