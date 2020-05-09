pipeline {
    agent any
	stage('gradle build') {
            steps {
            sh "./gradlew clean classes"
            }
        }
}
