pipline{
    agent any
    stages {

       stages('clone') {
          steps {
              git url:'https://github.com/Chiranthan117/jenkins-simple-demo.git',
                  branch:'main'
      }
}
stages('RUN script') {
    stages {
         sh 'chomd +x script.sh'
         sh './script.sh'
         }
     }
  }
}
