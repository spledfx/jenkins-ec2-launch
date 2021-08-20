pipeline {
    agent   any
       
    stages {
        stage('Hello') {
            steps {
            sh '''
                echo "Try now!"
                aws ec2 create-tags --resources i-0e8a071c445fbdb87,i-01ca815ff68a91d86,i-0f27d2908863d6e1b,i-0670e0084b4c4bdfa --tags Key=Project,Value=Jenkins --region='eu-west-1'
            '''
            }
        }
    }
}
