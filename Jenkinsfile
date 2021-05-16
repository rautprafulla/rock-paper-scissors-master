pipeline {
	agent { docker {  image 'maven:3.3.9'  } }
	stages {
		stage('log version info') {
			steps {
				sh 'mvn --verision'
				sh 'mvn clean install'
			}
		}
	}
}