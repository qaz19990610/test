# test
# test
Jenkinsfile(
pipeline {
    agent any
    
    stages{
        stage('Bulid'){
            steps{
                echo 'Hello world'
            }
        }
    }
})
