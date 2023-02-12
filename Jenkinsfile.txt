pipeline {
    agent any

    stages {
        stage('Git Featch') {
            steps {
                echo 'Featching'
            }
        }
        tage('Build') {
            steps {
                echo 'Build is Completed'
            }
        }
        stage('Testing') {
            steps {
                echo 'Testing Completed'
            }
        }
        tage('Deployment') {
            steps {
                echo 'Deployment Completed'
            }
        }
    }
}
