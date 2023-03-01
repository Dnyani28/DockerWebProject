node {
    def app

    stage('Clone repository') {
        /* Let's make sure we have the repository cloned to our workspace */

        checkout scm
    }
   
   

    stage('clone Repository') {
    
    sh '''
      mvn compile
    '''
    }

    

    stage('package') {
     
     sh '''
        mvn package
     '''   
        }
        
        
    }
       
        
