pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
             echo "${env.GIT_BRANCH}"
            }
        }
        
        
    }
}
