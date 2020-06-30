pipeline {
    agent any
    triggers {
        pollSCM('')
    }
    
    stages {
        
        stage('compare') {
            steps {

                sh ''' ./compare.sh '''
                
            }
        }
    }
   
}
