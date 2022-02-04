node{
 
    stage('Clone') {
        git 'https://github.com/farmanjosex/app-salaire.git'
    }
    stage('Ansible') {
     ansiblePlaybook (
      become: mouktar
      playbook: 'playbook.yml'
      inventory: 'hosts.yml'
     )
    }
}
