<b>Device Emulator</b>
<br/>
Used to simulate a device accessing the OAuth2 based device flow as described here - http://identityrelationshipmanagement.blogspot.co.uk/2015/10/device-authorization-using-oauth2-and.html
<br/>
<br/>
<b>Setup</b>
<br/>
Create OAuth2/OIDC client in OpenAM with appropriate scopes.
<br/>
<br/>
<b>To Run</b>
<br/>
Run ./deviceEmulator.sh.  Choose option C to configure the appropriate client secrets from the main menu.
<br/>
NOTE: Pressing C creates .settings file. This file should contain following variables:
<br/>
CLIENT_ID="substitute with your own"
CLIENT_SECRET="substitute with your own"
OPENAM_URL="substitute with your own"
RESPONSE_TYPE="token"
SCOPE="substitute with your own"
<br/>
Select 1 to start flow and follow instructions.
<br/>
<br/>
Use as-is no warranties.  OpenAM 13.0 (nightlies or Enterprise) required.  JQ JSON parser is also assumed to be present - https://stedolan.github.io/jq/download/
