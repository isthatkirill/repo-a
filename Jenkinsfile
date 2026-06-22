 pipeline {                                                                                                                                                                                                   
      agent any                                                                                                                                                                                                
      stages {                                                                                                                                                                                                 
          stage('Build') {                                                                                                                                                                                   
              steps {
                  setBuildCustomName 'Release-${Date:yyyy.MM.dd}-${Branch}-${Rev}'
                  sleep 100                                                                                                                                                                     
              }                                                                                                                                                                                                
          }                                                                                                                                                                                                    
      }                                                                                                                                                                                                        
  }      
