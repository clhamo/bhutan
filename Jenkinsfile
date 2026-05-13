pipeline {
  agent any 
    stages {
      stage ('Hello') {
        steps  {
          echo "Pipeline for poll scm"
        }
      }
      stage ('Hi') {
        steps {
          echo "task pipiline"
          cat file1
        }
      }
    }
}
