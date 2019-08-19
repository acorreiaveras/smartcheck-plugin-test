pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        smartcheckScan(imageName: 'ubuntu', smartcheckHost: 'smartcheck.kops.0secops.com', findingsThreshold: '[default:    {"malware":0,"vulnerabilities":{"defcon1":0,"critical":0,"high":0},"contents":    {"defcon1":0,"critical":0,"high":0},"checklists":{"defcon1":0,"critical":0,"high":0}}]', smartcheckPassword: 'administrator', smartcheckUser: 'trendmicro', smartCheckHost: 'smartcheck.kops.0secops.com')
      }
    }
  }
}