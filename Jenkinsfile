pipeline {
    agent {
	label 'ansible'
     }
   
    stages {
         stage('Running ansible role') {
            steps {
        echo "--------------Start-----------------"
		sh 'ansible-playbook install_clamav.yaml'
        echo "--------------Finish-----------------"
            }
        }  
    }    
}
