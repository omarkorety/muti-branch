pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stage('Print Branch name') {
        steps {
                    
             echo "${env.GIT_BRANCH}"

           }
        }
    
        
    }
}

