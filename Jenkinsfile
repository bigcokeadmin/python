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
                sh 'ls -l $WORKSPACE'
                sh 'python3 $WORKSPACE/scripts/python-script.py'
            }
        }
    }
}
