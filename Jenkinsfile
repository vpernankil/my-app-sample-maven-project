node{
    stage('Git Checkout'){
		git credentialsId: 'github', 
		    url: 'https://github.com/javahometech/my-app',
			branch: "${params.gitBranch}"
	}
	
	stage('Maven Build'){
		sh 'mvn clean package'
	}
	
}

