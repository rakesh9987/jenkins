pipeline {
   agent any
   stages{
      stage ('CheckoutStage') {
      steps {
            sh 'git clone https://github.com/rakesh9987/jenkins.git'
            sh cd jenkins
            bash hello_world.sh
   }
      }
   }
}




