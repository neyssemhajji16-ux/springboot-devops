pipeline {
    agent any

    stages {
        stage('Checkout GIT') {
            steps {
                echo 'Pulling...'
                git branch: 'main',
                    url: 'https://github.com/neyssemhajji16-ux/springboot-devops.git'
            }
        }

        stage('Date système') {
            steps {
                sh 'date'
            }
        }
    }
}
