pipeline {
    agent { dockerfile true }
    stages {
        stage('Launch') {
            steps {
                sh 'python /app/test.py'
            }
        }
        stage('Echo') {
            steps {
                sh 'echo $PWD'
            }
        }
    }
}
