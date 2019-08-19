pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('DeployProduction') {
            steps {
                echo 'Deployment Successful'
            }
            steps {
                input 'Does the staging environment looks ok?'
        }       
    }
}
