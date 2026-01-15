pipeline {
  agent any
  stages {
    stage('zabbix-docker-stage') {
      steps {
        tool(name: 'docker', type: 'update version')
      }
    }

  }
}