pipeline {
	agent  any

	stages {
		stage('Hello'){
			steps {
				sh '''
    				  ansible --version
	  			  sh 'ssh root@172.31.41.149'
				  cd /tmp
    				  ls
	  			'''
			}
		}
	}
}
