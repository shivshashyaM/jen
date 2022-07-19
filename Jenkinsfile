pipeline {
    agent any
    tools {nodejs "mynodejs"}
    stages {
        stage('Dev') {
            steps {
                git 'https://github.com/shivshashyaM/jen.git'
                echo "index.js file content "
                sh 'cat file.txt'
            }
        }
        stage ('build') {
            steps {
            sh 'npm install'    
            }
        }
    }

