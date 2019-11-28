node('LOVE')
{
stage('clone')
{
git 'https://github.com/rama2027/Session'
}
stage('Role')

{

sh 'sh $WORKSPACE/assumerole.sh'

}

stage('Describe')

{
sh 'sh $WORKSPACE/describe.sh'
}
}
