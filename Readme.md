In out [previous blog](https://devblogs.microsoft.com/dotnet/creating-interactive-net-documentation/), we announced the `dotnet try` global tool to enable developers to create workshops and write content that the users can interact with. This tool can greatly enhance the way the end users learn from your documentation by giving them hands on experince, wihout having to install any editor.

Today, we are announcing the avaialability of the "trydotnet-tutorial" template. This template can be installed as part of the other "dotnet new" templates and can then be used to create a boilerplate template to help content authors understand the basics of the "dotnet try" tooling.

## Setup

1. Install the template

```console
dotnet new -i Microsoft.DotNet.Try.ProjectTemplate.Tutorial --nuget-source https://dotnet.myget.org/F/dotnet-try/api/v3/index.json
```

2. Create a folder to include your tutorial project. In this case my folder name is my_tdn_tutorial

```console
dotnet new trydotnet-tutorial
```



This step would create a project file 