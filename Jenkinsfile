pipeline {
    agent none
    stages {
        stage('Big sleep') {
            parallel {
                stage('Sleep 1') {
                    agent {
                        label "kari-cluster-scratch"
                    }
                    steps {
                        sh 'date'
                        sh 'sleep 60'
                        sh 'date'    
                    }
                }
                stage('Sleep 2') {
                    agent {
                        label "kari-cluster-scratch"
                    }
                    steps {
                        sh 'date'
                        sh 'sleep 60'
                        sh 'date'    
                    }
                }
                stage('Sleep 3') {
                    agent {
                        label "kari-cluster-scratch"
                    }
                    steps {
                        sh 'date'
                        sh 'sleep 60'
                        sh 'date'    
                    }
                }
                stage('Sleep 4') {
                    agent {
                        label "kari-cluster-scratch"
                    }
                    steps {
                        sh 'date'
                        sh 'sleep 60'
                        sh 'date'    
                    }
                }
                stage('Sleep 5') {
                    agent {
                        label "kari-cluster-scratch"
                    }
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
