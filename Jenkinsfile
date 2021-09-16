node {
    checkout scm
    stage('Build') {
        sh 'make -n'
    }
    stage('Test') {
        echo 'Testing...'
    }
    stage('Deploy') {
        echo 'Deploying...'
    }
}
