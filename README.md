# Push Data to Power BI Datasets/Tables

A tiny example to push data to datasets/tables on Power BI service using custom SSIS component.
The example uses PBIPushData - custom SSIS component and PBIHelper - Desktop App, both available for free.
PBIPushData component & PBIHelper works with free as well as Pro Power BI service.

<a href="http://www.inservit.com/pbidemo">Click here</a> for details on prerequisites, Power BI API restrictions, workarounds and detailed instruction on executing the example.

<h2>Prerequisites</h2>

<h3>Step 1: Register App with Power BI Service</h3>
      <a href="http://www.inservit.com/downloads.html">Download and install PBIPushData SSIS Component</a> 
            Sign in to <a href="https://dev.powerbi.com/apps">https://dev.powerbi.com/apps</a> using your Power BI account.
            Complete section "Tell us about your app"
              Example:
                  <b>App Name:</b> PBIPushData
                  <b>AppType :</b>  Choose Native App
                  <b>URL     :</b> https://login.live.com/oauth20_desktop.srf

            Complete section “Choose APIs to access”
            Register App.
            Save Generated ClientID. This is required for both <i><u>PBIPushData SSIS Component</u></i> and <i><u>PBIHelper</u></i> application.
<h3>Step 2: Azure Permissions</h3>
      Sign in to your Azure account: https://manage.windowsazure.com/
         Click on option Active Directory.
         Click on your native application (registered in Step 3) to manage.
         Click on configure to provide permissions.

          NOTE: If your application is not listed, add your application and provide permissions.

<h3>Step 3: Create Datasets and Tables Using Power BI Helper</h3>
      <a href="http://www.inservit.com/pbiapiinfo.html">Power BI APIs have restrictions for pushing data to Power BI service</a>.   Data can be push to datasets/tables created using Power BI API. 
      Use Power BI Helper application to crete Datasets and Tables to match source data.
      
      <a href="http://www.inservit.com/pbidemo">Click here for detailed instructions.</a>
      
<h3>Step 4: Install PBIPushData SSIS component. </h3>
     <a href="http://www.inservit.com/downloads.html"> Download and install SSIS Destination Component PBIPushData.</a>
     
     Open the package and configure PBIPushData component.
     
     <a href="http://www.inservit.com/pbidemo">Click here for detailed instructions.</a>
