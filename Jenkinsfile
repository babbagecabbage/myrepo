pipeline {
    agent any

    stages {
        
        stage('Deploy') {
            steps {
                echo 'sending file for hosting on apache'
                bat 'copy *.html "C:\\Naman\\Apache24\\htdocs"'
                
            }
        }
    }
}
