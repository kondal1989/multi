pipeline {   
    agent any

    stages {   
        stage('Development branch') { 
            steps { 
               sh 'echo "This is development branch"' 
            }
        }
     
        stage('dev') { 
            steps { 
               sh 'echo "devlopment application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
