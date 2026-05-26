pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                 git branch: 'main',
                 url: 'https://github.com/dipali-nagesh/Configuration-Management-Using-Ansible.git'
            }
        }
        stage('Check Files') {
            steps {
                sh 'pwd'
                sh 'ls -la'
        
            }
        }

    }
}
