pipeline {
    agent any 
    environmental {
        GIT_URL="https://github.com/sanagamesh/AWS_works"
        GIT_CREDENTAILSID='jenkins'
        GIT_BRANCH='main'
    }
    stages {
        stage('Build') { 
            steps {
                echo "Enterd the build stage: "
                echo "${env.GIT_URL}"
            }
        }
        stage('Test') { 
            steps {
                // 
            }
        }
        stage('Deploy') { 
            steps {
                // 
            }
        }
    }
}
