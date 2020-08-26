pipeline{
    agent {label 'java'}
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
                sh "tree"
                //sh "mvn clean package"
            }   
        } 
    }   
}
