# .NET-Core-Exercise
## How to use?
### OSX (maybe also in linux)
* Build the webserver

```
$ cd HttpServer
$ dotnet restore
  Restoring packages for /Users/yunseong/git/dotnet-core-exercise/HttpServer/HttpServer/HttpServer.csproj...
  Lock file has not changed. Skipping lock file write. Path: /Users/yunseong/git/dotnet-core-exercise/HttpServer/HttpServer/obj/project.assets.json
  Restore completed in 521.07 ms for /Users/yunseong/git/dotnet-core-exercise/HttpServer/HttpServer/HttpServer.csproj.

  NuGet Config files used:
      /Users/yunseong/.nuget/NuGet/NuGet.Config

  Feeds used:
      https://api.nuget.org/v3/index.json
```

* Run the webserver

```
$ cd HttpServer
$ dotnet run
Hosting environment: Production
Content root path: /Users/yunseong/git/dotnet-core-exercise/HttpServer/HttpServer/bin/Debug/netcoreapp1.1
Now listening on: http://localhost:5000
Application started. Press Ctrl+C to shut down.
```

* Go to the browser and open `localhost:5000`, then you will see the response from the server.

```
Hello World. The Time is: 10:31:52 PM
```

### Windows (TODO)
Maybe we can build & run this application in VisualStudio
