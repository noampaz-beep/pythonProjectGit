node{
    properties([pipelineTriggers([pollSCM('* * * * *')])])
    stage("clone"){
        git branch: 'main', url: 'https://github.com/noampaz-beep/pythonProjectGit.git'
    }
    stage("show files"){
        bat "dir"
    }
}
