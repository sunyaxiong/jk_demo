pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
		stage('test') {
            steps {
                sh 'echo "Hello Test"'
                sh '''
                    echo "Multiline shell steps works too"
                '''
            }
        }
    }
}