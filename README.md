# Project-Alex
Web-based jeopardy-style game with account management and category/question generation. Final project for the Software Engineering Course. Languages/technology used: HTML/CSS/Javascript, PHP, MYSQL

Design documentation and source code available upon request. 


![alt text](https://raw.githubusercontent.com/vmyu/Project-Alex/master/images/image_1.png)

Single-player starts a new Jeopardy game session as a guest. When playing as a guest, your game sessions and records will not be saved. Registering and logging into a CS Jeopardy account will be able to pause and resume game sessions as well as keep record of your game history and scores.

Selecting Multiplayer directs the user to the multiplayer lobby to play CS Jeopardy with other players logged online.   

What is CS Jeopardy directs new users to a set of tutorials which explain how CS Jeopardy works.
Entering your CS Jeopardy username and password directs the player to the Private Lobby where the user can see their game history, submitted answer history, are able to resume incomplete games and have the option to start a new single-player game, join an existing multiplayer sessions and start a new multiplayer session for others to join.
Visitors without a CS Jeopardy account are able to use the register form to sign-up for a new account. To sign-up, you will need an unique username and a valid email address.

![alt text](https://raw.githubusercontent.com/vmyu/Project-Alex/master/images/image_2.png)

When logged into the Multiplayer Lobby, the user will be able to see all current multiplayer sessions they are able to join. The Waiting Games list will display the game name and the number of users in the session. The user can return to the main page by clicking 'Back to Home Page'.

![alt text](https://raw.githubusercontent.com/vmyu/Project-Alex/master/images/image_3.png)

When a user logs into their CS Jeopardy account, they will be directed to the Private Lobby. The user will be able to start a new single-player game, join an existing multiplayer session, and start a new multiplayer session for others to join. Also shown are the accuracy rates of correct answers based on difficulty of all questions they have answered in their game sessions. Clicking 'View all submitted answers' will allow for the user to see their complete history of their answer submissions as well as the correct answers.
The user will be able to resume incomplete games by clicking 'Load Game' next to the desired choice. Each game is displayed with the game ID, name of user, and the start date and time of the session.

![alt text](https://raw.githubusercontent.com/vmyu/Project-Alex/master/images/image_4.png)

Clicking 'View all submitted answers' displays the user’s answer history of questions. This page shows the question itself, the user’s submitted answer, and the correct answer.

![alt text](https://raw.githubusercontent.com/vmyu/Project-Alex/master/images/image_5.png)

This is the game board. A user may quit the game (and resume at a later time) by clicking 'Quit Game' in the top right of the screen. Next the round is stated, in this image it is the 'Jeopardy' round (1st round). The user's in-game score is stated followed by the amount of time a user has to select a question. By clicking on one of the buttons on the board the user will be asked a question who's difficulty is relative to the value stated on the button. When all of the questions have been selected the following round begins, and so on until the end of the game.

![alt text](https://raw.githubusercontent.com/vmyu/Project-Alex/master/images/image_6.png)

On this screen the user is asked a question and the value of this question is stated. If the user answers the question corectly the value of the question will be credited to the user's score, if the user answers incorrectly the value will be deducted from the user's score. Next, the user selects one of the following options to answer the question. The user submits their answer by clicking the 'Submit' button. By clicking 'Skip Question' no score is added or deducted and the question will not affect the user's question submission history. Clicking 'Submit' without selecting an option is the same as clicking 'Skip Question'.

![alt text](https://raw.githubusercontent.com/vmyu/Project-Alex/master/images/image_7.png)

When a question is answered correctly this page will display green. The first item restates the question, then the correct answer is listed. Next, the user's submitted answer appears. The value of this question is then stated followed by the amount that the user's score will increase (or decrease if the number is negative). The button at the bottom of the page returns the user to the game board.

![alt text](https://raw.githubusercontent.com/vmyu/Project-Alex/master/images/image_8.png)

When a question is answered incorrectly the answer page appears red. All other items on the screen are the same as the previous image.

![alt text](https://raw.githubusercontent.com/vmyu/Project-Alex/master/images/image_9.png)

On this page the user is given a final summary of their in-game performance. This score is not added to the user's account unless the user has completed the game. The user is returned to their lobby on clicking the 'Back to Lobby' button

![alt text](https://raw.githubusercontent.com/vmyu/Project-Alex/master/images/image_10.png)

Here an administrator may choose to view user accounts in order to alter the user's score, administrative priviledges or suspend the account. The admin user may also elect to upload new question by clicking on the 'Upload New Content' button. The logout button returns you to the very first page.

![alt text](https://raw.githubusercontent.com/vmyu/Project-Alex/master/images/image_11.png)

On the Account Management page an administrator user may select an account to alter. An administrator may alter the score, administrative priviledges or suspend a user account.  By clicking 'Manage' Displayed next to the user's name the administrator will be able to alter the account on the same row as the 'Manage' button that was clicked. The back button returns you to the main admin page. The logout button returns you to the very first page.

![alt text](https://raw.githubusercontent.com/vmyu/Project-Alex/master/images/image_13.png)

This page allows an administrator user to alter the selected user account in order to change the score, make another user an administrator or disable the account as indicated by the onscreen insructions.  The back button returns you to the main admin page. The logout button returns you to the very first page.

![alt text](https://raw.githubusercontent.com/vmyu/Project-Alex/master/images/image_12.png)

This is the game board. A user may quit the game (and resume at a later time) by clicking 'Quit Game' in the top right of the screen. Next the round is stated, in this image it is the 'Jeopardy' round (1st round). The user's in-game score is stated followed by the amount of time a user has to select a question. By clicking on one of the buttons on the board the user will be asked a question who's difficulty is relative to the value stated on the button. When all of the questions have been selected the following round begins, and so on until the end of the game.


