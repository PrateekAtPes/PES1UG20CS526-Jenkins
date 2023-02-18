pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
            sh "make -C main"
                echo 'Build stage completed'
            }
        
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
