pipeline {
    agent any {
        stages{
            stage ('git checkout')
             step{
              git branch: 'main', url: 'https://github.com/Le-Moktar/awscicd.git   
            }
            stage ('cho')
            step{
                sh 'echo cho'
            }
        }
    }
}