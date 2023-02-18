pipeline {
    agent any
    stages {
        }
        stage('Test') {
            steps {
                sh "/var/jenkins_home/workspace/PES1UG20CS526-1/main/hello_exec"
                echo 'Testing stage completed'
            }
        }
    }
    post {
            failure {
                echo 'Pipeline Failed'
            }
        }
}
