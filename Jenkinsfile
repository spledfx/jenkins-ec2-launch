pipeline {
    agent   any
       
    stages {
        stage('Hello') {
            steps {
            sh '''
                echo "Try now!"
                whoami
                cat ~/.aws/credentials
            '''
            }
        }
    }
}
