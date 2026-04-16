pipeline{
agent any
tools{ gradle 'GRADLE'
jdk 'JDK'

}
stages{
stage('Checkout'){
steps{
git branch:'main',url:'https://github.com/smshubham2005/MyGradle_Testone.git'
}
}
stage('Build'){
steps{
sh 'gradle build'
}
}
stage('Test'){
steps{
sh 'gradle test'}
}
stage('Run Application'){
steps{
sh 'gradle run'}

}
}
post{
success{
echo 'Build scuucess shubham 1bi23cs200'}
failure{
echo 'failure'
}}
}

