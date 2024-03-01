pipeline {
    agent any
    
    tools {
        // Refer to the Maven installation name configured in this job
        maven 'Maven 3.9.1'
    }
    
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
} 