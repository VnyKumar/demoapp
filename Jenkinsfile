pipeline {
    agent any
     
     triggers {
        pollSCM "* * * * *"
    }
    stages {
        stage('clone') {
            steps {
                //sh 'echo "Hello World"' 
                sh 'git clone https://github.com/VnyKumar/demoapp.git' 
		//sh 'javac *java'
		//sh 'java  HelloWorld'
		 sh 'mvn -B -DskipTests clean package'
                //git "https://github.com/VnyKumar/firstGit.git"
                
            }//steps
        }//stage
        
    }//stages
	
}//pipeline
