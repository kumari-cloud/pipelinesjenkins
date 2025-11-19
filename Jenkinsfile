pipeline {
    agent {
        label 'any'
        }
    
    stages {
        stage ('label-slave') {
            steps {
            sh 'hostname -i'}
        }
    }
}
