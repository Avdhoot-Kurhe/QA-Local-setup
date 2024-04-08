<h1 align="center">QA Testing Setup Guide - Windows </h1>

This guide will walk you through setting up your local environment for QA testing. Ensure you follow each step carefully.

## Prerequisites

Before you begin, make sure you have the following software installed:

- Java 17
- Latest version of Python
- Visual Studio Code (VS Code)
- Git
- Gradle

## 1: Install Java

1. Download and install Java 17 from the official Oracle website or your package manager.
   <br/>
   <a href="https://download.oracle.com/java/17/latest/jdk-17_windows-x64_bin.exe">Java Download</a>
   <br/>
   <a href="">Java Installation Documents</a>

## 2: Install Python

1. Download and install the latest version of Python from the official website or your package manager.
   <br/>
   <a href="https://www.python.org/ftp/python/3.12.2/python-3.12.2-amd64.exe">Python Download</a>
   <br/>
   <a href="">Python Installation Documents</a>

## 3: Install Visual Studio Code (VS Code)

1. Download and install Visual Studio Code from the official website or your package manager.
   </br>
   <a href="https://code.visualstudio.com/Download">VS-Code Download</a>

3. Open VS Code and install any necessary extensions for Java and Python development.

## 4: Install Git

1. Download and install Git from the official website or your package manager.
   <a href="https://github.com/git-for-windows/git/releases/download/v2.44.0.windows.1/Git-2.44.0-64-bit.exe">Git Download</a>
3. Configure Git with your name and email using the following commands:
```
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

## 5: Install Gradle

1. Download and install Gradle from the official website or your package manager.
   </br>
   <a href="https://services.gradle.org/distributions/gradle-8.7-all.zip">Gradle Download</a>
2. Ensure Gradle is added to your system PATH.

## 6: Verify Installations

1. Open a terminal or command prompt.
2. Run the following commands to verify installations:

```bash
java -version
python --version
code --version
git --version
gradle --version
