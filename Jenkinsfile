pipeline {
   agent any
   environment {
       
       GOCACHE = "/root"
   }
   stages {
       stage('Build') {

           
           steps {
               // Create our project directory.
	       sh 'pwd'
		sh 'whoami'
	       sh 'echo $PATH'
               sh '/usr/local/bin/kubectl get nodes'

           }
       }
	   }
}
