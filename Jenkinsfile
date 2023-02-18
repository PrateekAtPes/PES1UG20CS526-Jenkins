pipeline {
    agent any
    stages {
        }
        stage('Test') {
            steps {
                sh "/var/jenkins_home/workspace/pes1ug20cs226/main/hello_exec"
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
