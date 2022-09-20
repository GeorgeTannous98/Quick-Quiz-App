A small quiz application including trivia questions from different categories.

How to run:
1) clone/download the code.
2) run the following command with docker and make sure to replace the folder path to the cloned/downloaded folder:

     docker run -d -p 8080:8080 --name web-app -v "`Path/To/quiz-app`":"/usr/src/app" duaneleem/live-server:1.0
