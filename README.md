# Integrating_SonarQube_With_MavenProject

## Table of Contents
- [Description](#description)
- [Usage](#usage)
- [Tools and Technologies](#tools-and-technologies)
- [Integrate SonarQube with the application](#integrate-sonarqube-with-the-application)
- [Links](#links)
- [Credits](#credits)

## Description
SonarQube is an open-source platform designed to help development teams continuously inspect the quality of their source code. It is primarily used for code quality management, static code analysis, and the identification of code issues and vulnerabilities. SonarQube provides a centralized platform where developers can analyze, measure, and track the quality of their code throughout the software development lifecycle.
SonarQube is a valuable tool for maintaining code quality, reducing technical debt, and enhancing the overall reliability, security, and maintainability of software projects. It is commonly used by development teams, quality assurance teams, and DevOps teams to ensure that code meets established standards and remains of high quality throughout the development process.

## Usage
* Static Code Analysis: SonarQube scans the source code of a project to identify coding issues, bugs, security vulnerabilities, and code smells (code that may not be a bug but is poorly written and may lead to issues).
* Code Quality Metrics: It calculates various code quality metrics, such as code coverage, code duplication, complexity, and maintainability, helping development teams make informed decisions about code improvements.
* Continuous Integration and Continuous Deployment (CI/CD) Integration: SonarQube can be integrated into CI/CD pipelines to automatically analyze code quality and fail the build if code quality standards are not met.
* Security Scanning: It includes security-focused analyzers that can identify common security vulnerabilities in the code, such as SQL injection, cross-site scripting (XSS), and more.
* Customizable Rules: SonarQube allows teams to define custom coding rules and quality standards tailored to their specific project requirements.
* Reporting and Visualization: It provides reports and visual dashboards that show the overall code quality and the progress of code improvements over time.
* Historical Data: SonarQube keeps historical data, allowing teams to track code quality trends and improvements over multiple code revisions.

## Tools and Technologies
* IntelliJ IDEA CE
* GitHub
* Java
* Mockito
* SonarQube

## Integrate SonarQube with the application
* Installing Local Instance of SonarQube:
  * Download and install Java 17 on your system. 
  * Download the SonarQube Community Edition zip file. (https://www.sonarsource.com/products/sonarqube/downloads/)
  * As a non-root user, unzip it in, for example, C:\sonarqube or /opt/sonarqube.
  * As a non-root user, start the SonarQube server:
    * On Windows, execute:
      * C:\sonarqube\bin\windows-x86-64\StartSonar.bat
    * On other operating systems, as a non-root user execute:
      * /opt/sonarqube/bin/<OS>/sonar.sh console
  * Once your instance is up and running, Log in to http://localhost:9000 using System Administrator credentials:
    * login: admin 
    * password: admin
    
* Analysing a Project:
  * Select Create new project. 
  * Give your project a Project key and a Display name and select Set up. 
  * Under Provide a token, select Generate a token. Give your token a name, select Generate, and click Continue. 
  * Select your project's main language under Run analysis on your project, and follow the instructions to analyze your project. Here you'll download and execute a scanner on your code (if you're using Maven or Gradle, the scanner is automatically downloaded).

## Links
* GitHub: 

## Credits:
* Parul Raj
