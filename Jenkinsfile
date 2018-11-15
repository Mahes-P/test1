pipeline {
    
    agent none
    stages {
        
        stage ('clone') {
            
            agent any
            
            steps {
                
                git branch:'master',
                    url: 'https://github.com/Mahes-P/Local_Jenkins_Test1.git',
                    credentialsId: '10196212-886c-4c30-b4e7-8c104e671a01'
                    
            }
        }
        
        stage ('read content') {
            
            agent any
            steps {
                
               sh ' echo Hello '
               sh ' cat test.sh'
            }
            
            
        }
    }
    
}
