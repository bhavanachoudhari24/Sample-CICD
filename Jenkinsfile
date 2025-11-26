pipeline{
    agent {
        label "ubuntu-server"
    }
    stages{
        stage("checkout"){
            steps{
            echo "code checkout"
            git url:"https://github.com/bhavanachoudhari24/django-notes-app.git", branch:"main"
            echo "code checkout successful"
        }}
        stage ("build"){
            steps{
              echo "code build"
        }}
        stage("upload to docker hub"){
            steps{
              echo "image upload"
        }}
        stage("deploy"){
            steps{
              echo "code deploy"
        }}
     }
    }
    
    
    
    
