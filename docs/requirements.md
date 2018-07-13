# Flash Card Application

Flash cards are slips of paper with a term on one side and its definition on the reverse. Students use them to learn new vocabulary by shuffling the deck, then working through it one card at a time, guessing the term (if the definition is face up) or the definition (if the term is face up). In this project, you will write a web application that helps a user construct and then review a virtual flash card deck.

## Minimum Requirements

Your application should, minimally:

1. Use PHP/Laravel and PostgreSQL.
2. Have a github repository.
3. Require users to log in before displaying or managing the content of their deck.
4. Allow users to add, edit, and delete individual cards. Each card has a term and a definition (both are strings/text).
5. Provide a page where users can review their deck, one card at a time, showing both the term and the definition together. Some kind of control must be present to allow users to move from one card to the next.
6. Follow the design guidelines you've been learning from Jacqueline.

To turn in your project for grading, publish it to Heroku and post links to your repo and Heroku application in the #project3 Slack channel.

## If you complete the minimum requirements, consider one or more of the following enhancements...

* Allowing users to view the deck in alphabetical order by term, or with a random shuffle.
* Allowing users to review their deck by terms only, by definitions only, or by a random combination of both. Provide a control in the interface that reveals the missing information. (This simulates turning a card over in a physical flash card deck.)
* Adding controls so that users can mark whether they got the answer right or wrong. Continue presenting cards that were marked wrong until the user gets them right.
* Allowing users to move forward and backward through the deck.
* Animating the card flip.
* Allowing users to create more than one deck. Allow cards to belong to more than one deck.
* Allowing users to mark decks as public or private. Public decks should be viewable by guest users. Logged-in users should be given the option to view their own decks, public decks, or both.
* Allowing decks to contain images for definitions instead of text.
* Allowing decks to contain images in definitions in addition to text.
* Supporting mathematical notation in definitions.

Or, think up your own additional features.

Be creative and have fun!
