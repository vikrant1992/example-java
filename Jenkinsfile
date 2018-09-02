pipeline{
  agent any
	
	stages{
		stage('compile stage'){
			steps {
				withMaven(maven : 'maven3.5'){
				sh 'mvn clean compile'
				}
			}
		}
	}

		stage('test stage'){
			steps {
				withMaven(maven : 'maven3.5'){
				sh 'mvn test'
				}
			}
		}
	}	
