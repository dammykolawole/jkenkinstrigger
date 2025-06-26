pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                sh 'echo "Build completed"'
            }
           
        }
    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}