        pipeline { 
    agent any  
    stages { 
        stage('Build') { 
            steps { 
              echo 'This is a Pipeline.'
             }
        }
        stage('Archive') {
         steps {
           dir ('/target') {
           archive '*.jar'
         }  
      } 
    }
        
        
        
      
    }
}
