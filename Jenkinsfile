pipeline {
  agent none
  stages {
    stage('Say Hello') {
      agent { label 'nodejs-app' }
      steps {
        echo 'Hello World!'   
        sh 'java -version'
        echo "I am the very model of a modern Major-General"
        sh 'touch test_file; echo $(date +%F) >> test_file; cat test_file'
      }
    }
    stage('Just messing around') { 
      agent { label 'nodejs-app' }
      steps {
        echo "You're a wizard, Harry!"
        echo ''
        echo "Don't worry. You're just as sane as I am."
      }
    }
  }
}
