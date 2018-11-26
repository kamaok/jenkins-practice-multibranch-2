pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
			    sh "echo Building..."
			}
		}

		stage('Test') {
			steps {
			    sh 'echo Testing; exit 1'
			}
		}
		stage('Deploy') {
			steps {
			    sh	echo "Deploying"
			}
		}
	}
}
