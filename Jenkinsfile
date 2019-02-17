pipeline {
    agent {
        node {
            label 'master'
            customWorkspace "${env.JOB_NAME}/${env.BUILD_NUMBER}"
        }
   }
   stages {
       stage ('Build') {
           steps {
               sh "pwd"
           }
       }
 
       stage ('Test') {
           stops {
               sh "echo ${JAVA_HOME}"
           }
       }
   }
}
