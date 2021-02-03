pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		touch /home/hp/Desktop/build.txt
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
		touch /home/hp/Desktop/test.txt
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
		touch /home/hp/Desktop/deploy.txt
            }
        }
    }
}
