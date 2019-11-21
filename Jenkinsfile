node {
   stage('init') {
      checkout scm
   }
   stage('build') {
      sh '''
         cd trucks
         mvn clean package
      '''
   }
}
