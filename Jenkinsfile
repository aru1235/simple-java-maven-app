pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                
                    sh 'maven clean compile'
                
            }
        }

        stage ('Testing Stage') {

            steps {
    
                    sh 'maven test'
                
            }
        }


        stage ('Deployment Stage') {
            steps {
                
                    sh 'maven deploy'
                
            }
        }
    }
}
