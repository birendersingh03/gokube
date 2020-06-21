pipeline {
   agent any
   
   stages {
       stage('Build') {

           
           steps {
               // Create our project directory.
               sh 'cd /root/Kube'
               sh 'kubectl apply -f dep.yml'

           }
       }
	   }
}
