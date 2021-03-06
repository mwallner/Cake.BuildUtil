# Cake.BuildUtil

This is a custom [Cake](http://cakebuild.net/) script to build C# projects. Run `.\build.ps1` in the `SampleApplication\Source` folder for an example.

## What It Does

Cake.BuildUtil performs a set of given steps:

- Clean
- NuGet restore
- MSBuild
- VSMetrics (Using Visual Studio's Powertool `metrics.exe`)
- VSTest + OpenCover
- [Resharper CLI tools](https://www.jetbrains.com/resharper/features/command-line.html) (DupFinder and InspectCode)

All generated artifacts are saved in the `BuildArtifacts` folder.

## License

[MIT](http://opensource.org/licenses/MIT)
