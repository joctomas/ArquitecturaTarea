// Powered by Infostretch 

timestamps {

node () {

	stage ('Arqui - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'github_login_gvl', url: 'https://github.com/joctomas/ArquitecturaTarea.git']]]) 
	}
	stage ('Arqui - Build') {
 			// Shell build step
sh """ 
echo "hey" 
 """ 
	}
}
}