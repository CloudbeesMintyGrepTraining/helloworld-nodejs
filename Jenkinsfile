pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World!'   
        sh 'java -version'
        echo "I am the very model of a modern Major-General"
        sh 'touch test_file; echo $(date +%F) >> test_file; cat test_file'
      }
    }
  }
}
