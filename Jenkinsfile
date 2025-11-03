pipeline {
    agent any
    stages {
        stage('Deploy') {
            when {
                branch 'main'   // Runs only if branch is 'main'
            }
            steps {
                echo 'Deploying on main branch...'
            }
        }
    }
}
