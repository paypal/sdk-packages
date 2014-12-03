Payflow client SDK for Windows v3 patch
=======================================

**This is a temporary solution for v3 integrations that cannot be immediately upgrades.**  It is *strongly* recommended for you to upgrade to either the new SDKs or use the HTTPS interface.  The V3 SDK will no longer be supported in the near future.

If you are using the V3 Payflow client SDK for Windows and are not able to connect using SSL v3 protocol, you can download the [Payflow-dotnet-v3-patch](Payflow-dotnet-v3-patch.zip) as temporary solution.  Once you download the and unzip the file to your server, you will then need to replace the appropriate DLL, EXE or LIB files from your current integration.  Next, you will need to change the end point to one of the following URLs to use the patch:
 
- Live - https://payflowpro.paypal.com
- Test - https://pilot-payflowpro.paypal.com
 
For other versions download the [latest version of the Payflow SDKs](http://paypal.github.io/sdk/#payflow-gateway) (.Net or Java) or use the HTTPS interface.  See the [Payflow Documentation Guide](https://developer.paypal.com/docs/classic/payflow/integration-guide/) for more information.
 
If you choose to use the HTTPS interface, the [integration wizard](https://devtools-paypal.com/integrationwizard/) can assist you with a working example.  
 
Once you have made the changes you can verify the Client SDK you are using by looking at the transaction details within the Payflow Manager.
 
