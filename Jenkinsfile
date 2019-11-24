pipeline {
   agent any
   stages{
      stage('CheckoutStage') {
         steps {
            sh 'rm -rf *'
            sh '''
            git clone https://github.com/rakesh9987/learningpath.git
            cd learningpath
            bash hello_world.sh
            '''
   }
      }
      stage('mvn install') {
         steps {
                  sh '''
                  ls
                  cd learningpath
                  ls
                  cd my-app
                  mvn package
                  mvn clean compile
                  echo reached the last step RAY
                  '''
            }

   }
      }
   }
