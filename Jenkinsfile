node {
    /* Requires the Docker Pipeline plugin to be installed */
    docker.image('maven:3.3.3').inside {
        stage('Build') {
            sh 'mvn --version'
            sh 'java --version'
        }
    }
}