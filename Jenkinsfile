pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git 'https://github.com/najafathima9992/jenkiins'
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                sudo rm -rf /var/www/html/*
                sudo cp -r * /var/www/html/
                '''
            }
        }
    }
}
