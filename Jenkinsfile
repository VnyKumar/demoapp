pipeline {
    agent any
     
     triggers {
        pollSCM "* * * * *"
    }
    stages {
        stage('clone') {
            steps {
                echo 'Hello World' 
                git clone https://github.com/VnyKumar/demoapp.git 
		    javac *java
		    java *class
                //git "https://github.com/VnyKumar/firstGit.git"
                
            }
        }
        
    }
	
}
