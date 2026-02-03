# Exercise 11.1 Warming up

In a scenario where a team of 6 developers are almost ready to release their Java application, some precautions have to be made. The precautions are linting, testing and building the application.
For linting with Java, [Checkstyle](https://checkstyle.org/) or [SonarQube](https://www.sonarsource.com/products/sonarqube/) are the popular choices.
When it comes to testing, [JUnit](https://junit.org/) takes care of unit testing where you can also implement [Mockito](https://site.mockito.org/) to mock dependencies of the class being tested
Some popular tools for the building phase are, [Apache Maven](https://maven.apache.org/) and [Gradle](https://gradle.org/).
When doing the continuous integration step, there are many different services available to choose from. 
Many of the big cloud providers also come in with for example [AWS CodePipeline](https://aws.amazon.com/codepipeline/) and [Azure Pipelines](https://azure.microsoft.com/en-us/products/devops/pipelines).
But there are also other providers such as [GitLab](https://about.gitlab.com/solutions/continuous-integration/) which works in a similar manner to Github Actions
When it comes to choose if the setup should be self-hosted or in a cloud-based environment, it depends on what the application is. If the application has no special requirements the better choice is to go cloud.
This makes configuration simple and skips the process of setting up personal servers which will keep costs down.
A self-hosted option would be valid in a much bigger development environment where multiple teams can utilise the server and also afford the constant upkeep costs included with it.
