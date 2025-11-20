pipeline { 
  
   agent any

   stages {
   
     stage('Checkout') { 
        steps { 
         sh 'echo "Checkout code"'
        }
     }
     
     stage('Compile') { 
        steps { 
           sh 'echo "compile application..."'
        }
      }

        stage('Review') { 
        steps { 
           sh 'echo "Review application..."'
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
  
   	

     stage("Deploy application") { 
      
         steps { 
           sh 'echo "Deployment application..."'
         }

     }
  
   	}

   }
