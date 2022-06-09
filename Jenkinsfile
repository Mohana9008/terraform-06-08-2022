pipeline {
agent any

  stages{
    stage("terraform-apply"){
      steps{
      sh "terraform init"
        sh "terraform plan"
        sh "terraform apply"
      }
    }
  }
}
