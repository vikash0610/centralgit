node{
  stage('SCM Checkout'){
    git'https://github.com/vikash0610/centralgit'
  }
  stage('Compile-Package'){
    sh'mvn package'
  }
}
