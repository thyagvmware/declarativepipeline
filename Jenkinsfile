pipeline{
agent {
  docker { image 'node:16-alpine' }
}

  stages{
    stage('checkout'){
      steps{
           echo 'this is a checkout stage..'
          }
      }
    stage('build'){
      steps{
           echo 'this is a build stage..'
          }
      }
    stage('deploy'){
      steps{
           echo 'this is a deploy stage..'
          }
      }
  }
}
