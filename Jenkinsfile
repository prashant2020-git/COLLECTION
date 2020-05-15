pipeline {
   agent any

   stages {
      stage('COLLECTION') {
         steps {
           git 'https://github.com/prashant2020-git/COLLECTION.git'
           sh 'npm install'
           sh 'npm run api-tests'
         }
      }
   }
}
