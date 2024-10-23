task 1: In this task, I created a folder called `GitHub_task` on my local system and added a simple C program that prints "Hello World!" to the console. I then pushed this folder to the GitHub repository.
commands used:
mkdir GitHub_task: Created new directory called "GitHub_Task"
cd GitHub_task: changed directory to the newly created one
touch hello_world.c: Created an empty C file named `hello_world.c`. Wrote the C program to print "Hello World!".
git init: initialised a new git repository
git add hello_world.c: Staged the `hello_world.c` file for commit
git commit -m "Added hello_world.c to print Hello World": Committed the file to the local repository with a message.
git remote add origin https://github.com/MRM-AIA-TP-2026/MRM_AnanyaMishra.git: Added the remote GitHub repository to the local Git setup.
git push -u origin master:  Pushed the local commit to the remote repository on GitHub.
