node{
 
    stage('Clone') {
        git 'https://github.com/farmanjosex/ansible-jenkins.git'
    }
    stage('Build') {
    sh 'playbook -i hosts.yml playbook.yml'
    }
}
