pipeline {
  agent { docker { image 'node:20' } }
  stages {
    stage('Test') { steps { sh 'npm ci && npm test' } }
  }
}
