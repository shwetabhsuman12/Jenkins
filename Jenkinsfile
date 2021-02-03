pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		sudo sh "touch /home/hp/Desktop/POC/sample/build.txt"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
		sudo sh "touch /home/hp/Desktop/POC/sample/test.txt"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
		sudo sh "touch /home/hp/Desktop/POC/sample/deploy.txt"
            }
        }
    }
}
