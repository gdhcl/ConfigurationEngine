Prerequisites:
Visual Studio
.net framework 4.0/+
IIS 7.0/+
Powershell 3.0/+


Sales App
Step 1: Get latest code from TFS

Step 2: Replace Web.Config and atlantis under main/salesweb with sites\dev folder files in same form.

Step 3: Comment security section,modules section in web.config under sales.

Step 4: Build your solution

Step 5: Run the Utility as admin user.

Step 6: Go to IIS change the physical path to appropriate physical sales/main/web local path.


Mobile Web
Step 1: Get latest code from TFS for Sales,MYA,IDP,Cart.

Step 2: Get the latest code from Github for Resources[https://confluence.int.godaddy.com/display/MOBI/Shared+Resources]

Step 3: Replace Web.Config and atlantis under all TFS mapped main/web folders with sites\dev folder files in same form.

Step 4: Comment modules section in web.config under sales\main\web.

Step 5: Build all the projects.

Step 6: Run the Utility as admin user.

Step 7: Go to IIS change the physical path to appropriate physical /main/web local path for all the applications.
<<<<<<< HEAD
