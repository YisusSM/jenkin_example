pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        sh '''
        ls
        pwd
        echo "Do something :D"
        echo "Esto fue tomado desde el branch 2"
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
      ifconfig -a
      ls -lrt
      echo "Do do"
      '''
            }
        }
    }
}
