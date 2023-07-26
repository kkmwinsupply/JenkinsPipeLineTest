pipeline{
    agent{
        dockerContainer {
            image 'dockerjenkinskarthik:latest' 
        }
    }
    stages{
        stage('Build'){
            steps{
                sh 'node --version'
                sh 'pwd'
            }
        }
    }
}
