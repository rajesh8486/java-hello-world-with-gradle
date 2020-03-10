pipeline {
    agent any
    stage('Clean Build And Unit Tests') {
        steps {
            sh "./gradlew clean build"
        }
    }
}
