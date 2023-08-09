pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh "git config --global --unset http.proxy"
                sh "git config --global --unset https.proxy"
                sh "git clone https://github.com/supratim230184/Hello_World.git"
                sh "mvn clean package"
            }
        }
    }
}
