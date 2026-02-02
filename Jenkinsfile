pipeline{

    agent any

        stages{

            stage('welcome'){
                steps{
                    echo "pipeline started Successfully"
                }
        
            }
        
         stage('show files'){
                steps{
                    sh 'ls'
                    sh 'cat hellow.txt'
                }
            }

            
         stage('finished'){
                steps{
                    
                    echo "pipeline finished"
                }
            }

        }
    }

