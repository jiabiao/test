pipeline {
    agent any 
    triggers {
        cron('H/5 * * * *')
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
