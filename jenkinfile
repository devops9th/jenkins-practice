pipeline {
    agent { label jenkinsslave1' }
        stages {
            stage ('Git') {
                steps{
                    script {
                    checkout scm
                    }
                }
            }
            stage ('report'){
                steps{
                    script {
                    echo "WELCOME"
                    } 
                }
            }
    }
}
