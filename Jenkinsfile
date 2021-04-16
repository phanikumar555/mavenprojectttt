node('master') 
{
    stage('ContinuousDownload_master')
    {
        git 'https://github.com/intelliqittrainings/maven.git'             
    }
    stage('ContinuousBuild_master')
    {
        sh 'mvn package'
    }
}
