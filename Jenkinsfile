pipeline{
  agent any
	tools {
		jdk 'jdk1.7'
		maven 'mvn3.5'
	}
	
	stages{
		stage('compile stage'){
			steps {
				sh 'mvn clean compile'
			}
		}
	
		stage('test stage'){
			steps {	
				sh 'mvn test'
			}
		}
	}
}	
