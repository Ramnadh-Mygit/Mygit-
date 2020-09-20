pipeline {
    agent any 
    stages {
        stage('hello') {
            steps{
                echo 'hello ramnadh'
            }
        }
        stage('git clone') {
            steps{
                git 'https://github.com/Ramnadh-Mygit/Mygit-.git'
            }
        }
      stage('mvn test') {
         steps{
           sh "mvn clean package"
                }
            }
        }

}
