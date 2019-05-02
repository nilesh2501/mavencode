pipeline {
    agent any
            stages {
                    stage('One') {
                            steps {
                                    git credentialsId: '82217c48-32a0-4bd9-a315-67c1e847cd02', url: 'https://github.com/nilesh2501/mavencode.git' 
                            }
                    }
  
  stage('Build') {
                            steps {
                                    sh'mvn clean package'
                            }
                    }
                
            }
}
