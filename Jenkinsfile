pipeline {
   agent any
   stages{
      stage('CheckoutStage') {
         steps {
            sh 'rm -rf *'
            sh 'git clone https://github.com/rakesh9987/learningpath.git'
            sh 'ls -al'
            sh 'chmod 775 learningpath' 
            sh 'ls -al'
            sh 'cd learningpath'
            sh 'ls -al'
   }
      }
   }
}
