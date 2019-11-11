pipeline {
    agent { docker { image 'maven:3.6.2' } }

   stages {
        stage('Build') {
            steps {
                   sh 'sample.sh'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
    }
}
