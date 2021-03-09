

# Build Management with Maven

Maven is a build management tool from the Apache Software Foundation and is based on Java. It supports the creation and management of Java programs in a standardized way. Maven already has development environments such as InteliJ and Eclipse after installation. 

A standard Maven directory structure looks like this: 

<img src="/wiki/maven/maven-standard-structure.png" alt="Maven Directory Structure" width="400px" height="250px">

In Maven the pom.xml is the key file, all software dependencies are indicated there. This determines whether Maven has the required files in the local repository; if this is the case, the local file is used when compiling and is not copied to the project directory. If the file does not exist in the repository, Maven tries to connect via the repository on the intranet or Internet and to copy the desired files to the local repository. Well-known and public Maven repositories: Apache, Ibiblio, Codehaus or Java.net.


