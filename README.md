# Forked WebServiceStudio

This is a fork from https://github.com/adnanmasood/WebServiceStudio

### Version 2.2

- Methods are sorted alphabetically by default. Set options value `SortMethods=false` to use the default sort order (menu : _Edit_ > _Options..._).
- Arrays are created as `null` by default. Set options value `InitializeArraysAsNull=false` to always create a one element array (menu : _Edit_ > _Options..._).

------------------------------------------------------------------------------

From the original Readme:

WebServiceStudio
================

This  project was originally inspired from the .NET Webservice Studio tool and was hosted on codeplex with over 100K downloads.
http://webservicestudio.codeplex.com/

Now ported to github, Web Service Studio (v2.1) is now upgraded for framework 4.5.1 / VS.NET 2013.  Future enhancements /wishlist includes the support for Nullable Types, WCF REST style API, UI improvement, Client certificate support, and to allow a complete composite type testing.

Web Service Studio is a tool to invoke webmethods interactively. The user can provide a WSDL endpoint. On clicking button Get the tool fetches the WSDL, generates .NET proxy from the WSDL and displays the list of methods available. The user can choose any method and provide the required input parameters. On clicking Invoke the SOAP request is sent to the server and the response is parsed to display the return value.

This tool is meant for webservice implementers to test their webservices without having to write the client code. This could also be used to access other webservices whose WSDL endpoint is known. 

Please send your questions / comments / contribution requests to adnan.masood@owasp.org


