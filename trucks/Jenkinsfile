node {
   stage('init') {
      checkout scm
   }
   stage('build') {
      bat '''
         cd trucks
         mvn clean package
      '''
   }
}
