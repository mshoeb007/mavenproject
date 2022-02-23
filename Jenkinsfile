node {
    stage('SCM check') {
        git "https://github.com/mshoeb007/mavenproject/"
    }
    stage('--Package--') {
        def mavenvariable = tool name: 'M2_HOME', type: 'maven'
        sh "${mavenvariable}/opt/maven/bin/mvn package"
    }
}
