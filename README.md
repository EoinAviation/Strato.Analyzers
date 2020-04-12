# Strato.Analyzers
The `Strato.Analyzers` library contains custom StyleCop analyzer configurations for providing consistency throughout all Strato Systems Pty. Ltd. C# source code.

## Packaging
To correctly pack this into a NuGet package, run `dotnet pack -c Release /p:NuspecFile=Strato.Analyzers.nuspec`

## Usage
A NuGet package is available through the GitHub Package Repository [here](https://github.com/EoinAviation/Strato.Analyzers/packages/).
To make this source available in your IDE, add `https://nuget.pkg.github.com/eoinaviation/index.json` to your NuGet package feeds (Tutorials for [Visual Studio](https://docs.microsoft.com/en-us/nuget/consume-packages/install-use-packages-visual-studio#package-sources), [Rider](https://www.jetbrains.com/help/rider/Using_NuGet.html#sources))
Your IDE may prompt you for a username and password, use your GitHub username for the username, and you'll need a personal access token with read access to the GitHub Package registry for the password. More info [here](https://help.github.com/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-dotnet-cli-for-use-with-github-packages)
