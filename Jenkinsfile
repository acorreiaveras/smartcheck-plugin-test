pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        smartcheckScan(imageName: 'ubuntu', smartcheckHost: 'smartcheck.kops.0secops.com', smartcheckPassword: 'administrator', smartcheckUser: 'trendmicro', smartCheckHost: 'smartcheck.kops.0secops.com')
      }
    }
  }
}