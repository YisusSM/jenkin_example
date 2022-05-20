pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        sh '''
        ls
        pwd
        echo "Do something :D"
        '''
        
            }
        }
    stage('Test'){
        steps {
            sh '''
            echo "Do something too :P"
            hostname
            uname
            ls
            '''
            }
        }
  
  stage('deploy'){
    steps{
      sh '''
      touch 1
      ls -lrt
      echo "Do do"
      '''
            }
        }
    }
}
