pipeline {
    agent { 
	    dockerfile {
			filename 'Dockerfile'
			dir '.'
			label 'my-defined-label'
			additionalBuildArgs  '--build-arg version=1.0.2'
		}
	}
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}