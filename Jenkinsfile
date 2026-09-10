pipeline {
    agent any
    stages {
        stage('Compile and Run Java') {
            steps {
           
                bat 'javac Hello.java'
              
                bat 'java Hello'
            }
        }
    }
}
