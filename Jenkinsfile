pipeline{
    agent any 
    {        stages{
            stage("Build") {
                steps{
                    '''
                     echo "hello world:"
                '''
                }
            }
            stage("test"){
                steps {
                    timeout(time:3, unit:"SECONDS")
                    {
                        sh 'sleep 5'
                    }
                }
            }
        }    }
    
}