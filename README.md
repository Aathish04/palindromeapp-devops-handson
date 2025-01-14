# Hands-On Session on GitHub DevOps CI/CD - 30/10/2023

This repository contains code and instructions to be followed during the Hands-On Session on Github DevOps CI/CD. Please read through this README file carefully before and during the session.

## Prerequisites

We will need some software to be installed on your system before we can begin the session. Here's what you'll need:

1. **Git**
    - Git is a version control system that tracks changes in code. It works by creating snapshots of code over time, allowing multiple people to collaborate on a project while preserving a history of changes and enabling easy branching and merging of code.
    - The Git Guides on Github are a great source on how to install git to your system: https://github.com/git-guides/install-git

4. Now, you need to create a Github Account, if you don't have one already.
    - Follow the instructions [here](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account) to set up a new Github account.
  
Once you've done that, move onto the next piece of software you will need:

3. Java (OpenJDK 17)
    - You may already have a version of Java installed from working on other projects such as the Semester IV DBMS or Semester III OOPS project.
    - **To follow along in this session, you will need Java OpenJDK 17, so please be sure to install it.**
    - Follow the instructions [here](https://java.tutorials24x7.com/blog/how-to-install-openjdk-17-on-windows) to install OpenJDK 17 on Windows.
    - On Debian/Ubuntu/Kali, install the latest version of Java by running `sudo apt update && sudo apt install default-jdk` in the command line,
    - On MacOS, you can install Java using the instructions [here](https://www.codejava.net/java-se/install-openjdk-18-on-macos). If you have the Homebrew Package manager, you can install Java by simply running `brew install java`.

Once you've installed Java, the next piece of software you will need is:

4. IntelliJ Idea Community Edition IDE
    - Follow the instructions [here](https://www.jetbrains.com/help/idea/installation-guide.html) to install IntelliJ Idea IDE.
    - Follow the Instructions [here](https://www.jetbrains.com/help/idea/github.html) to set up GitHub Integration with IntelliJ Idea.


5. Clone/Download this repository to your computer.

6. Azure Setup
    - Set up your Microsoft Azure Student account - https://azure.microsoft.com/en-in/free/students


## Project Creation 

1. Navigate to https://start.spring.io. This service pulls in all the dependencies you need for an application and does most of the setup for you.

Choose Maven and Java. 

Click Dependencies and select Spring Web.

Click Generate.

Download the resulting ZIP file, which is an archive of a web application that is configured with your choices.

![image](https://github.com/Aathish04/palindromeapp-devops-handson/assets/33193764/80535673-ed3f-46c7-b555-626fa1b4a115)


2. Create a GitHub Repository for the project to be developed. Clone the said repository onto your local system using the "git clone name_of_repository" command.

3. Extract the contents of the ZIP file downloaded to the cloned repository.

4. Now youre ready to start working on the project!
