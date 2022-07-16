pipeline {
    agent any
    tools {nodejs "mynodejs"}
    stages {
        stage('Dev') {
            steps {
                git 'https://github.com/shivshashyaM/jen.git'
                echo "Jenkinsfile file content "
                sh 'cat Jenkinsfile'
            }
        }
        stage ('build') {
            steps {
            sh 'npm install'    
            }
        }
  }
}
