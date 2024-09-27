pipeline {
    agent any {
        stages{
            stage ('git checkout')
             step{
              git branch: 'main', url: 'https://github.com/Le-Moktar/awscicd.git   
            }
            stage ('test')
            step{
                sh 'echo test'
            }
        }
    }
}