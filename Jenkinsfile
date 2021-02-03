pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		sh "touch /home/hp/Desktop/POC/sample/build.txt"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
		sh "touch /home/hp/Desktop/POC/sample/test.txt"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
		sh "touch /home/hp/Desktop/POC/sample/deploy.txt"
            }
        }
    }
}
