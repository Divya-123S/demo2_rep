pipeline
{
agent any
stages
{
stage('clone')
{
steps{
git 'https://github.com/Divya-123S/demo2_rep.git'
}
}
stage('build')
{
steps{
sh'javac hello.java'
}
}
stage('run')
{
steps
{
sh 'java hello'
}
}
}
}
