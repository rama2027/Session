node('master')
{

stage('Role')

{

sh 'sh $WORKSPACE@script/assumerole.sh'

}

stage(Describe)

{
sh 'sh $WORKSPACE@script/describe.sh'
}
stage(clean)
{
cleanWs()
}
}
