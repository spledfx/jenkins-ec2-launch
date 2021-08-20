pipeline {
    agent   any
       
    stages {
        stage('Hello') {
            steps {
            sh '''
                aws ec2 terminate-instances --instance-ids i-0670e0084b4c4bdfa i-0f27d2908863d6e1b i-01ca815ff68a91d86
            '''
            }
        }
    }
}
