node{
  stage('SCM Checkout'){
    
    git 'https://github.com/praveen240256/my-app.git'
  }
  stage('Compile-Package'){
    //Get maven home path
    def mvnhome = tool name: 'M2_HOME', type: 'maven'
    sh "${mvnhome}/bin/mvn package"
  }
}
