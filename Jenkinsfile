pipeline {
    agent any
    stages {
        stage('Printing') {
            steps {
                echo 'Printing..'
                grep -o -i devops example.txt | wc -l
                sed -i '' 's/devops/hello_world/g' example.txt
            }
        }

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
