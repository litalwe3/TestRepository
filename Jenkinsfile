#!groovy
pipeline {
    agent docker
   stages {
stage('Docker Build') {
      agent docker
      steps {
        sh 'docker build -t litalwe3/spring-petclinic:latest .'
      }
}
}
}     
