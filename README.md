# [json3-nuget](https://www.nuget.org/packages/JSON3/3.3.0)
## [JSON3](http://git.io/json3) on [NuGet](https://www.nuget.org)

### Updating
 - Update the `json3.js` and `json3.min.js` files in `content/Scripts`.
 - Update `Package.nuspec` to increase version number.
 - Run
   ```
   NuGet.exe Pack Package.nuspec
   NuGet.exe Push JSON3.3.x.x.nupkg
   ```