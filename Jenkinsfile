node{
  stage('checkout'){
    git 'https://github.com/raghunath1986/test_trigger.git'
  }
  stage('print'){
    sh "chmod 755 ${WORKSPACE}/test.sh && ${WORKSPACE}/test.sh"
  }
}
