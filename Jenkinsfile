pipeline {
    agent any
    stages {
        stage ("Create zip file") {
            steps {
                sh 'zip middlewarescript_${BUILD_NUMBER}.zip * -x Jenkinsfile README.md'
            }
        }        
    }
}