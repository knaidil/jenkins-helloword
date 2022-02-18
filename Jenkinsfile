node {
    stage('clone') {
    git branch: 'main', url: 'https://github.com/knaidil/jenkins-helloword.git'
    }
    stage('build') {
        sh label: '', script: 'javac Main.java'
    }
    stage('run') {
            sh label: '', script: 'java Main'
    }
}

