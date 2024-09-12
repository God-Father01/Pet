pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                echo "Cloning the Git repository"
                sh "git clone https://github.com/God-Father01/Pet.git"
            }
        }

        stage('Build') {
            steps {
                echo "Building the artifact using Maven"
                sh "mvn clean package"
            }
        }

        stage('Try Docker') {
            steps {
                echo "Docker stage placeholder"
            }
        }
    }
}
