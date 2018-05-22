pipeline {
  agent any
  stages {
     stage('Deploy ARM') {
      environment {
        ANYPOINT_CREDENTIALS = credentials('anypoint.credentials')
      }
      steps {
        bat 'mvn deploy -P arm -Danypoint.target.type=server -Darm.target.name=test-apprhel74mutest08-mule411 -Danypoint.environment=Sandbox -Danypoint.username=bimehta -Danypoint.password=Mel2018a'
      }
    }
    }
}