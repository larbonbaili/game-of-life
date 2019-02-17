peline {
    agent {
        node {
            label ‘master’
            customWorkspace "${env.JOB_NAME}/${env.BUILD_NUMBER}"
        }
   }
   stages {
       stage (‘Build’) {
           sh “pwd”  //这个是Linux的执行
       }
 
       stage (‘Test’) {
           sh “echo ${JAVA_HOME}”  //这个是Linux的执行
       }
 
   }
}
