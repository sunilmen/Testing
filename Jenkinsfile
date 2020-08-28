pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Ashutosh from giit'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'printing enviornment variable'
                        // sh 'printenv'
                        
                        
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying the test website"
                        // sh 'cd /var/www/html | git pull https://github.com/ashutoshdubey21/web-demo.git'

                  }
            }
            
      }
}
