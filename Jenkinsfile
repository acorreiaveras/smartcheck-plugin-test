pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        smartcheckScan(imageName: 'ubuntu', smartcheckHost: 'smartcheck.kops.0secops.com', findingsThreshold: '5', smartcheckPassword: 'administrator', smartcheckUser: 'trendmicro', smartCheckHost: 'smartcheck.kops.0secops.com')
      }
    }
  }
}