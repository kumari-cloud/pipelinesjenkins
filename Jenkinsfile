pipeline {
    agent any
    stages {
        stage ('first build') {
            steps {
                retry (3) {
                echo "this is success"
                error "this is failure"
            }
            }
        }
    }
}
