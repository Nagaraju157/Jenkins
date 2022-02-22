pipeline{
    agent any
    stages{
        stage("welcome"){
            steps{
                git credentialsId: 'github', url: 'https://github.com/Nagaraju157/Jenkins_Pipeline.git'
            }
        }
    }
    
    
}
