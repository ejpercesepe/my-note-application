pipeline {
    agent any  

    stages {

        stage ("checkout from git"){
            steps {
                git 'https://github.com/ejpercesepe/simple-nodejs-app.git'
            }
        }
        stage ("install npm dependencies") {
            steps {
                sh "npm install"
            }
        }
        stage ("start application or ON") {
            steps {
                sh "npm start"
            }           
        }
        
 
    }
}