node {
  stage('Clone') {
    git clone 'https://github.com/gbigbi/jenkins-helloworld.git'
  }
  stage('Build'){
    sh label:'', script: 'javac Main.java'
  }
  stage('Run'){
    sh label: '', script: 'java Main'
  }
}
