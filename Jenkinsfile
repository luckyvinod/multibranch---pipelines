pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "sprint1 new changes application..."'
            }
        }

        stage("development1") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
