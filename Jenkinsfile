properties([pipelineTriggers([pollSCM('*/30 * * * *')])])
node{
    stage("one"){
        git "https://github.com/asafida/MySoftware.git"
    } 
    stage("bla") {
    sh "ls -l"
    }
}
