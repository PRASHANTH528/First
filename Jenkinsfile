pipeline
agent any
stages
{
stage('clone')
{
steps
{
git 'https://github.com/PRASHANTH528/First.git'
}
}
stage('build')
{
steps
{
sh 'javac HelloWorld.java'
}
}
stage('test')
{
steps
{
sh 'java HelloWorld'
}
}
}

