pipeline {
    agent any
    tools {
	maven 'M1'
    }    
    stages {
        stage ('Build') {
            steps {
                sh 'echo Packaging the Java project with Maven Build tool'
                sh 'mvn clean package'
            }
        }
    }
}
