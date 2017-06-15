node {
   // Mark the code checkout 'stage'....
   stage 'Checkout'

   // Checkout code from repository
   checkout scm

   // Get the maven tool.
   // ** NOTE: This 'M3' maven tool must be configured
   // **       in the global configuration.

   // Mark the code build 'stage'....
   stage 'Build'
   office365ConnectorSend status:'Master branch', message:'Message from Multibranch pipeline', webhookUrl:'https://outlook.office.com/webhook/9b1297db-b626-4d4b-923a-6d52dd0f60fe@72f988bf-86f1-41af-91ab-2d7cd011db47/JenkinsCI/62eb31ed8c2f48e98966ec2ad82b5b0f/11a97ad3-e780-471d-abd5-0abddae8e624'
   // Run the maven build
}
