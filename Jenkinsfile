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
                        date
                        sleep 60
                        date    
                    }
                }
                stage('Sleep 2') {
                    agent {
                        label "kari-cluster-scratch"
                    }
                    steps {
                        date
                        sleep 60
                        date    
                    }
                }
                stage('Sleep 3') {
                    agent {
                        label "kari-cluster-scratch"
                    }
                    steps {
			date
                        sleep 60
			date
                    }
                }
                stage('Sleep 4') {
                    agent {
                        label "kari-cluster-scratch"
                    }
                    steps {
			date
                        sleep 60
			date
                    }
                }
                stage('Sleep 5') {
                    agent {
                        label "kari-cluster-scratch"
                    }
                    steps {
			date
                        sleep 60
			date
                    }
                }                
            }    
        }
    }
}
