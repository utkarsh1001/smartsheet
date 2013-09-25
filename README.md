smartsheet
==========
Installing unmanaged package

Installation URL:
 
https://login.salesforce.com/packaging/installPackage.apexp?p0=04t90000000EbX8

1. Login to Salesforce Org where you want to install application.
2. Copy above URL & paste in browser url box & Enter.
3. You will see SF Installation Wizard. Keep default values & click continue for all Subsequent windows.

Custom Settings after Installation.

1. Select Your Name > Setup
2. Click Develop > Custom Settings.
3. If Package is installed successfully, You will see Challenge App Settings Object.
4. Click on Manage link present in Action column.
5. Click on New button present above Default Organization Level Value.
6. Fill up following details in present fields.






Smart sheet Client Id = Client Application ID generated in smartsheet.com User account.


Redirect URI	 = Redirect URI specified in Smartsheet application settings.


Smartsheet Client Secret = Client Application Secret generated in Smartsheet application settings.


Use Oauth Flow = Can keep unchecked by default. This field decides if 
                 application should use User-generated smartsheet token 
                 or Oauth token to make subsequent webservice calls to smartsheet webservices.


Remote Site Settings Addition.

Note: these remote site settings are automatically created when package is installed, so user does not need to set it manually. This is just additional helpful information.

Record 1: https://www.smartsheet.com

1. Select Your Name > Setup
2. Click Security Controls > Remote Site Settings.
3. Click on New button & enter following details in fields.


Remote Site Name	
Any name you want. For Ex: Smartsheet.


Remote Site URL	
	
	
https://www.smartsheet.com

Disable Protocol Security	
Keep unchecked as it is.


Description	
Provide some help information for this record. Else leave blank.


Active
	
Default it is checked. Keep it checked.



Record 2: https://api.smartsheet.com


Remote Site Name	
Any name you want without whitespace. For Ex: SmartsheetApi


Remote Site URL	
	
	
https://api.smartsheet.com


Disable Protocol Security	
Keep unchecked as it is.


Description	
Provide some help information for this record. Else leave blank.


Active
	
Default it is checked. Keep it checked.

