pipeline {
  agent any

  stages {
    stage('serverip') {
      steps {
            sh '''
                hostname -i
                echo "hostname is : $(hostname -i)"
               '''
      }
    }
    stage('uptime'){
      steps{
        sh '''
             uptime
             echo "uptime is : $(uptime)
            '''
        }
      }
  }
}
