pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name eshani-cluster-jenkins2 --template-body file://kubernetes-node-automate.yaml --region 'us-east-1'"
              }
         }


     }
}
