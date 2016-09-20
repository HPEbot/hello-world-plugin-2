 node ('master'){
  stage 'Setup'
  env.PATH = "${tool 'Maven 3'}/bin:${env.PATH}"
  stage 'Chekout'
  checkout scm
  stage 'build'
  sh 'mvn clean package'
 }
