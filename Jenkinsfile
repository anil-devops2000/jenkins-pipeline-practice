pipeline {
    agent any
      stages {
         stage ("Code") {
            steps {
              git "https://github.com/anil-devops2000/one.git"
            }
         }
         stage ("Build") {
             steps {
               sh "mvn clean package"
            }
         }
      }
}
