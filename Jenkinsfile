pipeline {
    agent {
        docker{
            image 'ruby'
        }
    }
    environnmrnt {
        CI = true
    }
    stages {
        stage('Bundle') {
            steps {
                sh "bundle install"
            }
        }

    }
}