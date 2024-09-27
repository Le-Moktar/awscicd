pipeline {
    agent any

    stages {
        stage('git checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Le-Moktar/awscicd.git'
            }
        }
        stage('Build'){
  steps {
       echo 'hello from the build stage'
  }
}
    }
}
