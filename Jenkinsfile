pipeline {
    agent any 1
    stages {
        stage('Build') {
            steps {
              sh './gradlew clean build'
            }
        }
    }
}
