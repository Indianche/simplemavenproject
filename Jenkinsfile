pipeline{
    agent any
    environment{
       PATH = "/usr/share/maven/bin:$PATH"
    }
    
    stages{
        stage("git checkout"){
            steps{
                
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
