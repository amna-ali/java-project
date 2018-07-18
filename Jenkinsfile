peline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "build step" 
            }
        }
        stage('Test') { 
            steps {
                sh "ant -f build.xml -v"  
            }
        }
        stage('Deploy') { 
            steps {
                echo "hello world" 
            }
        }
    }
}
