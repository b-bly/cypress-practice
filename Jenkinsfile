pipeline {
    agent { docker { image 'node:10.20.1' } }
    stages {
        stage('build') {
            steps {
                sh 'yarn cypress run'
            }
        }
    }
}