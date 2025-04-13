node {
    def app
    stage('Clone repository') {
        checkout scm
    }
    stage('Build image') {
       app = docker.build("SofijaRechkoska/cicd-homeworks")
    }
}
