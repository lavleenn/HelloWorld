node {
    def app

    stage('Build image') {
        /* Let's make sure we have the repository cloned to our workspace */

        app = docker.build("HelloWorld")
    }
}
