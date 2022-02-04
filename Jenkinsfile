node{
 
    stage('Clone') {
        git 'https://github.com/farmanjosex/ansible-jenkins.git'
    }
    stage('Build') {
    sh 'build-playbook -i hosts.yml playbook.yml'
    }
}
