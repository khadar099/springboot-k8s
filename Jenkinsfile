pipeline {
  agent any 
  
  stages {
    stage('Git Checkout') {
          steps{
              script{
                  git branch: 'develop', url: 'https://github.com/khadar099/springboot-k8s.git'
                  }
              }
          }
    }
}
    
    
    
