pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out from GIT...'
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: '882138e8-c15a-4512-b7b2-5e3398c0a519', url: 'https://github.com/addiittyya/repo.git']])
            }
        }
        stage('Build') {
            steps {
                echo 'Build......'
            }
        }
        stage('Upload...') {
            steps {
                echo 'Upload...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy....'
            }
        }
	}
}
