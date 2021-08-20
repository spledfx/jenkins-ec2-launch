pipeline {
    agent   any
    
    environment {
        AWS_ACCESS_KEY_ID="ASIAVIK5LQAAYA4K755C"
        AWS_SECRET_ACCESS_KEY="/TkGkGkm7Kn8JPCMY699pyID38rbrlf1M0++C8uV"
        AWS_SESSION_TOKEN="FwoGZXIvYXdzEKT//////////wEaDJ0kZV46R/W2xskrSCL8AeOBTLtPjM3Tdcmh7+fFddAAp1v2rx2P9D4/0QTAInX6FUnBujocx7LJTHmenPQHpfcb5c5mFNr0OkF6wfHQmxtgp5dRKb5UrqqdoAwW7gH5KGwHSFzzSaAlwM+O8FHBzriF+CANqOv7iuWjUsQR45mq2ixVe5GcMc7khfxZxOLLzab9pDEl8bA8gIn3PtE/wrvAHhEaXnVSjl8h27HTo4j3totiQkDlV0WlL0DFTSLkOpymhcYz+Kt+uWGZb4NeecnSJMGjdaXX7GqevCYmswunGrvnzaFWKcm7mv7aQ+h/in4jb82p1ziq1AU5N0szeMLqiepFKVrmKAo9kyj2k/6IBjIy2jIU/JFfmFxSGPKISMoLcSr5/HWYn3BJCzSewv2E5FIF6ki9rV/Be2MgMShpVoU3Nl4="
    }
    
    stages {
        stage('Hello') {
            steps {
            sh '''
                aws ec2 describe-instances --region='eu-west-1'
            '''
            }
        }
    }
}
