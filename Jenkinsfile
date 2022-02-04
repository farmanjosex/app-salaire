node{
 
    stage('Clone') {
        git 'https://github.com/farmanjosex/app-salaire.git'
    }
    stage('Build') {
    sh 'playbook -i hosts.yml playbook.yml'
    }
}
