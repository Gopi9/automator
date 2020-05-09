pipeline {
    agent any
    stages {
	 stage('gradle build') {
              steps {
              sh "sudo ./gradlew clean classes"
              }
         }
    }
}
