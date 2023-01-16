pipeline {
    agent any

    stages {

        stage('Parallel Steps') {
            Parallel {
             
                stage('one') {
                    steps {
                        sh 'sleep 100'
                    }
                }

                stage('two') {
                    steps {
                        sh 'sleep 120'
                    }
                }
                stage('three') {
                    steps {
                        sh 'sleep 150'
                    }
                }
            }
            
        }
    }
}
