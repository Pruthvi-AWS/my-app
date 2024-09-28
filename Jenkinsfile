node{
  stage('SCM Checkout'){
    git 'https://github.com/praveen240256/my-app.git'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
