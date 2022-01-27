pipeline { 
agent any 
    stages { 
        stage ('Build') { 
            steps {
                echo 'Building dummy project....'
            }
        }
        stage ('Test') { 
            steps {
                echo 'adding dummy tests...'
            }
        }
        stage ('QA') {
              steps {
                  echo 'its QA env'
              } 
        }
        stage ('Deploy') {
               steps {
                   echo 'Deployin on QA environment'
               } 
        }
        stage ('Monitor') { 
        }
 
    }           
 }
