pipeline {
    agent any

    stages {
        stage('Clone repository') {
            when {
                branch 'develop'
            }
            steps {
                dir('~/my-project') {
                    git branch: 'develop', url: 'https://github.com/subrahmanyamYedida/pipeline-task.git', branch: 'develop'
                }
            }
        }
    }
}
