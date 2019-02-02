pipeline {
	agent {
		docker { image 'node:7-alpine' }
	}
	stages {
		stage('Test-Gong') {
			sh -c 'node --version'
		}
	}
}
