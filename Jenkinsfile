pipeline {
    agent any
    
    stages {
        stage ('Build') {
            steps {
                sh 'echo Packaging the Java project with Maven Build tool'
                sh 'mvn clean package'
            }
        }
    }
}
