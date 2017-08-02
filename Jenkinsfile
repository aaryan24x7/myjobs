node{
stage('parameters'){
properties([buildDiscarder(logRotator(artifactDaysToKeepStr: '1', artifactNumToKeepStr: '5', daysToKeepStr: '5', numToKeepStr: '5')), parameters([choice(choices: ['list'], description: '', name: 'GERRIT_BRANCH')]), pipelineTriggers([])])
}
stage('java version'){
java('1.7')
}
stage('delete ws'){
deleteDir()
}
stage('check'){
checkout([$class: 'GitSCM', branches: [[name: '${GERRIT_BRANCH}']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'da47d6e3-7fee-4018-afff-4a483f5690c8', url: 'https://github.com/aaryan24x7/myjobs.git']]])

}
stage('build'){
echo 'hello'
}
stage('display'){
echo'hello'

}

stage('command'){
sh'ls -lart'
}
stage('end'){
echo'pipeline ends'
}

}
