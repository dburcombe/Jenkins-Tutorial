pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
 		git credentialsId: 'ca291dd8-5c41-44c4-8cc7-d54da619d2bf', url: 'https://github.com/dburcombe/Jenkins-Tutorial'
            }    
        }
        stage('Build') {
            steps {
                echo 'Building'
            }    
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }    
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }    
        }
         stage('Release') {
            steps {
                echo 'Releasing'
            }    
        }
    }
}
