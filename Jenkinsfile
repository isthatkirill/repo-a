 pipeline {                                                                                                                                                                                                   
      agent any                                                                                                                                                                                                
      stages {                                                                                                                                                                                                 
          stage('Build') {                                                                                                                                                                                   
              steps {
                  setBuildCustomName 'Release-$Date:yyyy.MM.dd}-${Branchq}-${Rev}'
                  sleep 100                                                                                                                                                                     
              }                                                                                                                                                                                                
          }                                                                                                                                                                                                    
      }                                                                                                                                                                                                        
  }      
