pipeline {
  agent any
  stages {
    stage('Static Analysis ') {
      steps {
        sh '''sonar-scanner \\
  -Dsonar.projectKey=Keyist-Ecommerce \\
  -Dsonar.sources=. \\
  -Dsonar.host.url=http://172.31.80.149:9000 \\
  -Dsonar.login=sqp_b1cb05f94adc627f8b5d0346e3435ebc28eaa6a8'''
      }
    }

  }
}