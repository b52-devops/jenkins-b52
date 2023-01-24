pipeline {
    agent any

    stages {
        stage('One'){
            steps {
                echo "I am stage One"
            }
        }

        stage('Two'){
            steps {
                echo "I am stage Two"
            }
        }

        stage('Three'){
            steps {
                    sh '''
                        echo hello World
                        echo Hai World
                        echo I am using Pipeline Syntax Generator
                    '''
                }
        }

    }
}