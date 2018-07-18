pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                sh "ant -f build.xml -v"
            }
        }
        stage('Test') { 
              steps {
        sayHello 'Awesome Test!'
      }
 
    }
    stage('Deploy') { 
      steps {
        sayHello 'Awesome Prod!'
      }
 
    }

            }
        }
