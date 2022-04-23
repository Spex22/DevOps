pipeline {
    agent any
    stages {
        stage('Parallel stage') {
            parallel {
                stage('First') {
                    steps {
                        build(job: "job1")
                    }
                }
                stage('Second') {
                    steps {
                        build(job: "job2_hm")
                    }
                }
                
            }
            
        }
        
    }
}
