pipeline {
    agent any
    triggers {
        pollSCM('')
    }
    
    stages {
        
        stage('compare') {
            steps {

                sh ''' /var/lib/jenkins/jobs/declarative/compare.sh '''
                
            }
        }
    }
   
}
