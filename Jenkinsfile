pipeline {
    agent any // This means run on any available agent

    stages {
        stage('Hello') {
            steps {
                echo 'Hello from the new Pipeline!'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building the project now ..."' // 'sh' step runs a shell command
                sh 'ls -la' // List files
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the project now ...'
            }
        }
    }
}
