pipeline{
node{
stage('checkout'){
checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'da47d6e3-7fee-4018-afff-4a483f5690c8', url: 'https://github.com/aaryan24x7/myjobs.git']]])

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
}
