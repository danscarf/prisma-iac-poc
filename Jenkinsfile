node {
    /* Requires the Docker Pipeline plugin to be installed */
    docker.image('maven:3.6.3-jdk-11-openj9').inside {
        stage('Build') {
            sh 'mvn --version'
            sh 'java --version'
        }
    }
}