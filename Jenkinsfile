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
               sh 'cd ${GOPATH}/Kube'
               sh 'kubectl apply -f dep.yml'

           }
       }
	   }
}
