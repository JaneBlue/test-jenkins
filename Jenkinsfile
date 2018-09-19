pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'docker build -t registry.cn-hangzhou.aliyuncs.com/k8s-mirrors/kube-app:$BUILD_NUMBER .'
      }
    }
  }
}
