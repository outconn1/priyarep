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
   office365ConnectorSend   message:'Message from Multibranch pipeline', webhookUrl:'https://outlook.office.com/webhook/b8c8ad05-edca-46dd-9aa8-1ac857a5c591@72f988bf-86f1-41af-91ab-2d7cd011db47/JenkinsCI/a4c9856ec4d9469a93e0fea372ef8c9d/b8c8ad05-edca-46dd-9aa8-1ac857a5c591', color: '800000'
   // Run the maven build
}



