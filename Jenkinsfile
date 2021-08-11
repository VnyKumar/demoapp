pipeline {
    agent any
     
     triggers {
        pollSCM "* * * * *"
    }
    stages {
        stage('clone') {
            steps {
                echo 'Hello World'
                //git 'https://github.com/ravdy/hello-world.git'
                //git "https://github.com/VnyKumar/firstGit.git"
                
            }
        }
        
    }
	post {
        always {
            clearws()
			//deleteDir()
        }

        success {
            emailext (
               //send email
            )
        }

        failure {
            emailext (
                //send notification
            )
        }
    }
}
