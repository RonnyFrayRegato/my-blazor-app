![Tutorial 6 - Blazor - Build a Blazor Todo List App Screenshot](https://user-images.githubusercontent.com/71354370/135465279-b1f2bea0-c166-4527-8730-b94a6c213bbf.png)

*Hello, my name is Ronny and I am a Software Engineering student at Florida Gulf Coast University in Fort Myers, FL. Here, you will find an Azure Static Web App with .NET and Blazor. This is the link to the website: https://ashy-sand-07a1b4a0f.azurestaticapps.net*

*Below is a link to the tutorial from Microsoft on how to create a new Blazor app.*

// Getting Started Tutorial: https://devblogs.microsoft.com/aspnet/azure-static-web-apps-with-blazor/

*The most recent change to the static web app is the addition of a to-do list app. The screenshot at the top displays the to-do list while also showing the other pages available on the Blazor app. Below is a link to the tutorial from Microsoft on building a Blazor to-do list app.*

// To-Do List Tutorial: https://docs.microsoft.com/en-us/aspnet/core/tutorials/build-a-blazor-app?view=aspnetcore-5.0&pivots=webassembly#build-a-todo-list-blazor-app-1

*The following instructions from the Getting Started Tutorial have been added as an introduction and first steps into creating a new Blazor app.*

# Blazor Starter Application

This template contains an example [Blazor WebAssembly](https://docs.microsoft.com/aspnet/core/blazor/?view=aspnetcore-3.1#blazor-webassembly) client application, a C# [Azure Functions](https://docs.microsoft.com/azure/azure-functions/functions-overview) and a C# class library with shared code.

## Getting Started

Create a repository from the [GitHub template](https://docs.github.com/en/enterprise/2.22/user/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) and then clone it locally to your machine.

Once you clone the project, open the solution in [Visual Studio Code](https://code.visualstudio.com/) or [Visual Studio](https://visualstudio.microsoft.com/vs/preview/vs2022/) and follow these steps:

- In the **API** folder, copy `local.settings.example.json` to `local.settings.json`
- Press **F5** to launch both the client application and the Functions API app. In Visual Studio, you can right click the solution and select both API project and client project as startup projects. 

_Note: If you're using the Azure Functions CLI tools, refer to [the documentation](https://docs.microsoft.com/azure/azure-functions/functions-run-local?tabs=windows%2Ccsharp%2Cbash) on how to enable CORS._

## Template Structure

- **Client**: The Blazor WebAssembly sample application
- **API**: A C# Azure Functions API, which the Blazor application will call
- **Shared**: A C# class library with a shared data model between the Blazor and Functions application

## Deploy to Azure Static Web Apps

This application can be deployed to [Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps), to learn how, check out [our quickstart guide](https://aka.ms/blazor-swa/quickstart).
