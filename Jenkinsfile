pipeline {
    agent any
    
    stages {
        stage('Clone repository') {
            steps {
                dir('path/to') {
                    git branch: 'develop', url: 'https://github.com/subrahmanyamYedida/pipeline-task.git', branch: 'develop'
                }
            }
        }
    }
}

