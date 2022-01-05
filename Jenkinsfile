pipeline{
      agent any
  
      stages{
        stage('Build'){
          
                        when{
                                changeset globe: "*.js"
                        }
          steps{
              echo "Hello World changeset JS"
          }
       }
    }
}
            
    
