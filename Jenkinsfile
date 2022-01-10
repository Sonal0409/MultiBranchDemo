pipeline { 
  
   agent any

   stages {
   
     stage('Checkout') { 
        steps { 
         sh  'echo "Checkout code"'
        }
     }
     
     stage('Compile') { 
        steps { 
           sh 'echo "compile application..."'
        }
      }

      stage('Test') { 
        steps { 
           sh 'echo "Test application..."'
        }
      }
         stage("Package application") { 
         steps { 
           sh 'echo "package application..."'
         }

     }
  
   	}

   }
