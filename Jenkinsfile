pipeline {
	agent { label 'master' }
	stages {
		stage ('build') {
	        steps {
                     echo " This is the build step "
                     }
		}
		stage ('test: integration-&-quality') {
			steps {
                      echo " This is the integration testing step   "
                     }
		}
		stage ('test: functional') {
			steps {
                      echo " This is the functional testing step   "
                     }
		}
		stage ('test: load-&-security') {
			steps { 
                          echo " This is the Deployment Step   "
                     }
		 }
	}
}
