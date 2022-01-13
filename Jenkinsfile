pipeline {
    def app
    stages{
    stage('Build image') {
        /* Let's make sure we have the repository cloned to our workspace */
        steps{
            app = docker.build("helloworld")
        }
    }
    }
}
