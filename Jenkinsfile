node {
    stage('clone') {
        git branch: 'main', url: 'https://github.com/Said-Learn-hub/Jenkins-Git-Learn.git'
    }
    stage('build') {
    sh '''    javac Main.java'''
    }
    stage('run') {
        sh '''    java Main'''
    }
}
