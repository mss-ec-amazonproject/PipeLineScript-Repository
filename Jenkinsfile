node('nodes')
{
    
    def mavenHome = tool name: "maven3.8.3"
 /*   
    properties([buildDiscarder(logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '', numToKeepStr: '5')), pipelineTriggers([pollSCM('* * * * *')])])
    
        stage('Checkout'){
             git branch: 'development', credentialsId: 'd1f2e9f5-2114-4795-87e9-d35f22ea30e0', url: 'https://github.com/mss-ec-amazonproject/maven-web-application.git'        
        }
    
    stage('Build')
    {
        sh "${mavenHome}/bin/mvn clean package"
    }
 
    stage('ExecuteSonarQubeReport')
    {
        sh "${mavenHome}/bin/mvn clean sonar:sonar"
    }
    
    stage('UploadArtifactsIntoNexus')
    {
        sh "${mavenHome}/bin/mvn deploy"
    }
    stage('DeployAppIntoTomcatServer')
{
    sshagent(['662d8c4b-d0d8-46fa-91a2-878e23f6a895']) {
    sh "scp -o StrictHostKeyChecking=no target/maven-web-application.war ec2-user@3.133.95.119://opt/apache-tomcat-9.0.54/webapps/"
}
}    

stage('EmailNotification')
{
    emailext body: '''Build is Over!!

Regards,
g venkatesh,
8688282706''', subject: 'Build is Over!!', to: 'gandikotavenkatesh312@gmail.com'
}
*/
}
