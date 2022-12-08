node {

    stage('Gitclone') {
        git branch: 'main', credentialsId: 'f3a6ac37-839a-40ee-b2a4-07a61a337299', url: 'https://github.com/Shivachinna1234/sudheer.git'
	   
    }
    stage('java version') {   
	
	   sh 'java -version'
    
    }
    stage('maven version') {   
	
	   sh 'mvn --version'
    
    
    
    }
    stage('maven validate') {   
	
	   sh 'mvn validate'
    
    }
    stage('maven compile') {   
	
	   sh 'mvn compile'
    
    }
    stage('maven test') {   
	
	   sh 'mvn test'
    }
    stage('maven package') {   
	
	   sh 'mvn package'
       
    }
    stage('maven deploy') {   
	
	   sh 'mvn deploy'
    }
}


