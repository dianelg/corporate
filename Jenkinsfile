pipeline{
    
    agent any
    stages{
        stage("git clone"){
            steps{
                git credentialsId: 'dianelg', url: 'https://github.com/dianelg/corporate.git'
            
                catchError(message: 'Deployment is unsuccessful') {
    // some block
}
            }
         stage("time stamp"){
            steps{
                timestamps {
    // some block
}
        }
    }
}
    }

