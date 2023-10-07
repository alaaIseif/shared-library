@Library('my-shared-library') _

pipeline {
    agent any
    
    stages {
        stage('Install Nginx') {
            steps {
                installNginx()
            }
        }
    }
}
