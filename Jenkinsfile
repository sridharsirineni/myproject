node{
	stage ('Build'){
	
    	if (params['PROJECT'] == 'dev'){
	        git branch: 'dev', credentialsId: 'SridharSirineniGitRepo', url: 'https://github.com/sridharsirineni/myproject.git'
	        sh 'ls'
	    }
	    else if (params['PROJECT'] == 'stage'){
	        git branch: 'stage', credentialsId: 'SridharSirineniGitRepo', url: 'https://github.com/sridharsirineni/myproject.git'
	        sh 'ls'
    	}
	    else if (params['PROJECT'] == 'prod'){
	        git branch: 'prod', credentialsId: 'SridharSirineniGitRepo', url: 'https://github.com/sridharsirineni/myproject.git'
	        sh 'ls'
    	}
    }
}
