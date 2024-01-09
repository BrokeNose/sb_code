pipeline {
    agent any
    tools{
        maven 'my_maven'
    }
    environment {
        GITNAME = 'brokennose'
        GITMAIL = 'ths8976@naver.com'
        GITWEBADD = 'https://github.com/SonDaewon/sb_code.git'
        GITSSHADD = 'git@github.com:SonDaewon/sb_code.git'
        GITCREDENTIAL = 'git_cre'
    }
    
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}