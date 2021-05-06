node {
     stage('Clone repository') {
         checkout scm
     }

     stage('Build image') {
         app = docker.build("neojinn/jenkins:$BUILD_NUMBER")
     }
}
