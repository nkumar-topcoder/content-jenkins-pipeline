pipeline {
agent any
stages {
stage('build') {
steps {
sh 'javac -d . src/*.java'
sh 'echo Main-Class: Rectangulator > MANIFEST.MF'
sh 'jar -cvmf MANIFEST.MF rectangle.jar *.class'
  AWS_ACCOUNT_ID=123456789055
}
}
}
}
