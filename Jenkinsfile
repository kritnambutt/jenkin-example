pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                grep -o -i devops copy-example.txt | wc -l
                sed -i '' 's/devops/hello_world/g' example.txt
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
