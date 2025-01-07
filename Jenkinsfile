pipleline {
    agent {
        label 'Agent'
    } 
    stages {
        stage('Build') {
            steps {
                sh 'echo This is Build'
            }  
        }

        stage('Test') {
            steps {
                sh 'echo This is Test'
            }  
        }
        stage('Deploy') {
            steps {
                sh 'echo This is Deploy'
            }  
        }
    }

    post {
        always{
            echo " This section runs always"
        }

        success{
            echo "This section run when pipline is success"

        }

        failure{
            echo "This section run when pipline is failure"
        }
    }
}