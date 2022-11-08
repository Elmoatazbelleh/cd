pipeline {
      agent any

          stages {


	        stage('Checkout GIT ') {
                 steps {
                    echo 'Pulliing ...';
		            git branch: 'motaz', credentialsId: 'Git', url: 'https://github.com/Elmoatazbelleh/cd.git'
		            
                        }
                 }
          }
}
