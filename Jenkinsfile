pipeline {
    agent any
    triggers {
        pollSCM('')
    }
    
    stages {
        
        stage('compare') {
            steps {

                sh ''' cp /var/lib/jenkins/jobs/declarative/b.txt /var/lib/jenkins/jobs/declarative/d.txt '''
                
            }
        }
    }
   
}
