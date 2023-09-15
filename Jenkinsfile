pipeline { 
    agent any 

    stages { 
        stage('Create python file') {
            steps {
                sh """
                               echo $USERNAME
                               echo $FILENAME
                """
            }
        }
        stage('Run Python Script') {
            steps{
                sh 'pwd'
                sh 'echo $WORKSPACE'
                // sh 'python3 $workspace/scripts/python-script.py'
            }
        }
    }
}
