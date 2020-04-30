pipeline {
    agent any
    stages {
        stage('One') {
            steps {
                echo 'Hello Samus'
                echo 'Hello Samus' samus.txt
            }
        }
        stage('Two') {
            steps {
                cd /home/ec2-user
                mkdir jenkins_pipleine_folder
                cd jenkins_pipleine_folder
                touch play.txt
            }
        }
    }
}
