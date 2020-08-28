pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is SunilM'
                        echo 'We are Starting the Deployment'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'printing enviornment variable'  
                        //sh 'mvn -f java-tomcat-sample/pom.xml clean package'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying the test website"
                        // sh 'cd /var/www/html | git pull https://github.com/xyz/web-demo.git'
                  }
            }
            stage('Deploy to Production') {
                  steps {
                        echo "Deploying the test website to production"
                        
                  }
            }
            
      }
}
