pipeline {
   agent any
   stages{
      stage('CheckoutStage') {
          steps {
            sh 'rm -rf jenkins'
            sh 'git clone https://github.com/rakesh9987/jenkins.git'
            sh 'hello_world.sh'
   }
      }
   }
}
