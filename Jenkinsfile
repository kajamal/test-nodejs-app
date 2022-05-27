pipeline { 
  
   agent any

   stages {
   
     stage('npm') { 
        steps { 
           sh 'echo "npm instalation..."' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
