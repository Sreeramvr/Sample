node('master')
{
stage('Download') 
{
    git 'https://github.com/Sreeramvr/Sample.git'
}

stage('Deployment')
{
    
    sh ''' scp   /home/ubuntu/.jenkins/workspace/sample/*.html ubuntu@172.31.44.23:/var/www/html/
'''
}
}