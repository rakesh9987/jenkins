pipeline {
   agent any
   tools {
   maven 'maven_3.6.2'
   }
   stages{
      stage('CheckoutStage') {
         steps {
            sh 'rm -rf *'
            sh '''
            git clone ${repo}
            #git clone https://github.com/rakesh9987/learningpath.git
            #checkout scm
            ls
            cd learningpath
            bash hello_world.sh
            '''
   }
      }
      stage('mvn install') {
         steps {
                  sh '''
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
