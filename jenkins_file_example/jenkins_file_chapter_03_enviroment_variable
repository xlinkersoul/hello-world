pipeline {
	agent any
	environment {
		A=1
		B=2
	}
	stages {
		stage('Build'){
			steps {
				sh 'printenv'
			}
		}
	}
}
