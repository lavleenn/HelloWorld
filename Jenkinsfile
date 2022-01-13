 def app
pipeline {
    agent any
    stages{
    stage('Build image') {
        /* Let's make sure we have the repository cloned to our workspace */
        steps{
         script {app = docker.build("helloworld")}
        }
    }
    }
}
