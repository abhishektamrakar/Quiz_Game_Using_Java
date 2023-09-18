# Quiz Game Using Java

This is a Quiz Game with a Command Line User Interface that allows you to easily create, take, view and list the quiz. Users may easily create quizzes, play quizzes, view the questions and answers and list the quizzes that are available. The Quiz Game has a simple design, with commands like create, take, view, list and exit.

The user can use create command to create a quiz, take command to take the quiz, view command to view the quiz, list command to display all of the quizzes that are currently available and exit command to end the quiz game. The command will be quickly followed by the system which will act accordingly.

The quiz game is Command Line User Interface system. The system uses the while loop, for loop, HashMap class and Scanner class. Specified methods, such as createQuiz(), takeQuiz(), viewQuiz() and listQuiz() are used to handle the commands. Using the HashMap class and array list the quiz questions and answers are inserted into the game.

Methods used in the project:

createQuiz():

If the user gives the command to create a quiz, this method is triggered. The method initially asks for the name of the quiz, the number of questions to be added, and choices of each question, and the correct answer to the question. Once the quiz is created message is displayed.

takeQuiz():

If the user wishes to play the quiz game, the take command is used. takeQuiz() method is invoked when the take command is given to the system. Initially, the system will ask on which topic the user wants to play the quiz game. The questions are displayed with options for the given topic. At last, the achieved score is displayed to the user.

viewQuiz():

When the user gives view command to the system, the viewQuiz() method is triggered. Initially the method asks the name of the quiz, and if it is found it displays the quiz questions and its answer to the users otherwise the not found message is displayed.

listQuiz():

When the user gives list command to the system, the listQuiz() method is invoked. This method displays the list of all quiz topics that are available in the game.
