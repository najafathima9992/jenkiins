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
          sudo mkdir -p /var/www/html
          sudo cp -r /var/lib/jenkins/workspace/jenkins/* /var/www/html/
          '''
        }
     }
     }
}   
