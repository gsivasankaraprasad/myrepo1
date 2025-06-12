pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World!'
                echo "Build number: ${env.BUILD_NUMBER}"
                echo "Job name: ${env.JOB_NAME}"
                sh 'mkdir dir4'
                sh 'date'
                sh 'touch file123'
            }
        }
    }
}
