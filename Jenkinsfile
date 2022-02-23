pipeline {
    agent any
    environment {
        PATH="/opt/maven/bin:$PATH"
    }    
    
    stages {
        stage('SCM') {
            steps {
                git 'https://github.com/Bism123/testrepo.git'
            }
        }
        stage('Maven') {
            steps {
               sh "mvn package"
            }
         stage('hi') {
            steps {
                git 'hi guys how are you'
            }
        }   
        }
    }   
    
}
