pipeline {
      agent any

          stages {


	        stage('Checkout GIT ') {
                 steps {
                    echo 'Pulliing ...';
		            git branch: 'motaz', credentialsId: 'jenkins-git', url: 'https://github.com/Elmoatazbelleh/cd.git'
		            
                        }
                 }
          }
}
