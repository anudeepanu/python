    pipeline {
    agent {
        node {
            label 'ssh'
        }
    }
    /*environment {
		    DOCKERHUB_CREDENTIALS=credentials('dockerhub-cred')
	}*/
    stages {
        stage('clone') {
            steps {
                git credentialsId: 'for-gihubtokens', url: 'https://github.com/anudeepanu/python.git'
            }
        }
    }
}
