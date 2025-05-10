pipeline {
    agent {

       docker.image('maven:3.8.7-openjdk-17').inside {
    ...
    }
           
 
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}

