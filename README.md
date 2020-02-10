pipeline {
    agent any

    stages {
        stage('jhg') {
            steps {
                echo 'Building..'
            }
        }
        stage('kumar') {
            steps {
                echo 'Testing..'
            }
        }
        stage('newjob') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
