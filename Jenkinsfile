pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
          node {
            echo 'Pulling...' + env.BRANCH_NAME
            checkout scm
        
    }
        }
        
    }
}

