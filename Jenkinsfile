pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo 'Testing..'
                echo grep -o -i devops copy-example.txt | wc -l
                echo sed -i '' 's/devops/hello_world/g' example.txt
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
