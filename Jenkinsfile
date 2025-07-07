pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                retry (3) {
                    echo "This is my hello prgm"
                    error "This gives the error"
                }
            echo "printing afer multiple retry"    
            }
        }
    }
}
