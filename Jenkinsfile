pipeline {
    agent any

    stages {
       

        stage('run front end') {
            steps {
                echo "executing yarn"
                node.js(Node-23.11.0){
                   sh 'echo "Building the application"'
            }
        }
        }

        stage('Test') {
            steps {
                echo "executing gradle..."
                withGradle()
                
                    sh './gradlew-v'
            }
        }

     
            
        }
    }
}
