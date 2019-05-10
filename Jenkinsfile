pipeline {
    agent any 
    stages {
        stage('build') {
            steps {
                bat 'python pipelineTesting.py'
                echo 'Hello Python Pipeline'
            }
        }
    }
}