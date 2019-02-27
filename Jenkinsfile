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
   office365ConnectorSend   message:'Message from Multibranch pipeline', webhookUrl:'https://outlook.office.com/webhook/f77fb87a-e579-4981-a6f3-18c681ba5c2d@72f988bf-86f1-41af-91ab-2d7cd011db47/JenkinsCI/ddb08c145d524ad7a0aedef7ccecf2c9/f77fb87a-e579-4981-a6f3-18c681ba5c2d'
   // Run the maven build
}



