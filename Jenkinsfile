pipeline {
  agent {
    dockerfile {
      dir 'build'
    }
  }

  stages {
    stage('Run seed script') {
      steps {
        sh "python3 seed.py"
      }
    }

  }
}

