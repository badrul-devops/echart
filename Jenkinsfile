pipeline{
    agent any 
    tools {
         jdk 'java'
         maven 'maven'
    }

    stages{
        stage("Checkout from github"){
            steps{
                checkout scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/badrul-devops/echart.git']])
            }
        }
        
    }

}