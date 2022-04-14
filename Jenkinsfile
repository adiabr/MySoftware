properties([pipelineTriggers([pollSCM('30 * * * *')])])
node{
    stage("clone"){
        git branch: 'master'm url:'https://github.com/adiabr/MySoftware.git'
    }
}
