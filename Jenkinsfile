node{
  stage('SCM Checkout'){
    
    git 'https://github.com/Pruthvi-AWS/my-app.git'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
