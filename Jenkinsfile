pipeline{
node{
stage('checkout'){
checkout scm

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
