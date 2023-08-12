pipeline{
  agent any
  stages{
    stage('main-deploy'){
      when {
        branch "main"
      }
      steps{
        echo "deploy to main environment"
      }
    }
    stage('dev-deploy'){
      when {
        branch "dev"
      }
      steps{
        echo "deploy to dev environment"
      }
    }
    stage('uat-deploy'){
      when {
        branch "uat"
      }
      steps{
        echo "deploy to uat environment"
      }
    }
    stage('prod-deploy'){
      when {
        branch "prod"
      }
      steps{
        echo "deploy to prod environment"
      }
    }
  }
}
