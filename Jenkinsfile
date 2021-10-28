node{
  stage('checkout'){
    git 'https://github.com/raghunath1986/test_trigger.git'
  }
  stage('print'){
    sh "${WORKSPACE}/test.sh"
  }
}
