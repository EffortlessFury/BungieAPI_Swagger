# BungieAPI_Swagger

A note:

I've been using AutoRest to create my Swagger generated class library for .NET. In the case of AutoRest, if creating the API with the -AddCredentials flag to add support for credentials to the generated client class, you can not use the client itself to Auth, as the class can only be created if Auth credentials (Access Token) are provided at instantiation time.
