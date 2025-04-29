pipeline {
    agent any
    triggers {
        pollSCM '* * * * *'
    }

    stages {
        stage('build') {
            steps {
                echo 'Hello World'
            }
        }
 
        stage('test') {
            steps {
                echo 'Hello test'
            }
        }


        stage('deliver') {
            steps {
                echo 'Hello deliver'
            }
        }
    }
}
