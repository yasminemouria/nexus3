node{
  stage('SCM Checkout'){
  git 'https://github.com/anoirest07/maven-project'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
