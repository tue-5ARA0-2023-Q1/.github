# Getting Started

The course uses Python with the Visual Studio Code (VSCode) integrated development environment (IDE) and Anaconda package manager. In the following we explain how to set-up your development environment, and how to get started with the assignments. The setup and assignments are tested for Windows 10 and the respective versions as mentioned below. Unfortunately we cannot support other versions or operating systems. In case of problems, please first consult the FAQ on the Canvas discussions page.


_Install VSCode_

VSCode is a popular Integrated Development Environment (IDE) for many programming languages. VSCode incorporates auto-completion, syntax and style-checks, Git integration and many other handy features. Navigate to `https://code.visualstudio.com/`, and install the latest version for Windows (if not already installed). When opening VSCode for the first time, choose "Browse Language Extensions" and install the extensions for Python and Jupyter.


_Install Anaconda_

Anaconda is a package manager and environment manager for Python. TUe laptops already come with Anaconda Navigator installed. You can verify by opening a PowerShell from the Start Menu and typing `conda --version`, which should return the version number. If you do not have Anaconda, navigate to `https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links` and install the latest Miniconda3 for Windows. Then open Anaconda Prompt from the Start Menu and type `conda init powershell` to be able to open Anaconda from Windows PowerShell (which will be handy). Verify your installation by typing  `conda --version` and `python --version`, which should return your conda version and Python version for the base environment.


_System Paths_

Check whether your system supports long file paths. By default Windows only allows file paths up to 260 characters, which is insufficient for some of the packages that we will use. In order to check/change this, open the Registry Editor and navigate to HKEY_LOCAL_MACHINE -> SYSTEM -> CurrentControlSet -> Control -> FileSystem and make sure the LongPathsEnabled item is set to 1.


_Install Git Bash for Windows_

Git Bash is a standalone command-line interface for Git. Navigate to `https://git-scm.com/downloads` and install the latest Git Bash for Windows.


_Setup GitHub_

GitHub is an online hosting platform for code-related projects. In this course you will use GitHub to host your work and collaborate with peers on a shared code-base. Assuming you already have a GitHub account, navigate to `https://docs.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account` and follow the instructions to setup your SSH keys. Note that this may require you to generate a new SSH key.


_Assignments_

With your environment setup, you can start the assignments. The assignments are divided into three projects, and will be shared via a GitHub Classroom invitation.

1. A Git and Github tutorial, where you'll learn to use basic version control (individually, week 1);
2. The development and training of an application for mushroom foragers that classifies mushroom edibility (individually, week 2,3);
3. The development and training of a pokerbot, an agent that plays Kuhn poker against fellow students (group, week 4-8).
