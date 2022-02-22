node {
    stage('SCM check') {
        git "https://github.com/mshoeb007/mavenproject/"
    }
    stage('--Package--') {
            sh 'mvn package'
    }
}
