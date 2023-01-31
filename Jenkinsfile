pipeline { 
    agent any 
    parameters {
        string(name: 'Names', defaultValue: 'Lokesh')
        choice(name: 'Fruits', choices: ['Apple', 'Mango', 'Grapes'])
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
