pipeline {
	agent {
		docker { image 'node:7-alpine' }
	}
	stages {
		stage('Test') {
			sh -c 'echo $(hostname)'
		}
	}
}
