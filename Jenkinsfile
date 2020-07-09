@Library('shlib')
pipeline{
 agent any

  stages{
stage("c"){
            steps{
           confluenceConnectorSpace()
              confluenceLogs('space created')
            }
             
            }
}
}
