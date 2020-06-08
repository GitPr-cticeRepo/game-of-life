node {
    stage('scm') {
        git 'https://github.com/GitPr-cticeRepo/game-of-life.git'
    }
    stage('build') {
        sh 'mvn package'
    }
}
