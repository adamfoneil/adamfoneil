I'm into C#, SQL Server, modern .NET, Blazor, Razor, DigitalOcean, and Azure. I love relational data access, [Dapper](https://github.com/StackExchange/Dapper), and I make a couple Dapper extension libraries:
- [Dapper.Entities](https://github.com/adamfoneil/Dapper.Entities), my latest repository-based library for Dapper
- [Dapper.QX](https://github.com/adamfoneil/Dapper.QX), for making inline SQL better and testable
I've also come around to enjoying EF Core. For the longest time I did not like EF, but I've changed my mind recently.

Along with some SQL Server-related libraries and tools:
- [BackgroundService.Extensions](https://github.com/adamfoneil/BackgroundService.Extensions) cronjob and queue support for .NET web apps
- [Ensync](https://github.com/adamfoneil/Ensync), a SQL schema diff/merge command-line tool, reboot of [ModelSync](https://github.com/adamfoneil/ModelSync)
- [Zinger](https://github.com/adamfoneil/Postulate.Zinger), a SQL client sort of like SSMS specifically for C# productivity. Check out its [Data Migrator](https://github.com/adamfoneil/Postulate.Zinger/wiki/Data-Migrator) feature and its [SqlSchema](https://github.com/adamfoneil/SqlSchema) library. [Zinger2](https://github.com/adamfoneil/Zinger2) in progress
- [SqlServer.LocalDb](https://github.com/adamfoneil/SqlServer.LocalDb), an integration testing library for SQL Server 
- [Excel2SqlServer](https://github.com/adamfoneil/Excel2SqlServer.Library), an Excel import library
- [DbCache](https://github.com/adamfoneil/DbCache) for throttling API calls to 3rd party services
- [DataTables.Library](https://github.com/adamfoneil/DataTables.Library) has some small ADO.NET helpers

I also work with Blazor a lot. Most of my work is closed-source, but I have a couple things in progress that are public:
- [ApiAuthDemo](https://github.com/adamfoneil/ApiAuthDemo) demonstrates a Blazor WASM app using APIs that require authorization
- [LiteInvoice3](https://github.com/adamfoneil/LiteInvoice3) is a freelancer's invoicing app, testing Blazor WASM + Server hybrid architecture
- [PayPalComponenets.RCL](https://github.com/adamfoneil/PayPalComponents.RCL) is a miniature PayPal IPN testing dashboard with a [Pay Now button](https://github.com/adamfoneil/PayPalComponents.RCL/blob/master/PayPalComponents.RCL/Components/PayNowButton.razor) component.
- [UserVoice.RCL](https://github.com/adamfoneil/UserVoice.RCL) is a user feedback and acceptance test portal.
- [GitHubIssues.RCL](https://github.com/adamfoneil/GitHubIssues.RCL) lets users see your GitHub Issues within your application. Also its [standalone GitHub client](https://github.com/adamfoneil/GitHubIssues.RCL/tree/master/GitHubApiClient)

I have some closed-source products:
- [Sendhook.net](https://sendhookapp.azurewebsites.net/) for capturing inbound email as HTTP posts at your own endpoints, uses Azure functions, queues, and blob storage. (Note this app is currently stopped, but feel free to ask me about it.)
- [SqlChartify](https://sqlchartify.azurewebsites.net/) for writing queries and getting charts made with [ChartJS](https://www.chartjs.org/).

Some other odds and ends:
- [QuestPdfUtil](https://github.com/adamfoneil/QuestPdfUtil) a very lightweight HTML -> PDF converter
- [RoslynMarkdowner](https://github.com/adamfoneil/RoslynMarkdowner), a utility for generating C# documentation as markdown. I use this whenever I want to provide a reference of methods and parameters for my libraries.
- In [ChunkUpload](https://github.com/adamfoneil/ChunkUpload), I sketched out an approach to supporting large file uploads. A NuGet [package](https://www.nuget.org/packages/AO.AzureUploader) came out of this that I'm using in other projects now.

WinForms stuff:
- [AzDeploy](https://github.com/adamfoneil/AzDeploy), my continuous deployment mechanism for WinForms apps
- [AOLicensing](https://github.com/adamfoneil/AOLicensing) for desktop app gatekeeping and licensing
- [ImgCloudPaste](https://github.com/adamfoneil/ImgCloudPaste), for pasting images and getting screenshot URLs using Azure storage
