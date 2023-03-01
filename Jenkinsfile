pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                echo "Build"
            }
        }
        stage('Test'){
            steps {
                echo "testing"
            }
        }
        stage('Deploy') {
            steps {
               echo "deploy"
            }
        }
    }
}
