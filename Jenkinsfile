pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Successfully fetched the latest code from GitHub!'
            }
        }

        stage('Deploy') {
            steps {
                sh 'cp -rf index.html /var/www/html/'
            }
        }
    }
}
