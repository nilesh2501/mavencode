node {
   def mvnHome
   stage('Preparation') 
     git credentialsId: '82217c48-32a0-4bd9-a315-67c1e847cd02', url: 'https://github.com/nilesh2501/mavencode.git'     
      mvnHome = tool 'Maven'
   }
   
stage('Quality Gate'){
sh 'mv package'
}

   
  
