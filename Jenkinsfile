pipeline {
    agent {
		/Applications/Docker.app/Contents/Resources/bin/docker { image 'hello-world'  }
	}
    stages {
        stage('Test') {
            steps {
		    sh 'node --version'
		}
	     }
        


    }
}
