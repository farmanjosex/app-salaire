node{
 
    stage('Clone') {
        git 'https://github.com/farmanjosex/ansible-jenkins.git'
    }
    stage('Build') {
    sh 'hosts.yml playbook.yml'
    }
}
