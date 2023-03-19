pipeline {
    agent any 
    triggers {
        cron('H H 1,15 1-11 *')
    }  
    stages {
        stage("build") {
            steps{
                echo 'hello dev'
                sh 'ls'
            }
        }
    }
}
