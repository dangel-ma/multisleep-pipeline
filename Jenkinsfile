pipeline {
    agent {
        label "basic-ecs-agents"
    }
    stages {
        stage('Big sleep') {
            parallel {
                stage('Sleep 1') {
                    steps {
                        sh 'date'
                        sh 'sleep 60'
                        sh 'date'    
                    }
                }
                stage('Sleep 2') {
                    steps {
                        sh 'date'
                        sh 'sleep 60'
                        sh 'date'    
                    }
                }
                stage('Sleep 3') {
                    steps {
                        sh 'date'
                        sh 'sleep 60'
                        sh 'date'    
                    }
                }
                stage('Sleep 4') {
                    steps {
                        sh 'date'
                        sh 'sleep 60'
                        sh 'date'    
                    }
                }
                stage('Sleep 5') {
                    steps {
                        sh 'date'
                        sh 'sleep 60'
                        sh 'date'    
                    }
                }                
            }    
        }
    }
}
