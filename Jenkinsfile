pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                sh 'go build'
            }
        }

        stage('finish') {
            sh 'echo PIPELINE FINISHED'
        }
    }
}