pipeline {
    agent any
    stages {
        stage('begin') {
            steps {
                echo 'Hello pipeline'
            }
        }
        stage('run test') {
            steps {
                echo 'run test'
            }
        }
    }
    post {
        always {
            echo 'say goodbay'
        }
    }
}
