pipeline {
  agent any
  stages {
    stage('') {
      steps {
        smartcheckScan(imageName: 'ubuntu', smartcheckHost: 'smartcheck.kops.0secops.com', findingsThreshold: '5', smartcheckPassword: 'administrator', smartcheckUser: 'trendmicro', imagePullAuth: '{"aws": {"region": "us-west-1"}}}', insecureSkipRegistryTLSVerify: true, insecureSkipTLSVerify: true, smartCheckHost: 'smartcheck.kops.0secops.com')
      }
    }
  }
}