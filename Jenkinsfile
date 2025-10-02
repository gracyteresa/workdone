pipeline {
    agent any
    stages {
        stage('Stage 1') {
            steps {
                echo 'iam stage1'
            }
        }
        stage('stage2'){
            steps{
                echo "iam stage2"
            }
        }
        
    }
    post{
        always{
            echo" run always"
        }
        success{
            echo " only on success"
        }
        failure{
            echo " only on failure"
        }
    }
}