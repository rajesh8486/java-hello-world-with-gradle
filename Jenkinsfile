pipeline {
    agent any
    stages {
        stage('Clean Build And Unit Tests') {
            steps {
                sh "./gradle clean build"
            }
        }
    }
}
