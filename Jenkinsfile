pipeline{
        agent any
        stages{
            stage('handle secretes'){
                steps{
                        sh "docker login -u ${DOCKER_LOGIN_USR} -p ${DOCKER_LOGIN_PSW}"
                }
            }
        }
}
