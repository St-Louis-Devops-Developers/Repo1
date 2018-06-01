node
{
    stage('Checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/bhargav570392/githubtest.git']]])
    }
    
    stage('mail')
    {
        mail bcc: '', body: '''Greetings,
Hope u r doing good.''', cc: 'reply2bhargav94@gmail.com', from: '', replyTo: '', subject: 'Regarding veridic', to: 'brahminikatta@gmail.com'
    }
}
