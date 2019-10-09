pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                sh "aws s3 sync . s3://www.shouhou123.com/ttds"
            }
        }
    }
}
