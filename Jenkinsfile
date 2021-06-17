pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('') {
      steps {
        mail(subject: 'starting job', body: 'job started', to: 'bulumaknight@gmail.com')
      }
    }

  }
}