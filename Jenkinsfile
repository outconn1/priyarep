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
   office365ConnectorSend   message:'Message from Multibranch pipeline', webhookUrl:'https://outlook.office.com/webhook/184376c3-dda3-4fbe-9514-16ae5b6877ae@72f988bf-86f1-41af-91ab-2d7cd011db47/JenkinsCI/a07cf1294f6d408682932feee58babc9/184376c3-dda3-4fbe-9514-16ae5b6877ae
', color: '800000'
   // Run the maven build
}



