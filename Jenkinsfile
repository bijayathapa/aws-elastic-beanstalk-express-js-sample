peline {
    agent {
        docker {
            image 'node:16-bullseye-slim' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm installi --save' 

            }
        }
    }
}
