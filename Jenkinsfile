pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('First') {
            steps {
                echo "1st"
            }
        }
        stage('Second'){
            steps {
                echo "Second application"
            }
        }
        stage('Third') {
            steps {
               echo "Third application"
            }
        }
         stage('Fourth') {
            steps {
               echo "Fourth application"
            }
        }
    }
}
