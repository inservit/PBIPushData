# Push Data to Power BI Datasets/Tables

A tiny example to push data to datasets/tables on Power BI service using custom SSIS component.<br />
The example uses <a href="http://www.inservit.com/pbipushdata.html">PBIPushData - custom SSIS component</a> and <a href="http://www.inservit.com/pbihelper.html">PBIHelper - Desktop App</a>, both available for free.
<br />PBIPushData component & PBIHelper works with free as well as Pro Power BI service.

<a href="http://www.inservit.com/pbidemo">Click here</a> for details on prerequisites, Power BI API restrictions, workarounds and detailed instruction on executing the example.

<h2>Prerequisites</h2>

<h3>Step 1: Register App with Power BI Service</h3>
      Sign in to <a href="https://dev.powerbi.com/apps">https://dev.powerbi.com/apps</a> using your Power BI account.
            Complete section "Tell us about your app" <br />
              Example:
<br />              
                  App Name: PBIPushData
<br />                  AppType : Choose Native App
<br />                  URL     : https://login.live.com/oauth20_desktop.srf 

<br />            Complete section “Choose APIs to access” 
<br />            Register App. 
<br />            Save Generated ClientID. 
<br />            This is required for both PBIPushData SSIS Component and PBIHelper application.
            
<h3>Step 2: Azure Permissions</h3>
      Sign in to your Azure account: https://manage.windowsazure.com/
<br />   Click on option Active Directory.
<br />   Click on your native application (registered in Step 1) to manage.
<br />   Click on configure to provide permissions.

<br />   NOTE: If your application is not listed, add your application and provide permissions.

<h3>Step 3: Create Datasets and Tables Using Power BI Helper</h3>
      <a href="http://www.inservit.com/pbiapiinfo.html">Power BI APIs have restrictions for pushing data to Power BI service</a>.   Data can be pushed to datasets/tables created using Power BI API. 
<br />      <a href="http://www.inservit.com/downloads.html"> Download and install Power BI Helper application.</a>
<br />      Use Power BI Helper application to crete Datasets and Tables.
      
<br />      <a href="http://www.inservit.com/pbidemo">Click here for detailed instructions.</a>
      
<h3>Step 4: Install PBIPushData SSIS component. </h3>
     <a href="http://www.inservit.com/downloads.html"> Download and install SSIS Destination Component PBIPushData.</a>
     
<br />     Open the package and configure PBIPushData component.
     
<a href="http://www.inservit.com/pbidemo">Click here for detailed instructions.</a>
