node {
   def mvnHome
   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      //git 'https://github.com/jglick/simple-maven-project-with-tests.git'
      git 'https://github.com/sajeshkumary/gitbox.git'
   }
   stage('Build') {
      echo "building..."
    bat 'sajesh.bat'
   }
   stage('Results') {
       build job: 'Buildjob'
      echo "results..."
   }
}
