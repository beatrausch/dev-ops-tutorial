pipeline {
    agent {
        docker 'gradle:latest'
    }

    stages {
        stage('Build') {
            steps {
                sh 'gradle build'
            }
        }
    }
}
