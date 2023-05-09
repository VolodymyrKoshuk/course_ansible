pipeline {
    agennt {
	label 'ansible'
     }
   
    stages {
         stage('Running ansible role') {
            steps {
		sh 'ansible-playbook install_clamav.yaml'
            }
        }  
    }    
}
