pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
		retry(3) {
		    sh 'echo "Hello World"'
		}
		
		timeout(time: 3, unit: 'MINUTES') {
		    sh 'echo "1"'
		}
	     }
        }
    }
}
