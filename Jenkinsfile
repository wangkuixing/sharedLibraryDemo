
@Library('jenkinslib') _

def tools = new com.binks.jenkins.tools()

pipeline {
    agent any
    stages {
        stage("第一步") {
            steps {
                script {
                    execShell()
                    tools.PrintMes("Hello Binks!")
                }
            }
        }
    }
}