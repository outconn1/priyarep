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
   office365ConnectorSend   message:'Message from Multibranch pipeline', webhookUrl:'https://outlook.office.com/webhook/62363663-ab0d-4b0d-a2c6-a1528f9f8d4a@72f988bf-86f1-41af-91ab-2d7cd011db47/JenkinsCI/afac6abb832a473bb0c411152247db0f/b8c8ad05-edca-46dd-9aa8-1ac857a5c591', color: '800000'
   // Run the maven build
}



