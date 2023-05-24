pipeline {
    agent any

    stages {
        stage('Git checkout') {
            steps {
             git 'https://github.com/arjunrayewar3196/hello-world-servlet.git'
            }
        }
        stage('display massage') {
            steps {
             sh 'this is testing pipeline'
            }
        }
    }
}
