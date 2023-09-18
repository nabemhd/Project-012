
pipeline {
    agent any

    stages {
        stage('Hello-World') {
            steps {
                echo 'Hello Wrold'
            }
        }
        stage('build') {
            steps {
                sh 'mvm clen deploy'
            }
        }
    }
}

