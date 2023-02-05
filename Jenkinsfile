pipeline {
    agent { label 'windows' }
    stages {
        stage('*********************************Check Parameters*********************************') {
            steps {
                echo "Welcome Heavy coder"
            }
        }
        stage('*********************************Exploratory data analysis*********************************') {
            steps {
                bat 'python EDA.py --a --b'
            }
        }
    }
}
