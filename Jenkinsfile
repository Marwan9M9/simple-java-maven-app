pipeline {
    agent { label 'agent-1' }  // specify your Jenkins node here
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
