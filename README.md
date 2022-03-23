Task 1:
Run a docker container and in PHP print “Hello World” to the terminal
NOTE: No framework for this, all we want to see is a simple PHP script running in a Docker container.

Instructions:
1. Pull the repositorie into your local machine
2. Open terminal and goto pulled repositorie directory/folder
3. Run command
    
   For Linux/Mac
   docker run -it --rm --name Task1 -v "$PWD":/home/test1 -w /home/test1 php php task1.php

   For Windows
   docker run -it --rm --name Task1 -v %cd%:/home/test1 -w /home/test1 php php task1.php

   If command didn't work, replace the <current directory path> with the full directory path of pulled repositorie directory
   docker run -it --rm --name Task1 -v <current directory path>:/home/test1 -w /home/test1 php php task1.php