pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		sh "touch /home/hp/Desktop/build.txt"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
		sh "touch /home/hp/Desktop/test.txt"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
		sh "touch /home/hp/Desktop/deploy.txt"
            }
        }
    }
}
