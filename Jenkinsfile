pipeline {
   agent any

   stages {
      stage('Build - SCM') {
        steps {
          echo 'Building...'
          echo "Running ${env.BUILD_ID} ${env.BUILD_DISPLAY_NAME} on ${env.NODE_NAME} and JOB ${env.JOB_NAME}"
        }
   }
   stage('Test - SCM') {
     steps {
        echo 'Testing...'
     }
   }
   stage('Deploy - SCM') {
     steps {
       echo 'Deploying...'
     }
   }
  }
}