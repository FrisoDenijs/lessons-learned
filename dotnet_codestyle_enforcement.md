* https://docs.microsoft.com/en-us/dotnet/fundamentals/code-analysis/overview
* https://docs.microsoft.com/en-us/dotnet/fundamentals/code-analysis/configuration-options
* https://makolyte.com/how-to-enable-the-built-in-net-analyzers/
* https://stackoverflow.com/q/70517332/1984657

Example lines for .editorconfig:

    # IDE0060 error on dotnet_code_quality_unused_parameters
    dotnet_code_quality_unused_parameters = all
    dotnet_diagnostic.IDE0060.severity = error
    
Property group in csproj file:

    <PropertyGroup>
        <EnforceCodeStyleInBuild>true</EnforceCodeStyleInBuild>
        <AnalysisLevel>6.0-recommended</AnalysisLevel>
    </PropertyGroup>

* [Code Quality Rules](https://docs.microsoft.com/en-us/dotnet/fundamentals/code-analysis/quality-rules/)
* [Code Style Rules](https://docs.microsoft.com/en-us/dotnet/fundamentals/code-analysis/style-rules/])
