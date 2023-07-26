pipeline{
    agent{
        docker {
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
