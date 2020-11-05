node{
    stage('Git Checkout'){
		
	 git 'https://github.com/vpernankil/my-app-sample-maven-project'
	
    }
	
    stage('Maven Build'){

	//Get maven home path
	def mvnhome = tool name: 'maven3', type: 'maven'
	sh "${mvnhome}/bin/mvn clean package"
 
   }
	
}

