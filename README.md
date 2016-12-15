# GZipRequestHandler

An ASP.NET Web API message handler that supports decompression of gzip'd data.

All credit goes to StackOverflow user **petriq**. The source of this package was provided by him in response to [this StackOverflow question](http://stackoverflow.com/questions/24180697/how-to-upload-gzip-compressed-data-using-system-net-webclient-in-c-sharp).

The handler is published as a NuGet package.

To enable gzip decompress in your Web API project, add the following line to your _Global.asax_ file:

`GlobalConfiguration.Configuration.MessageHandlers.Add(new GZipRequestHandler());`
