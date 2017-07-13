# Take the "time travel" skill off the page, by accessing the parentElement of the Panda skill and using remove().

  var timeTravelBar = document.querySelectorAll( '.bar-default' )[2];

  var timeTravelText = document.querySelector( '#time-travel' );

  timeTravelBar.removeChild( timeTravelText );

________________________________________________________________________________________________
# That drawing of Pikachu is really cute. Let’s duplicate it using cloneNode() and insert it at the bottom of the .portfolio-container using insertAdjacentHTML() or appendChild().

  var pikachu = document.querySelector("#right-image img[src]");

  var pikachuClone = pikachu.cloneNode();

  var portfolioContainer = document.querySelector(".portfolio-container");

  portfolioContainer.appendChild(pikachuClone)

________________________________________________________________________________________________
# Wow, that was so satisfying I think we should do it 10 more times. Use a for loop to help you do this.

  for (i = 0; i < 10; i++) {portfolioContainer.appendChild(pikachu.cloneNode())};

________________________________________________________________________________________________
# At this point our new elements are attached to each other but are still floating in the void separate from our webpage's DOM.

# It's up to you to go through the same process for the second span that will go in the right-hand column of the <ul> (below Panda's phone number). Look up the docs for the Date class to find a way of displaying the current date inside your next text node.

# After that, find a way of selecting the <ul> and append the new <li> to it. For bonus marks, apply the correct classes to these new elements of yours so the styling is consistent with the rest of the list items.

# Provided code:

var listItem = document.createElement('li');

var leftSpan = document.createElement('span');

var lastUpdated = document.createTextNode('Page last updated on');

leftSpan.appendChild(lastUpdated);

listItem.appendChild(leftSpan);

# Solution:
