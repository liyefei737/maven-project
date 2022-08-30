pipeline {
    agent any

    stages {
        stage('running stages code from Jenkinsfile 1') {
            steps {
                sh "echo 1st stage"
            }
        }
                stage('running stages code from Jenkinsfile 2') {
            steps {
                echo '2nd stage'
            }
        }
        
                        stage('another stage') {
            steps {
                echo 'xxx'
            }
        }
    }
}
