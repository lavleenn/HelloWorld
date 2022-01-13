pipeline {
    agent any
    stages{
    stage('Build image') {
        /* Let's make sure we have the repository cloned to our workspace */
        steps{
         def app = docker.build("helloworld")
        }
    }
    }
}
