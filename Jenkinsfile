pipeline{
    agent any
    environment{
       PATH = "/usr/share/maven/bin:$PATH"
    }
    
    stages{
        stage("git checkout"){
            steps{
                git 'https://github.com/Indianche/Helloworld.git'
                sh "ls"
                sh "pwd"
            }   
        } 
        stage("maven build"){
            steps{
                sh "mvn clean package"
            }   
        } 
    }   
}
