pipeline {
	agent { dockerfile true }
	stages {
		stage('build-container') {
			steps { 
				sh "echo building container ${env.shiv_var} ${shiv_var}"
			}
		}
	}					
}

