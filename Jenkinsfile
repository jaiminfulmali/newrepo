pipeline {
    agent any
    triggers {
        pollSCM('')
    }
    
    stages {
        
        stage('compare') {
            steps {

                sh ''' cp b.txt d.txt '''
                
            }
        }
    }
   
}
