pipeline {
  agent any 
  stages {
    stage('Start-container') {
      steps {
        sh ''' sudo docker run --name demo1 -p 80:80 -d nginx 
        '''
      }
    }
  }
}
