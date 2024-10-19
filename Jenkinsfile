pipeline {
    environment {
        DB_HOST = "192.168.12.1"
        USERNAME = 'user1'
        PASSWORD = 'password123'
    }

    stages {
        stage('Setup') {
            steps {
                sh "pip install -r requirements.txt"
                echo "Database IP is: ${DB_HOST}"
            }
        }

        stage('setup') {
            steps {
                sh "pip install -r requirements.txt"
                echo "Database IP is: ${DB_HOST}"
            }
        }
    }
}