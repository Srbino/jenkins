pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Zde můžete spustit buildovací skripty, např. mvn clean install pro Maven projekty
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Zde můžete spustit testovací skripty, např. mvn test pro Maven projekty
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Zde můžete spustit deployovací skripty nebo příkazy
            }
        }
    }
    post {
        always {
            echo 'This will always run'
        }
        success {
            echo 'This will run only if successful'
        }
        failure {
            echo 'This will run only if failed'
        }
    }
}