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
    stage('Read JSON File') {
            steps {
                script {
                    def jsonData = readJSON file: 'data.json'
                    echo "Value of key1: ${jsonData.url}"
                  }
              }
          }
      }
}
    
    
    
