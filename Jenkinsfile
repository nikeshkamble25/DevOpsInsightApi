node
{
    stage('Code Checkout')
    {
        checkout([$class: 'GitSCM',
              branches: [[name: "master^b34c41dcf159a94147eaaaaabc4ab1c226f6d270"]],
              doGenerateSubmoduleConfigurations: false,
              extensions: [],
              submoduleCfg: []])    
    }
}