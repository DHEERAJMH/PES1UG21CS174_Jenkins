pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Compile the .cpp file using shell script
                script {
                    sh 'g++ -o my_program PES1UG21CS174-1.cpp'
                }
            }
        }
        
        stage('Test') {
            steps {
                // Print output of .cpp file using shell script
                script {
                    sh './my_progr'
                }
            }
        }
        
        stage('Deploy') {
            steps {
                // Deployment steps (if any)
                echo 'Deployment steps...'
            }
        }
    }
    
    post {
        failure {
            echo 'Pipeline failed'
        }
    }
}
