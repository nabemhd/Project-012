
pipeline {
    agent any

    stages {
        stage('Hello-World') {
            steps {
                echo 'Hello Wrold'
            }
        }
environment {
    PATH = "/opt/apache-maven-3.9.2/bin:$PATH"
}
 
        stage('build') {
            steps {
                sh 'mvm clen deploy'
            }
        }
    }
}

