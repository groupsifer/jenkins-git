pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
		    echo"I can code"
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
