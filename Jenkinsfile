node {
    stage('clone') {
    git 'https://github.com/nadeebencheikh/Jenkins.git'
                   }
    stage('build') {
    sh 'javac Main.java'
                   }
    stage('run') {
    sh 'java Main'
                   }
}
