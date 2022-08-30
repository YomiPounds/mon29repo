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
                sh 'bash -x /var/lib/jenkins/workspace/monday29-pipeline/yomi.sh'
            }
        }
    }
}