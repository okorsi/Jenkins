pipeline {
    agent any   
    
    options {
        disableConcurrentBuilds()
    }
    stages {
        stage("Wait") {
            steps {
                sleep time: 45, unit: 'SECONDS' 
            }
        }
    }
}
