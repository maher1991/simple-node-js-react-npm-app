pipeline {
    agent {
    docker {
	image 'node:23.5'
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

