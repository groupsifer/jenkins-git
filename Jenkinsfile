pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
		    echo"I can code"
		    ls -a 
		    who
		    cat /etc/shadow
		    cat /etc/passwd
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
