pipeline{
  agent{
    label 'master'
  }
  stages{
    stage("git_checkout"){
      steps{
      
      }
    }
    stage("Maven_build"){
      steps{
        sh 'mvn clean package'
      }
    }
    stage("upload_artifact"){
      steps{
        echo "upload completed"
      }
    }
    stage("Deployment"){
      steps{
        echo "deplyment completed"
      }
    }
  }
}
