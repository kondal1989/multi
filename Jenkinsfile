pipeline {   
    agent any

    stages {   
        stage('Production branch') { 
            steps { 
               sh 'echo "This is Production branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "Production application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
