[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15271584&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

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


ANSWER 1:
How to install windows:
Step 1: Check Compatibility

    System Requirements:
        Processor: 1 gigahertz (GHz) or faster with at least 2 cores on a compatible 64-bit processor or System on a Chip (SoC)
        RAM: 4 GB or more
        Storage: 64 GB or larger storage device
        System firmware: UEFI, Secure Boot capable
        TPM: Trusted Platform Module (TPM) version 2.0
        Graphics card: DirectX 12 compatible graphics / WDDM 2.x
        Display: >9” with HD Resolution (720p)
        Internet connection: Internet connectivity is necessary to perform updates and to download and take advantage of some features.

    Check with PC Health Check Tool:
        Download the PC Health Check tool from Microsoft.
        Install and run the tool to check if your PC meets the requirements.

Step 2: Back Up Your Data

Before proceeding with the installation, back up your important files to an external hard drive or cloud storage to prevent data loss.
Step 3: Download Windows 11

    Windows 11 Installation Assistant:
        Go to the Windows 11 download page.
        Download the Installation Assistant and run it.
        Follow the prompts to download and install Windows 11.

    Create Installation Media:
        Download the Windows 11 Media Creation Tool from the same page.
        Run the tool and select “Create installation media (USB flash drive, DVD, or ISO file) for another PC”.
        Choose your language, edition, and architecture (64-bit).
        Follow the instructions to create the installation media.

Step 4: Install Windows 11
Option 1: Upgrade from Windows 10

    Run the Installation Assistant:
        If using the Installation Assistant, it will guide you through the upgrade process.
        Your files and apps should be preserved, but back up data just in case.

Option 2: Clean Installation

    Boot from Installation Media:
        Insert the USB flash drive or DVD and restart your PC.
        Press the key (usually F2, F12, Delete, or Esc) to open the boot menu.
        Select the USB drive or DVD from the boot menu.

    Install Windows 11:
        Follow the on-screen prompts to start the installation.
        Select your language, time, and keyboard preferences, then click "Next".
        Click "Install Now".
        Enter your product key or select "I don’t have a product key" if reinstalling (Windows will activate automatically later).
        Choose the edition of Windows 11 that matches your product key.
        Accept the license terms and click "Next".
        Select “Custom: Install Windows only (advanced)” for a clean installation.
        Delete all partitions or select the partition where Windows is currently installed and click "Next". Warning: This will erase all data on the selected partition.
        The installation will begin, and your PC will restart several times.

Step 5: Set Up Windows 11

    Initial Setup:
        After the installation, you will be guided through the initial setup process.
        Select your region and keyboard layout.
        Connect to a Wi-Fi network if prompted.
        Sign in with your Microsoft account or create a local account.
        Follow the on-screen instructions to customize settings.

Step 6: Install Updates and Drivers

    Windows Update:
        Go to Settings > Update & Security > Windows Update.
        Check for updates and install any available updates.

    Drivers:
        Go to the manufacturer’s website to download and install the latest drivers for your hardware components.

Step 7: Restore Data

If you performed a clean installation, now is the time to restore your backed-up data from the external drive or cloud storage.

ANSWER 2:
HOW TO INSTALL AN IDE
For Windows:

    Download VS Code:
        Go to the Visual Studio Code website.
        Click on the "Download for Windows" button. This will download an installer file (VSCodeSetup.exe).

    Run the Installer:
        Locate the downloaded VSCodeSetup.exe file and double-click to run it.
        If prompted by User Account Control, click "Yes" to allow the installer to run.

    Install VS Code:
        Read and accept the license agreement, then click "Next".
        Choose the destination folder for the installation and click "Next".
        Select additional tasks (e.g., create a desktop icon) and click "Next".
        Click "Install" to begin the installation process.
        Once the installation is complete, you can choose to launch VS Code immediately.

    Launch VS Code:
        Open VS Code from the Start menu or desktop shortcut.

ANSWER 3:
HOW TO SETUP GIT
   Step 1: Install Git
For Windows:

    Download Git:
        Go to the Git for Windows website.
        Download the installer.

    Run the Installer:
        Locate the downloaded Git-2.x.x-64-bit.exe file and double-click to run it.
        Follow the installation instructions, keeping the default options unless you have specific preferences.
        Open your terminal or Git Bash (on Windows).

Set your username:
git config --global user.name "Your Name"

Set your email:
git config --global user.email "your.email@example.com"

Verify your configuration:
    git config --list
    This command lists all your Git configuration settings.

Step 3: Initialize a Git Repository

    Navigate to your project directory:
cd /path/to/your/project

Initialize a new Git repository:
git init

Add files to the repository:
git add .

This adds all files in the current directory to the staging area. Use git add <filename> to add specific files.
Commit the files:

    git commit -m "Initial commit"

Step 4: Connect to a Remote Repository

    Create a repository on a hosting service like GitHub, GitLab, or Bitbucket.

    Copy the repository URL.

    Add the remote repository:

    sh

git remote add origin <repository-url>

Replace <repository-url> with the URL you copied.

Push your changes to the remote repository:

sh

    git push -u origin master

    The -u flag sets the upstream branch, so future pushes can be done with git push.

Step 5: Use Git in Visual Studio Code

    Open VS Code.

    Install the Git Extension (if not already installed):
        Go to the Extensions view by clicking on the Extensions icon in the Sidebar or pressing Ctrl+Shift+X (Windows/Linux) or Cmd+Shift+X (macOS).
        Search for "Git" and install the official Git extension.

    Open your project folder:
        Go to File > Open Folder and select your project directory.

    Access Git features in VS Code:
        Use the Source Control view by clicking the Source Control icon in the Sidebar or pressing Ctrl+Shift+G (Windows/Linux) or Cmd+Shift+G (macOS).
        Here you can see changes, commit, push, pull, and manage branches.

ANSWER 4:
HOW TO SETUP AND INSTALL PYTHON
For Windows:

    Download Python:
        Go to the official Python website.
        Click on the "Downloads" tab and then click "Download Python 3.x.x" (where x.x is the latest version).

    Run the Installer:
        Locate the downloaded python-3.x.x.exe file and double-click to run it.
        Check the box that says "Add Python to PATH".
        Click "Install Now" or choose "Customize installation" to select optional features and the installation path.

    Verify the Installation:
        Open Command Prompt.
        Type python --version and press Enter. You should see the installed Python version.
        Type pip --version and press Enter to verify that pip (Python's package installer) is also installed.

            Verify the Installation:
        Open Terminal.
        Type python3 --version and press Enter. You should see the installed Python version.
        Type pip3 --version and press Enter to verify that pip is also installed.

Step-by-Step Guide for Using Python in Visual Studio Code

    Install VS Code:
        If you haven't already installed Visual Studio Code, download and install it from the official VS Code website.

    Install the Python Extension:
        Open VS Code.
        Go to the Extensions view by clicking on the Extensions icon in the Sidebar or pressing Ctrl+Shift+X (Windows/Linux) or Cmd+Shift+X (macOS).
        Search for "Python" and install the official Python extension by Microsoft.

    Configure the Python Interpreter:
        Open the Command Palette by pressing Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (macOS).
        Type Python: Select Interpreter and select it.
        Choose the Python interpreter you want to use.

    Verify the Setup:
        Create a new Python file (.py).
        Write a simple Python script, such as:

        python

print("Hello, World!")

Run the script by clicking the "Run" button in the top right corner of the editor or by pressing Ctrl+F5 (Windows/Linux) or Cmd+F5 (macOS).


ANSWER 5:
HOW TO INSTALL AND SETUP PIP
Step 1: Check if Python and pip are already installed

    Open Command Prompt:
        Press Win + R, type cmd, and press Enter.

    Check Python installation:
        Type python --version and press Enter.
        If Python is installed, it will show the version number. If not, you'll need to install Python first (see Step 2).

    Check pip installation:
        Type pip --version and press Enter.
        If pip is installed, it will show the version number. If not, you'll proceed with the installation steps below.

Step 2: Install Python (if not already installed)

    Download Python:
        Go to the official Python website.
        Click on the "Downloads" tab and then click "Download Python 3.x.x" (where x.x is the latest version).

    Run the Installer:
        Locate the downloaded python-3.x.x.exe file and double-click to run it.
        Important: Check the box that says "Add Python to PATH".
        Click "Install Now" or choose "Customize installation" to select optional features and the installation path.

Step 3: Install pip (if not already installed)

    Download get-pip.py:
        Open a web browser and go to the get-pip.py script.
        Right-click on the page and select "Save As" to download the get-pip.py script to your computer.

    Run the get-pip.py script:
        Open Command Prompt.
        Navigate to the directory where you saved get-pip.py using the cd command. For example:

        sh

cd C:\path\to\directory

Run the script by typing:

sh

        python get-pip.py

Step 4: Verify the Installation

    Check pip installation:
        Open Command Prompt.
        Type pip --version and press Enter.
        This should display the version of pip installed.

Troubleshooting

    Add Python and pip to PATH manually:
    If you didn't check the "Add Python to PATH" box during installation, you might need to add Python and pip to your PATH manually.
        Open the Start menu and search for "Environment Variables".
        Select "Edit the system environment variables".
        In the System Properties window, click the "Environment Variables" button.
        In the Environment Variables window, find the "Path" variable in the "System variables" section and click "Edit".
        Click "New" and add the path to your Python installation directory (e.g., C:\Python39 or C:\Users\YourUsername\AppData\Local\Programs\Python\Python39).
        Click "New" again and add the path to the Scripts directory inside your Python installation directory (e.g., C:\Python39\Scripts or C:\Users\YourUsername\AppData\Local\Programs\Python\Python39\Scripts).
        Click "OK" on all windows to apply the changes.

    Ensure you have administrative privileges: If you encounter permission errors, try running Command Prompt as an administrator.

ANSWER 6:
HOW TO INSTALL, SETUP AND CONFIGURE SQL
Step 1: Download SQL Server

    Visit the SQL Server Download Page:
        Go to the Microsoft SQL Server downloads page.

    Choose Your Edition:
        Select the appropriate edition for your needs:
            SQL Server Developer: A full-featured free edition, licensed for use as a development and test database in a non-production environment.
            SQL Server Express: A free edition of SQL Server ideal for development and production for desktop, web, and small server applications.
        Click "Download now" for the edition you choose.

Step 2: Install SQL Server

    Run the Installer:
        Locate the downloaded installer file (e.g., SQL2019-SSEI-Dev.exe for Developer edition) and double-click to run it.

    Choose Installation Type:
        The installer will prompt you to choose an installation type. For a basic setup, select "Basic".

    Accept License Terms:
        Read and accept the license terms, then click "Next".

    Choose Install Location:
        Select the installation path or accept the default location, then click "Install".

    Installation Process:
        The installer will download the necessary files and install SQL Server. This may take a few minutes.

    Installation Complete:
        Once the installation is complete, you’ll see a summary screen. Note the "Instance name" and other details provided.

Step 3: Install SQL Server Management Studio (SSMS)

    Download SSMS:
        Go to the SQL Server Management Studio download page.

    Run the Installer:
        Locate the downloaded installer file (e.g., SSMS-Setup-ENU.exe) and double-click to run it.

    Install SSMS:
        Follow the installation prompts. Accept the license terms, choose the installation path, and click "Install".
        The installation process may take several minutes.

Step 4: Configure SQL Server

    Launch SSMS:
        Open SQL Server Management Studio from the Start menu.

    Connect to SQL Server:
        In the "Connect to Server" window:
            Server type: Database Engine
            Server name: The instance name noted during SQL Server installation (e.g., DESKTOP\SQLEXPRESS or localhost).
            Authentication: Select "Windows Authentication" for simplicity.
        Click "Connect".

    Create a New Database:
        In SSMS, right-click the "Databases" folder in the Object Explorer.
        Select "New Database...".
        Enter a database name and click "OK".

    Create a New User (Optional):
        Expand the "Security" folder, right-click "Logins", and select "New Login...".
        Enter a login name, select "SQL Server authentication", and set a password.
        Under "User Mapping", map the login to your new database and assign roles as needed.
        Click "OK".

Step 5: Verify the Installation

    Run a Test Query:
        Open a new query window by clicking "New Query" in SSMS.
        Run a simple SQL command like:

        sql

        SELECT @@VERSION;

        Execute the query by clicking "Execute" or pressing F5.

Additional Tips

    Firewall Configuration:
    If you need to allow remote connections to your SQL Server, make sure to configure the Windows Firewall to allow SQL Server traffic. You may need to open TCP port 1433.

    SQL Server Configuration Manager:
    Use SQL Server Configuration Manager to manage SQL Server services, configure network protocols, and manage SQL Server network configuration.

    Backup and Restore:
    Regularly back up your databases and learn how to restore them to prevent data loss.


ANSWER 9:
NO CHALLENGES FACED
   
