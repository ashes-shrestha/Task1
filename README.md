**Task 1:**
Run a docker container and in PHP print “Hello World” to the terminal
NOTE: No framework for this, all we want to see is a simple PHP script running in a Docker container.

Prerequisite:
**Docker**

**Instructions:**
1. Clone/Download the repository into your local machine
2. Open terminal and goto the repository directory/folder
3. Run command:
    
  **For Linux/Mac**
   
   docker run -it --rm --name Task1 -v "$PWD":/home/test1 -w /home/test1 php php task1.php
   

   **For Windows**
   
   docker run -it --rm --name Task1 -v %cd%:/home/test1 -w /home/test1 php php task1.php
   

   **If command didn't work, replace the <path> with the full directory path of repository directory**
    
   docker run -it --rm --name Task1 -v <path>:/home/test1 -w /home/test1 php php task1.php
