# Continuous Integration with CircleCI


*Continuous Integration (CI)* bedeutet: 
```
 CI is a software development practice wherein developers regularly merge their code
 with a central repository after which automated builds and tests are run.
 ```
Das heißt, CI Tools bieten die Möglichkeit den Code automatisch zu Kompilieren und zu Testen sobald dieser in ein Repository committed wird.

In unserem Fall verwenden wir dafür CircleCI (https://circleci.com), welches direkt mit GitHub integriert ist und somit sehr leicht verwendbar ist.

Sie können sich bei CircleCI direkt mit Ihrem GitHub Account einloggen und sollten danach gleich ihr jeweiliges Team Repository in der Übersicht sehen.

![ProjektUebersicht](/wiki/circleci/projects.png)


Wenn sie dann dieses Projekt auswählen, sehen sie den Status des Projekts und ob der letze "Build" (sprich der letzte Kompilierdurchgang des Projekts) erfolgreich war.


**Bei Grün ist alles OK!**

![ProjektUebersicht](/wiki/circleci/build-ok.png)



**Bei Rot gibt es ein Problem!**


![ProjektUebersicht](/wiki/circleci/build-failed.png)


Sollte der Build fehlschlagen, können sie sich die Details dazu ansehen und so dem Fehler auf den Grund gehen.
Sie finden dazu eine detaillierte Fehlerausgabe, wenn sie auf den jeweiligen Build klicken der fehlgeschlagen ist.


![ProjektUebersicht](/wiki/circleci/build-error.png)


In diesem Beispiel sieht man gleich, dass der Build fehlgeschlagen ist, weil ein Kompilierfehler aufgetreten ist:
In der Klasse `ProjectManager.java` wurde eine Klammer vergessen was zu einem Fehler geführt hat.

Wird dieser Fehler beseitigt und der Code erneut in das GitHub Repository gepusht, startet CircleCI  automatisch  einen neuerlichen Build und das Problem sollte behoben sein.


