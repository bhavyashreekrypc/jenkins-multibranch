pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
          sh 'sudo apt-get install npm
'
           sh 'npm install' 
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
