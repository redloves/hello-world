Jenkinsfile (Scripted Pipeline)
/* ��ҪDocker Pipeline��� */
node('docker') {
    checkout scm
    stage('Build') {
        docker.image('maven:3.3.3').inside {
            sh 'mvn --version'
        }
    }
}