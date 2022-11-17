pipeline {
    agent { docker 'maven:3.8.1-adoptopenjdk-11' } 
    stages {
        stage('build') {
            steps {
                echo 'Building Project'
            }
        }
        stage('test') {
            steps {
                echo 'Testing'
            }
        }
        stage('deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}