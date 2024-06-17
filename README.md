[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15282227&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   My machine is new and it came with windows 11 
![alt text](<Screenshot 2024-06-17 001749 windows.png>)
2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
Visual studio code installed 
![alt text](<Screenshot 2024-06-17 0019 Vs code .png>)
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Git hub account alraedy set up and created a reposity Thandeshnie and linked to git bash 
used git  config --global user.name "Thandeshnie"
git config --global user.email"thandeshnie12@gmail.com

![alt text](<Screenshot 2024-06-17 002516git.png>)
![alt text](<Screenshot 2024-06-17 002547git hub.png>)
4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  Python installed 
![alt text](<Screenshot 2024-06-17 002616py.png>)
5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   Intalled 
![alt text](<Screenshot 2024-06-17 002642pip.png>)
6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   
   Installed !
![alt text](<Screenshot 2024-06-17 002704my sql.png>)

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

1.Creating git hub account and adding resipository
2.Install git (Git bash and extension GUI and CMD )
- git  config --global user.name "Thandeshnie"
-git config --global user.email"thandeshnie12@gmail.com
-git init
-git clone <https://github.com/Thandeshnie/Thandeshnie.git>
-git add .
-git add <project>
-git commit -m "Your commit message"
-git push origin master
3.Installing Vs code and learning to navigate on it and additin it to environment 
4.Installing python and ensuring add it to path. checking its version on git bash through command python -version 
-Activate virtual environment with source/Scripts/activate on Git Bash 
-Installed python packages
5.Mysql,I nstalled Sql and adde it environment and also add to path 
-Verify the installation by running mysql --version in Git Bash.
-Installed mysql packages 
6.Django - Mkdir Plpproject
-cd Plpproject
-pip install virtualenv
-python -m virtualenv  Plpproject
-source plpproject/Scripts/activate
-cd myplpproject
-pip install django
django-admin startpoject plpproject_ecommerce
-cd plpproject_ecommerce
-py manage.py startapp plpproject_app
-ls
-code .
7. Challanges that I came accros is that on vs code after setting up every thing , I couldnot push my conntact to the website. The installation was successfull just that my content did not push throug to the web. 
![alt text](<Screenshot 2024-06-17 174644 product list.png>)

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
