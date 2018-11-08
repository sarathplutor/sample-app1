node{
  stage('SCM checkout'){
    git 'https://github.com/sarathplutor/sampleapp1'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
