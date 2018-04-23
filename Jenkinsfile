def branch_name = env.BRANCH_NAME != null ? env.BRANCH_NAME : 'master'

pipeline {
    agent any


    stages {
      stage('apiserver tests') {
        steps {
          echo "We have run the tests against apiserver"
        }
      }
      stage('apiserver build') {
        steps {
          echo "We have built apiserver"
        }
      }
    }
}
