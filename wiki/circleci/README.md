# Continuous Integration with CircleCI


*Continuous Integration (CI)* definition: 
```
 CI is a software development practice wherein developers regularly merge their code
 with a central repository after which automated builds and tests are run.
 ```
This means that CI tools offer the possibility to automatically compile and test the code as soon as it is committed to a repository.
 
In our case we use CircleCI (https://circleci.com), which is integrated directly with GitHub and is therefore very easy to use.

You can log into CircleCI directly with your GitHub account and should then immediately see your respective team repository in the overview. 

![ProjektUebersicht](/wiki/circleci/projects.png)

If you then select this project, you will see the status of the project and whether the last "build" (i.e. the last compilation run of the project) was successful. 


**Everything is OK!**

![ProjektUebersicht](/wiki/circleci/build-ok.png)



**Something Failed!**


![ProjektUebersicht](/wiki/circleci/build-failed.png)


If the build fails, you can look at the details and get to the bottom of the error. You will find a detailed error output if you click on the respective build that failed. 


![ProjektUebersicht](/wiki/circleci/build-error.png)


In this example you can immediately see that the build failed because a compile error occurred:
In the class `ProjectManager.java` a bracket was forgotten which led to an error.

If this error is fixed and the code is pushed into the GitHub repository again, CircleCI automatically starts a new build and the problem should be resolved. 


