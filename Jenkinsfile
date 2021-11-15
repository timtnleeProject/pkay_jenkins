pipeline {
    agent { docker { image 'node:14-alpine' } }

    environment {
        HELLO = 'hello'
    }

    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                echo "HELLO: ${HELLO}"
            }
        }
    }
}