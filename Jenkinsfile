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
                sh '$workspace/scripts/python3 python-script.py'
            }
        }
    }
}
