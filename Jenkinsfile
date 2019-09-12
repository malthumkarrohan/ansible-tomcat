pipeline {
    agent any
    stages {
        stage('ansible tomcat') {
            steps {
                sh 'ansible-playbook tomcat.yml' 
            }
        }
    }
}
