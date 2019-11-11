pipeline {
    agent { docker { image 'maven:3.6.2' } }

   stages {
        stage('Build') {
            steps {
                   sh 'mvn --version'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
    }
}
