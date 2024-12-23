pipeline {
    agent {
    docker {
	image 'node:23.5'
	args '-u 1000:1000' // Run container as a non-root user
	}
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}

