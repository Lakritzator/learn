# learn
This readme contains topics, with links to details, which a dotnet or java developer from my point of view should know to be successful as a developer. This document is probably never be finished, it will need changes all the time just so as developers never finish learning!

This is work in progress, there is a lot of todos.
- Add why
- Add links
- Add more topics


## generic topics

These topics are of a generic nature, and most of them can be used independent of the technology used. These topics can but don't have to be in the specific language table, if so that information is specify to the technology.

- Source Code Versioning
  
  Having a tool to version your code is very important, this enables you to track changes and separate future development features from the current version until they are ready. When not working locally and synchronizing with a server you get the added benefit of having backups, tracking the changes of everybody, doing / having code reviews and have your application build on a build server.
  Here are some examples of such systems: https://hackernoon.com/top-10-version-control-systems-4d314cf7adea and here you can see the popularity https://www.g2crowd.com/categories/version-control-systems
  - [Git](https://www.youtube.com/watch?v=SWYqp7iY_Tc)
    
    I will just mention Git, as it's more or less the defacto. And some of the online git service providers are:
    - [GitHub](https://github.com)
    - [BitBucket](https://bitbucket.org)
    - [GitLab](https://about.gitlab.com/)
- IDE

  What IDE to use is a popular discussion, in this time and age it's not really a huge problem when multiple IDEs are used inside a team. The most important feature of an IDE is having git support, and it will certainly help if the IDE knows your project structure and does color highlighting. Some people are satisfied with vi(m) and other commandline tools, but my advice is using one of the following:
  - [Visual Studio Code](https://code.visualstudio.com/)
    A free, platform independent and open source code editor.
  - [Visual Studio](https://visualstudio.microsoft.com/) (2017 / 2019)
    A versatile code editor for Windows & Mac. has a free community version.
  - [Eclipse](https://www.eclipse.org/eclipseide/)
    A free and open source code editor.
  - [IntelliJ Idea](https://www.jetbrains.com/idea/)
    A java based, platform independent, code editor. Has a free community version. I find that IntelliJ Idea is one of the best when it comes to refactoring features and language support.
- Ticket / bug reporting systems

  Without having a way to express your product with features and bugs, you will have a hard time tracking what needs to be done. Here are some solutions for this:
  - [Jira](https://www.atlassian.com/software/jira)
  - Use the issue system of your source control service
    - [GitHub](https://github.com)
    - [BitBucket](https://bitbucket.org)
    - [GitLab](https://about.gitlab.com/)
  - [Azure DevOps](https://azure.microsoft.com/en-us/services/devops/)
- Agile
  
  When working for enterprises, you will need to follow a certain methodology, currently many are using one that follows the agile way of working. You will need a basic understanding of this.
  - [Here](https://www.youtube.com/watch?v=502ILHjX9EE) is a youtube video explaining how agile can work.
  - [Here](https://www.youtube.com/watch?v=rIaz-l1Kf8w) is a YouTube video to have the differences of the most popular methods (Scrum / Kanban) explained.
- [Dependency management](https://docs.gradle.org/current/userguide/introduction_dependency_management.html)
  
  Almost no application can refrain from using other dependencies, like Framework code, Loggers etc. To be able to find, update (Lifecycle management), scan, delete all of these, a system should be used.
  - [Dependabot](https://dependabot.com/) can automatically check your dependencies and create pull requests for them.
- Code styles
  Make sure you have a code style for your project, and document this to reduce friction and questions with other developers.
  - [EditorConfig](https://editorconfig.org/)
- Code quality
  - Testing
    - Unit testing
    - Integration tests
    - Manual testing
    - UI testing
  - [Code coverage](https://www.atlassian.com/continuous-delivery/software-testing/code-coverage)
  - Static code scanning
    - Fortify
    - "Lint"
    - PMD
- [Dependency Injection (DI) / Inversion of Control (IoC)](https://en.wikipedia.org/wiki/Inversion_of_control)
- [CI/CD (Continuous Integration and Continuous Delivery)](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment)
  
  Every project should have a CI/CD system, which automatically builds, tests and "ships" your software.
  - [Jenkins](https://jenkins.io/)
  - [Azure DevOps](https://azure.microsoft.com/en-us/services/devops/)
  - [AppVeyor](https://www.appveyor.com/)
  - [TeamCity](https://www.jetbrains.com/teamcity/)
- [Docker](https://itnext.io/docker-from-the-beginning-part-i-ae809b84f89f)
  - Kubernetics

## Java 

- The language
  - [Java](https://www.learnjavaonline.org/)
  - [Kotlin](https://kotlinlang.org/) as a compatible alternative to Java
- [Spring-Framework](https://spring.io/) is a framework which offers enterprise grade Java components, helping you to build applications with little fuzz.
  - Spring-Boot
  - Spring-Cloud-Config
- Dependency management
  - [Maven](https://maven.apache.org/)
  - [Gradle](https://gradle.org)
- IDE setup
  - [Develop Java with Visual Studio Code](https://code.visualstudio.com/docs/languages/java)

## dotnet

- Languages
  - [C#](https://www.learncs.org/)
  - [F#](https://fsharp.org/learn.html)
- Dependency management
  - [NuGet](https://www.nuget.org/)
