pipeline{
    agent any
    stages{
        stage('clone repo'){
            steps{
                sh 'echo "Do have a great day Abayomi"'
            }
        }
        stage('check yourself'){
           steps{
                sh 'whoami'
           }
        }
        stage('create a bash file'){
            steps{
                sh 'sudo chmod +x idris.sh'
                sh 'bash -x idris.sh'
            }
        }
    }
}