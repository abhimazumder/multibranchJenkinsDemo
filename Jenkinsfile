pipeline {
  agent any
  stages {
  stage('Hello') {
      steps {
        echo 'Hello'
        sh 'pwd'
        sh 'ls'
      }
    }
    stage('World') {
      steps {
        echo 'World'
        sh 'pwd'
        sh 'ls'
      }
    }
    stage('Optional') {
    when {
    	branch "deb-123"
    }
    steps{
    	echo "deb branch running"
    }
    }
  }
}
