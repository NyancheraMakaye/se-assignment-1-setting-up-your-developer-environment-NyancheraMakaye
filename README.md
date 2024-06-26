[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15292002&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

a. Download Windows 11:
- Visit the official Microsoft website: [Windows 11
Download](https://www.microsoft.com/software-download/windows11).
- Download the Windows 11 Installation Assistant.
- Run the downloaded file and follow the on-screen instructions to upgrade or install
Windows 11.
![alt text](<Screenshot (3).png>)

b. Installation Process:
- Ensure your PC meets the minimum system requirements.
- Back up your important files.

- Follow the installation steps, including selecting the installation type, partitioning
your hard drive if necessary, and configuring initial settings.

c. Post-Installation Setup:
- Configure your user account, regional settings, and privacy settings.
- Install necessary drivers and updates.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

a. Download VS Code:
- Visit the Visual Studio Code download page: [VS Code
Download](https://code.visualstudio.com/Download).
- Select the appropriate version for Windows and download the installer.
![alt text](<Screenshot (4).png>)
b. Installation Process:
- Run the downloaded installer.
- Follow the installation wizard, accepting the license agreement and choosing the
installation location.
- Select additional tasks such as adding to PATH and creating a desktop icon.

c. First Launch and Setup:
- Launch VS Code and install recommended extensions like Python, GitLens, and
Docker.




3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   a. Install Git:
- Download Git from the official site: [Git Download](https://git-scm.com/downloads).
- Run the installer and follow the setup instructions, choosing your preferred options for
PATH, line endings, and other settings.
![alt text](<Screenshot (6).png>)
b. Create a GitHub Account:
- Visit [GitHub](https://github.com) and sign up for a new account if you still need to
get one.
![alt text](<Screenshot (7).png>)
3. Initialize a Git Repository:
- Open Git Bash or the terminal in VS Code.
- Navigate to your project directory or create a new one:
```bash
mkdir my_project
cd my_project
```
- Initialize a Git repository:
```bash
git init
```
- Create a README file:
```bash
echo "# My Project" >> README.md
```
- Add the README file to the staging area:
```bash
git add README.md
```
- Commit the changes:

```bash
git commit -m "Initial commit"


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
a. Download Python:
- Visit the official Python website: [Python
Download](https://www.python.org/downloads/).
- Download the latest version of Python for Windows.
c:\Users\user\Pictures\Screenshots\Screenshot (8).png
b. Installation Process:
- Run the installer, ensure you check the option to add Python to PATH.
- Follow the installation wizard.
c. Verify Installation:
- Open Command Prompt and type:
```bash
python --version
```
- Verify pip installation:
```bash
pip --version


5. Install Package Managers:
   If applicable, install package managers like pip (Python).
Verification of pip Installation:
1. Verify pip:
- Open Command Prompt and type:
```bash
pip --version


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
a. Download MySQL:
- Visit the MySQL download page: [MySQL
Download](https://dev.mysql.com/downloads/windows/installer/5.7.html).
- Download the MySQL Installer for Windows.
c:\Users\user\Pictures\Screenshots\Screenshot (9).png
c:\Users\user\Pictures\Screenshots\Screenshot (10).png
b. Installation Process:
- Run the MySQL Installer and follow the setup wizard.
- Choose the setup type (e.g., Developer Default).
- Configure MySQL Server settings, including the root password.

c. Verify Installation:
- Open MySQL Workbench or MySQL Shell and connect to your MySQL server.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
Optional Steps for Installing and Setting Up Docker:
a. Download Docker:
- Visit the Docker Desktop download page: [Docker
Download](https://www.docker.com/products/docker-desktop).
- Download and run the Docker Desktop installer.
![Docker Download](images/docker-download.png)
b. Installation Process:
- Follow the installation instructions.
- Start Docker Desktop and follow the setup wizard.
NB:NOT OPTED FOR
c. Verify Installation:


8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
c:\Users\user\Pictures\Screenshots\Screenshot (11).png

challenges  Configuring the Root Password in mysql
- Solution: Followed a step-by-step tutorial and used the official MySQL(not yet solved)
documentation for troubleshooting.
9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

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
