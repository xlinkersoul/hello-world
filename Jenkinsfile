pipeline {
	agent {
		docker { image 'node:7-alpine' }
	}
	stages {
		stage('BuildGongTest'){
			steps {
				sh 'node --version'
			}
		}
	}
}
