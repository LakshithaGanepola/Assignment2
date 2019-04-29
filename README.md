# Assignment2
Instructions for the Google .NET Client API – Drive.Sample
Browse Online
Browse Source, or main file Program.cs
1. Checkout Instructions
Prerequisites: Install Visual Studio, and Mercurial.

cd [someDirectory] 
hg clone https://code.google.com/p/google-api-dotnet-client.samples/ google-api-dotnet-client-samples

2. API access Instructions

Important: after checking out the project, compiling and running it, you need to do the following:

Visit the Google APIs console

If this is your first time, click "Create project..."

Otherwise, click on the drop down under the "Google APIs" logo at the top left, and click "Create..." under "Other projects"

Click on "API Access", and then on "Create an OAuth 2.0 Client ID...".

Enter a product name and click "Next".

Select "Installed application" and click "Create client ID".

Activate the Drive API for your project.

Setup Project in Visual Studio

Open the GoogleApisSamples.sln with Visual Studio

Click on Build > Rebuild Solution

Execute the .exe in Drive.Sample\bin\Debug
