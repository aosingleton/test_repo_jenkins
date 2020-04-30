
pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            echo 'Hello Samus'
            sh 'chmod +x ./start.sh'
            sh  'start.sh'
         }
      }
   }
}
