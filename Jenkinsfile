node{
stage('checkout'){
checkout changelog: false, poll: false, scm: [$class: 'GitSCM', branches: [[name: '*/master']], browser: [$class: 'GithubWeb'], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '91b9dc38-3327-4971-ab6b-a15dff71fa45', url: 'https://github.com/aaryan24x7/myjobs.git']]]

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
