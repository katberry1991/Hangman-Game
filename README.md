# Homework: Hangman-Game
Phrase/Word Guessing Game

Try to enter the correct phrase/word using the buttons at the bottom of the screen until word is correctly entered or until  attempts are depleted.

Letters should reveal themselves as letters are correctly entered, lives should be counted, number of guesses remaining should be counted as well. 

Technologies Used

HTML
CSS
Javascript

HTML was used to create the basic structure of the pages. CSS was applied to style pages and allow game to be viewable across various screen widths by adding media queries (example shown below). Lastly, Javascript was utilized to allow funcitionality with the use of arrays to list words/phrases for player to guess, and "onclick" functionality for buttons to start the game and select letters (array and "onclick" examples shown below). 

Media Query Example: 
@media (max-width: 450px){
    #restriction{
        right: 60px;
        bottom: 15px;
        font-size: 10px;
    }
}

Array Example:
var authors = ["Bradbury", "Salinger", "Wittlinger", "Twain", "Asimov", "Hemingway", "Steinbeck", "Picoult", "Zindel", "Capote", "Harper Lee", "Frost", "Whitman", "Silverstein", "Rowling", "Emerson", "Vonnegut", "Fitzgerald", "Poe", "Hawthorne", "Morrison", "Melville", "Applegate", "Faulkner", "Angelou", "Dahl"];  

onclick Example:
 <div id="phrases" onclick="phrase()">Authors</div>
 
 Acknowledgements
 How to code a hangman game - HTML, CSS, JavaScript (w/ source code) by Joe Reisigl 
