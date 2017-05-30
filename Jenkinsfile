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
   office365ConnectorSend status:'Master branch', message:'Message from Multibranch pipeline', webhookUrl:'https://github.com/outconn/test369.git'
   // Run the maven build
}
