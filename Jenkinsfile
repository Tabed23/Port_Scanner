pipeline {
  agent any
  tools {
        go "Go1.16.3"
    }
  environment {
        GO111MODULE = 'on'
    }
   stages {
        stage('Compile') {
            steps {
                sh 'go build'
            }
        }
   }
}
