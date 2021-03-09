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


Sollte der Build fehlschlagen, können sie sich die Details dazu ansehen und so dem Fehler auf den Grund gehen.
Sie finden dazu eine detaillierte Fehlerausgabe, wenn sie auf den jeweiligen Build klicken der fehlgeschlagen ist.


![ProjektUebersicht](/wiki/circleci/build-error.png)


In diesem Beispiel sieht man gleich, dass der Build fehlgeschlagen ist, weil ein Kompilierfehler aufgetreten ist:
In der Klasse `ProjectManager.java` wurde eine Klammer vergessen was zu einem Fehler geführt hat.

Wird dieser Fehler beseitigt und der Code erneut in das GitHub Repository gepusht, startet CircleCI  automatisch  einen neuerlichen Build und das Problem sollte behoben sein.


