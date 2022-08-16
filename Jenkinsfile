node('master')
{
    stage('Code Checkout')
    {
        checkout([$class: 'GitSCM',
              branches: [[name: "master"]],
              doGenerateSubmoduleConfigurations: false,
              extensions: [],
              submoduleCfg: []])    
    }
}