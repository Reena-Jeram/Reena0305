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
                echo "end"
            }
        }
        stage('Deploy') {
            steps {
               echo "ending"
            }
        }
    }
}
