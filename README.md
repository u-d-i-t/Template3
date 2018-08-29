# Alexa Math Geek

This is the code for a new Alexa Skill that helps kids and adults alike practice and strengthen basic math facts.  This code is designed and built to run in AWS Lambda.

Included files are:

* [math_geek.py](math_geek.py) - Python code to deploy in Lambda
* [math_geek_intent.json](math_geek_intent.json) - Alexa Intent Schema
* [math_geek_utterances.txt](math_geek_utterances.txt) - Alexa Sample Utterances

## Voice User Interface Design

Here is the voice interaction design for math geek indicating the intended flow through the application.  Red blocks indicate potential entry points, and arrows follow through the application logic.  Purple blocks are areas where the action taken depends on where in the application the user currently is.  For example, if a user says a number, the program will either consider it an answer to the last asked qeustion, or adjust the difficulty level of the game depending on what was last asked.



