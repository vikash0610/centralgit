node{
  stage('SCM Checkout'){
   
    
    
    git'https://github.com/vikash0610/centralgit'
  }
  stage('Compile-Package'){
      //get maven home path
      def mvnHome = tool name: 'maven-app', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
  }
}
