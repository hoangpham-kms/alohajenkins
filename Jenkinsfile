pipeline {
    agent {
        label 'master'
    }

    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE    = 'sqlite'
    }

    stages {
        stage('Build') {
            steps {
                echo "Database engine is %DB_ENGINE%"
                echo "DISABLE_AUTH is %DISABLE_AUTH%"
                bat 'set'
            }
        }
    }
}
