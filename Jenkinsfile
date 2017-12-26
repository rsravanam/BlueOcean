pipeline {
    agent { 
	    dockerfile {
			filename 'Dockerfile'
			dir 'Docker-file'
		}
	}
    stages {
        stage('Test') {
            steps {
                echo 'hello'
            }
        }
    }
}