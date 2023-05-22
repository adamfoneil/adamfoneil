I'm into C#, SQL Server, modern .NET, Blazor, Razor, and Azure. I love relational data access, [Dapper](https://github.com/StackExchange/Dapper), and I make a couple Dapper extension libraries:
- [Dapper.Repository](https://github.com/adamfoneil/Dapper.Repository), a repository pattern approach to Dapper
- [Dapper.QX](https://github.com/adamfoneil/Dapper.QX), for making inline SQL better and testable
- [Models](https://github.com/adamfoneil/Models), some low-level model class stuff I use everywhere

Along with some SQL Server-related libraries and tools:
- [BackgroundService.Extensions](https://github.com/adamfoneil/BackgroundService.Extensions) cronjob and queue support for .NET web apps
- [SqlServerUtil](https://github.com/adamfoneil/SqlServerUtil) bulk insert, deep copy, and view materializing utilities for SQL Server
- [ModelSync](https://github.com/adamfoneil/ModelSync), a SQL schema diff library that can treat .NET assemblies as data sources. Powers my [ModelSync App](https://github.com/adamfoneil/ModelSync.WinForms)
- [Zinger](https://github.com/adamfoneil/Postulate.Zinger), a SQL client sort of like SSMS specifically for C# productivity. Check out its [Data Migrator](https://github.com/adamfoneil/Postulate.Zinger/wiki/Data-Migrator) feature and its [SqlSchema](https://github.com/adamfoneil/SqlSchema) library.
- [SqlServer.LocalDb](https://github.com/adamfoneil/SqlServer.LocalDb), an integration testing library for SQL Server 
- [Excel2SqlServer](https://github.com/adamfoneil/Excel2SqlServer.Library), an Excel import library
- [DbCache](https://github.com/adamfoneil/DbCache) for throttling API calls to 3rd party services
- [DataTables.Library](https://github.com/adamfoneil/DataTables.Library) has some small ADO.NET helpers

I like helping developers who are stuck. I have a deep background in SQL Server, C#, WinForms, MVC, and .NET Core. If you think I can help with something, please [reach out](mailto:adamosoftware@gmail.com).

I also work with Blazor a lot. Most of my work is closed-source, but I have a couple Razor Class Libraries in progress that are public:
- [PayPalComponenets.RCL](https://github.com/adamfoneil/PayPalComponents.RCL) is a miniature PayPal IPN testing dashboard with a [Pay Now button](https://github.com/adamfoneil/PayPalComponents.RCL/blob/master/PayPalComponents.RCL/Components/PayNowButton.razor) component.
- [KnowledgeBase.RCL](https://github.com/adamfoneil/KnowledgeBase.RCL) is a small knowledge base framework using markdown and Azure blob storage.
- [UserVoice.RCL](https://github.com/adamfoneil/UserVoice.RCL) is a user feedback and acceptance test portal.
- [GitHubIssues.RCL](https://github.com/adamfoneil/GitHubIssues.RCL) lets users see your GitHub Issues within your application. Also its [standalone GitHub client](https://github.com/adamfoneil/GitHubIssues.RCL/tree/master/GitHubApiClient)

I have some closed-source products:
- [Sendhook.net](https://sendhookapp.azurewebsites.net/) for capturing inbound email as HTTP posts at your own endpoints, uses Azure functions, queues, and blob storage. (Note this app is currently stopped, but feel free to ask me about it.)
- [SqlChartify](https://sqlchartify.azurewebsites.net/) for writing queries and getting charts made with [ChartJS](https://www.chartjs.org/).

Some other odds and ends:
- [QuestPdfUtil](https://github.com/adamfoneil/QuestPdfUtil) a very lightweight HTML -> PDF converter
- [RoslynMarkdowner](https://github.com/adamfoneil/RoslynMarkdowner), a utility for generating C# documentation as markdown. I use this whenever I want to provide a reference of methods and parameters for my libraries.
- In [ChunkUpload](https://github.com/adamfoneil/ChunkUpload), I sketched out an approach to supporting large file uploads. A NuGet [package](https://www.nuget.org/packages/AO.AzureUploader) came out of this that I'm using in other projects now.
- [CloudObjects](https://github.com/adamfoneil/CloudObjects) is a REST API project in .NET Core

WinForms stuff:
- [AzDeploy](https://github.com/adamfoneil/AzDeploy), my continuous deployment mechanism for WinForms apps
- [AOLicensing](https://github.com/adamfoneil/AOLicensing) for desktop app gatekeeping and licensing
- [ImgCloudPaste](https://github.com/adamfoneil/ImgCloudPaste), for pasting images and getting screenshot URLs using Azure storage
- [JsonSettings](https://github.com/adamfoneil/JsonSettings), for strong-typed json-based configuration, mainly in WinForms apps, with DPAPI encryption
- [SourceFolderCleanup](https://github.com/adamfoneil/SourceFolderCleanup) another WinForms app I use personally
- [CredManager2](https://github.com/adamfoneil/CredManager2), a password manager I use myself, because it's fun to make stuff like this
- [WinForms.Library](https://github.com/adamfoneil/WinForms.Library), data binding helpers for WinForms. I never made the transition to XAML/WPF, sorry
