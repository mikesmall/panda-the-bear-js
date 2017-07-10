1. Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead.
PROTIP: use the inspector to learn the dimensions of the current profile image and use a placeholder image service such as Place Bear to get an image of the same size.

        var profileImage = document.querySelector('.profile-image');

        profileImage.src = 'http://i.imgur.com/bJ9obIc.jpg';

1. Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing.

        var skyImage = document.querySelector('img[title="Man Walking on Ice"]');

        skyImage.src = 'http://i.imgur.com/V0BKDRg.jpg';

2. Select the heading that says "Panda the Bear" and change it to your own name.

        var pageTitle = document.querySelector('h1[class="highlight"]');

        pageTitle.innerText = 'Mike Small';

3. Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector)

        
