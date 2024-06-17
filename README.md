[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15206396&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   I have choosed windows 10 because of my Hardware specification.
   windows 11 have good features to work on it.
   Here is the steps to install windows 11: 
   Using the Installation Assistant:
      1. Check System Requirements
      2. Backup Your Data
      3. Download Windows 11 from the link provided above 
      4. Run the downloaded file and follow the on-screen instructions to upgrade to Windows 11.
   Downloading the ISO file: 
      1. Download the ISO file
      2. Create Bootable Media use tool like refuse to create bootable USB drive from the ISO file.
      3. install windows 11 with following instructions

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   For me VS code is my choice because of it's flexiebility
   here is steps to install VS Code: 
      1. Download the Installer from the link provided above or from thier official website
      2. Run the Installer
      3. Follow the Setup Wizard
      4. Install

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   To install Git:
      1. Download the installer form the official website https://www.git-scm.com/
      2. Follow the Setup Wizard
      3. Complete the Installation
      4. Verify the Installation using the command --vertion on cmd
   How to configure in local machine
      1. Set name using the command git config --global user.name "Name" 
      2. Set Email using the command git config --global user.email "Email"
      3. Verify configration using the command git config --list
   How to create GitHub account for hosting repositories
      1. Go to the website https://github.com
      2. Sign Up for an account 
      3. Enter detail
      4. Verify account
      5. create repository 
      6. Enter detail about repository name ...
   Initialize a Git repository for project and make first commit
      1. To initialize use the git init command on desired directory
      2. clone or add files we want to push
      3. use git commit -m "Initialize commit" command to make commit
      4. use git add . command to push that all we made
      5. using git push command we can upload to the GitHub repository

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
   How to install python
      1. Run python Installer
      2. Customize Installation Options
      3. Start Installation
      4. Verify Installation
      5. Install pip and additional tools

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   If Python is installed correctly, pip should come bundled with it. However, depending on the system and Python installation method, it may need to verify or install pip separately. Here’s how to ensure pip is installed and ready to use:
      1. To check weather if it is insataled, use this command pip --version
      2. If not download get-pip.py script from official website

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   Steps to download and install MySQL database on windows:
      1. Go to official website https://dev.mysql.com/downloads/windows/installer/5.7.html
      2. Download the installer
      3. Run
      4. Follow the setup wizard and customize Installation opition
      5. Install
7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
   Both Docker and virtual machines are excellent tools for achieving isolated project dependencies and consistent environments. 
   Choosing the right tool depends on specific needs:
      1. For modern applications with well-defined dependencies, Docker is a great choice due to its speed, efficiency, and portability.
      2. f you need to run legacy applications, require stricter isolation, or want more flexibility in terms of supported operating systems, then VMs are the way to go.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   My chosen text editor or IDE is VS Code.
   Available extensions, plugins, and add-ons for VS Code editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration:
      1. Syntax Highlighting: Better TOML
      2. Linting: Pylint
      3. code formatting: Prettier
      4. Version Control Integration: GitLens

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
    This document outlines the steps taken to set up my development environment, including chosen tools, configurations, customizations, and any troubleshooting encountered.
      1. Operating System:
         OS: [Windows 10]
      2. Text Editor/IDE:
         Software: [Visual Studio Code]
         Configuration:
            Theme: [One Dark Pro]
      3. Development Tools:
            Version Control System (VCS): Git
            Configuration: name and Email setted.
      4. Troubleshooting:
            dependency conflicts

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
