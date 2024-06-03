pipeline {   
    agent any
    stages {   
        stage('Main') { 
            steps { 
               sh 'echo "This is main1 branch.....' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is Sprint1 branch"'
            }
        }

        stage("Development") { 
             steps { 
                sh 'echo "This is development branch"'
            }
        }  
    }
}
