pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/dipali-nagesh/Configuration-Management-Using-Ansible.git'
            }
        }

        stage('Run Ansible Playbook') {
            steps {
                    sh 'ansible-playbook playbooks/Configration.yml'
            }
        }

    }
}
