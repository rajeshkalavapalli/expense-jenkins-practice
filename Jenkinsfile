pipeline{
    agent {
        label 'AGENT-1'
    }
    options {
        timeout(time: 15, unit: 'MINUTES') 
        disableConcurrentBuilds()
    }
    stages{
        stage('build') {
            steps{
                sh 'echo this is build'
            }
        }
        stage('test') {
            steps{
                sh 'echo this is test'
                sh 'sleep 10'
            }
        }
        stage('deploye') {
            steps{
                sh 'echo this is deploye'
            }
        }
        
    }
    
}