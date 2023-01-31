pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                echo "${Names}" 
            }
        }
        stage('Test'){
            steps {
                echo "${Fruits}" 
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying the code to server"
            }
        }
    }
}
