pipeline {
    agent any
    tools {nodejs "mynodejs"}
    stages {
        stage('Dev') {
            steps {
                git 'https://github.com/toshallab/aws_codebuild_codedeploy_nodeJs_demo.git'
                echo "index.js file content "
                sh 'cat index.js'
            }
        }
        stage ('build') {
            steps {
            sh 'npm install'    
            }
        }
    }
}
