@Library('shared-library')_
pipeline {
    agent any
    stages {
        stage('calling displayname') {
            steps {
                script{
                    displayname 'hithesh'
                }
            }
        }
        
       
        stage("Dev") {
            steps {
                echo "Started stage Dev"
            }
        }
            stage("QA") {
            steps {
                echo "Started stage QA"
            }
        }


        stage("stake") {
            steps {
                echo "Started stage stake"
            }
        }
    
    }
}
