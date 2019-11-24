pipeline {
   agent any
   stages{
      stage('CheckoutStage') {
          steps {
            sh 'rm -rf *'
            sh 'git clone https://github.com/rakesh9987/jenkins.git'
            sh 'bash hello_world.sh'
   }
         stage('mvn clean install') {
          steps {
            sh 'mvn clean install'
   }
      }
   }
}
