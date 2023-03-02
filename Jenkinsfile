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
                echo "test"
            }
        }
        stage('Deploy') {
            steps {
               echo "deployed"
            }
        }
    }
}
