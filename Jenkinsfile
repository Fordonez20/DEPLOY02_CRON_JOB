pipeline {
    agent any
    
    triggers {
        cron('*/2 * * * *')
    }
    
    stages {
        stage('build') { 
            steps {
                echo 'Build Stage Success' 
            }
        }
        stage('test') { 
            steps {
                echo 'Test Stage Success' 
            }
        }
        stage('deploy') { 
            steps {
                echo 'Deploy Stage Success' 
            }
        }
    }
    
}
