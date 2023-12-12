This console app uses the GMAIL API to read emails, nested emails, Mail Subject, Body, Date, From Email addresses, and reads Attachments files of an email.     


Steps to setup Gmail API Console Application

Configure Google Developer console for Gmail API 

URL - https://console.developers.google.com
1) Create Google Project.   
2) Create OAuth Consent Screen for Application.  
 3) Enable Gmail API.  
4) Create OAuth 2.0 Client Id to access Gmail API.
5) Clone this project.
6) Open the Console Application in Visual Studio 2019 or later versions.
7) Open NuGet Package Manager Console & run this below command. 
   Install-Package Google.Apis.Gmail.v1   
8) Make sure to update your client secrets on the ClientDetails folder in the project.
9) Run the project and you should see it will start reading your emails from gmail.
10) You can now expand this system for other types of projects.
