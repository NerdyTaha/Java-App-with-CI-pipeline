# Java-App-with-CI-pipeline
This is a repository for demonstrating CI pipelines built using Github Actions. This repo includes making Docker image of an app and pushing it to a repository with an automated CI pipeline.

=======

##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
>>>>>>> 10c5fe0 (Taha doing initial commit of all code files)
