pipeline {
   agent any
   stages{
      stage('CheckoutStage') {
          steps {
            sh 'rm -rf *'
            sh 'git clone https://github.com/rakesh9987/learningpath.git'
            sh 'cd learningpath' 
            sh 'hello_world.sh'
   }
      }
   }
}
