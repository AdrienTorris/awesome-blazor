# Awesome Blazor [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[<img src="https://adrientorris.github.io/wwwroot/images/blazor/logo-blazor.png" align="right" width="170">](https://dotnet.microsoft.com/apps/aspnet/web-apps/client)

> A collection of awesome Blazor resources.

Blazor is a .NET web framework using C#/Razor and HTML that runs in the browser with WebAssembly.

Contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/AdrienTorris/awesome-blazor/blob/master/CONTRIBUTING.md) pages first. Thanks to all [contributors](https://github.com/AdrienTorris/awesome-blazor/graphs/contributors), you're awesome and wouldn't be possible without you!

## Contents
* [Introduction](#introduction)
* [General](#general)
* [Sample Projects](#sample-projects)
* [Tutorials](#tutorials)
* [Libraries & Extensions](#libraries--extensions)
* [Videos](#videos)
* [Articles](#articles)
* [Podcasts](#podcasts)
* [Presentations slides](#presentations-slides)
* [Tooling](#tooling)
* [Books](#books)
* [E-Books](#e-books)
* [Courses](#courses)
* [Community](#community)
* [Other Languages](#other-languages)

## Introduction
### What is Blazor
Blazor is a .NET web framework to build client web apps with C#.
Blazor lets you build interactive web UIs using C# instead of JavaScript. Blazor apps are composed of reusable web UI components implemented using C#, HTML, and CSS. Both client and server code is written in C#, allowing you to share code and libraries.
More information on the [official website](https://dotnet.microsoft.com/apps/aspnet/web-apps/client).

### Requirements
Please note that if you want to open Blazor projects in Visual Studio, you must have [Visual Studio 15.7 Preview 1](https://www.visualstudio.com/vs/preview/) or later and the [.NET Core 2.1 Preview 1 SDK](https://www.microsoft.com/net/download/dotnet-core/sdk-2.1.300-preview1).
Recommanded: the latest [Visual Studio 2019 Preview](https://visualstudio.microsoft.com/) and the latest [.NET Core SDK](https://dotnet.microsoft.com/download/dotnet-core/3.0).

Note: the Blazor Visual Studio extension is not longer required since the [ASP.NET Core Preview 7](https://dotnet.microsoft.com/download/dotnet-core/3.0).

Here is the documentation of Microsoft, [Get started](https://docs.microsoft.com/en-us/aspnet/core/blazor/get-started?view=aspnetcore-3.0&tabs=visual-studio) with Blazor.

## General
* [ASP.NET Blog's archives](https://devblogs.microsoft.com/aspnet/category/blazor/) - Archives of the ASP.NET blog about Blazor.
* [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/client) - Official website of Blazor, from Microsoft.
* [Blazor bites](https://chrissainty.com/blazor-bites/) - Blazor bites series by chris Sainty.
* [Blazor-Dev gallery on .NET Foundation](https://dotnet.myget.org/gallery/blazor-dev) - Daily builds of the 'dev' branch of Blazor.
* [Blazor Extensions](https://github.com/BlazorExtensions) - Curated extensions for Microsoft ASP.Net Core Blazor.
* [Blazor University](http://blazor-university.com/) - Unofficial documentation website.
* [Demo](https://blazor-demo.github.io/) - Official demo website.
* [FAQ](https://github.com/aspnet/Blazor/wiki/FAQ) - FAQ.
* [GitHub repository](https://github.com/aspnet/Blazor) - ![GitHub stars](https://img.shields.io/github/stars/aspnet/Blazor?style=flat-square&cacheSeconds=604800) The official Blazor repository.
* ['Hello World' sample](https://github.com/dodyg/practical-aspnetcore/tree/master/projects/blazor) - 'Hello World' sample.
* [Introduction to ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/) - Introduction to ASP.NET Core.
* [Study Blazor](https://studyblazor.com) - Blazor tutorial for beginners, in simple and easy steps starting from basics to advanced concepts with more code snippets.
* [Workshop](https://github.com/dotnet-presentations/blazor-workshop/) - ![GitHub stars](https://img.shields.io/github/stars/dotnet-presentations/blazor-workshop?style=flat-square&cacheSeconds=604800) Build a complete Blazor app and learn about the various Blazor framework features along the way.

## Sample Projects
### Authentication
* [BlazorWithIdentity](https://github.com/stavroskasidis/BlazorWithIdentity) - ![GitHub stars](https://img.shields.io/github/stars/stavroskasidis/BlazorWithIdentity?style=flat-square&cacheSeconds=604800) A sample project showcasing a Blazor app using EF Core with Identity authentication.
* [Blazor.JWTTest](https://github.com/shawty/blazor.jwttest) - ![GitHub stars](https://img.shields.io/github/stars/shawty/blazor.jwttest?style=flat-square&cacheSeconds=604800) JWT authentication for a blazor hosted (Client/Serverside) app with API and Authentication.
* [BlazorAuthenticationSample](https://github.com/christiansparre/BlazorAuthenticationSample) - A sample showing some of the ASP.NET Core Blazor authentication features (also some testing...).
### CMS
* [BlogCore](https://github.com/thangchung/blog-core) - ![GitHub stars](https://img.shields.io/github/stars/thangchung/blog-core?style=flat-square&cacheSeconds=604800) Modern CMS on Domain-driven Design and Clean Architecture patterns.
* [WordDaze](https://github.com/chrissainty/worddaze) - ![GitHub stars](https://img.shields.io/github/stars/chrissainty/worddaze?style=flat-square&cacheSeconds=604800) Blogging application written using Blazor with a WebAPI backend.
* [RapidCMS](https://github.com/ThomasBleijendaal/RapidCMS) - A code-first, extensible Blazor app that generates a CMS for your own database.
### Games
* [AsteroidsWasm](https://github.com/aesalazar/AsteroidsWasm) - ![GitHub stars](https://img.shields.io/github/stars/aesalazar/AsteroidsWasm?style=flat-square&cacheSeconds=604800) A mixed bag of C# projects to see if a single .NET Standard base can run across all common platforms include WebAssembly. [Demo](https://aesalazar.github.io/AsteroidsWasm/).
* [BlazorQuiz](https://github.com/Amine-Smahi/BlazorQuiz) - ![GitHub stars](https://img.shields.io/github/stars/Amine-Smahi/BlazorQuiz?style=flat-square&cacheSeconds=604800) Simple quiz using Blazor.NET and WebAssembly.
* [Blagario](https://github.com/ctrl-alt-d/Blagario) - ![GitHub stars](https://img.shields.io/github/stars/ctrl-alt-d/Blagario?style=flat-square&cacheSeconds=604800) Experimental lab to test blazor server side as multiplayer game engine.
* [BlazorChess](https://github.com/Lupusa87/BlazorChess) - Chess engine implemented with Blazor. [Demo](https://lupblazorchess.z20.web.core.windows.net/).
* [Tzaar](https://github.com/paularundel/tzaar) - Implementation of the board game Tzaar with Blazor and SignalR. [Demo](https://tzaar.azurewebsites.net/).
* [BlazorGameSnake](https://github.com/Lupusa87/BlazorGameSnake) - 2D game snake with customizations, path finding algorithm, and sound effects using SVG. [Demo](https://lupblazorsnake.z20.web.core.windows.net/).
* [Blazor20Questions](https://github.com/MetalMichael/blazor-20-questions) - Client/Server game using Websockets (SignalR) & MongoDB API, with Docker (docker-compose).
* [BlazorDestinationGame](https://github.com/SharePointSean/BlazorDestinationGame) - Quizz about places in the world. [Demo](https://blazordestinationgame.azurewebsites.net/).
* [BlazorDice](https://github.com/shahedc/BlazorDemos/tree/master/BlazorDice) - Roll the dice.
* [BlazorPong](https://github.com/MACEL94/BlazorPong) - Pong in Blazor server side using SignalR Core. [Demo](https://blazorpong-dev-as.azurewebsites.net).
### ToDos
* [BlazorTasks](https://github.com/BorowskiKamil/blazor-tasks) - ![GitHub stars](https://img.shields.io/github/stars/BorowskiKamil/blazor-tasks?style=flat-square&cacheSeconds=604800) To-Do App.
* [Bolero.TodoMVC](https://github.com/fsbolero/TodoMVC) - ![GitHub stars](https://img.shields.io/github/stars/fsbolero/TodoMVC?style=flat-square&cacheSeconds=604800) A TodoMVC clone using Bolero.
* [BlazorAdvancedTodo](https://github.com/EdCharbeneau/BlazorAdvancedTodo) - A Blazor to-do app with state and undo function.
### Others
* [Flight Finder](https://github.com/aspnet/samples/tree/master/samples/aspnetcore/blazor) - ![GitHub stars](https://img.shields.io/github/stars/aspnet/samples?style=flat-square&cacheSeconds=604800) Flight Finder.
* [Oqtane Framework](https://github.com/oqtane/oqtane.framework) - ![GitHub stars](https://img.shields.io/github/stars/oqtane/oqtane.framework?style=flat-square&cacheSeconds=604800) Modular Application Framework for Blazor.
* [BlazorElectronExperiment](https://github.com/SteveSandersonMS/BlazorElectronExperiment.Sample) - ![GitHub stars](https://img.shields.io/github/stars/SteveSandersonMS/BlazorElectronExperiment.Sample?style=flat-square&cacheSeconds=604800) ![Status](https://img.shields.io/static/v1?label=status&message=archived&color=lightgrey) Exploring how a Blazor could be used to build a cross-platform desktop application using [Electron](https://electronjs.org/).
* [Toss.Blazor](https://github.com/RemiBou/Toss.Blazor) - ![GitHub stars](https://img.shields.io/github/stars/RemiBou/Toss.Blazor?style=flat-square&cacheSeconds=604800) Twitter-like web application using Blazor.
* [BlazorFileReader](https://github.com/Tewr/BlazorFileReader) - ![GitHub stars](https://img.shields.io/github/stars/Tewr/BlazorFileReader?style=flat-square&cacheSeconds=604800) Read-only File streams in Blazor. [Demo](https://tewr.github.io/BlazorFileReader/).
* [BlazorBoilerplate](https://github.com/enkodellc/blazorboilerplate) - ![GitHub stars](https://img.shields.io/github/stars/enkodellc/blazorboilerplate?style=flat-square&cacheSeconds=604800) Admin Dashboard / Starter Template with IdentityServer4, MatBlazer for Material Design.
* [BlazeDown](https://github.com/EdCharbeneau/BlazeDown) - ![GitHub stars](https://img.shields.io/github/stars/EdCharbeneau/BlazeDown?style=flat-square&cacheSeconds=604800) BlazeDown, online Markdown editor. [Demo](https://edcharbeneau.com/BlazeDown/).
* [Tour of Heroes](https://github.com/lohithgn/blazor-tour-of-heroes) - ![GitHub stars](https://img.shields.io/github/stars/lohithgn/blazor-tour-of-heroes?style=flat-square&cacheSeconds=604800) Blazor implementation of Angular Tour of Heroes.
* [BlazorChatSample](https://github.com/conficient/blazorchatsample) - ![GitHub stars](https://img.shields.io/github/stars/conficient/blazorchatsample?style=flat-square&cacheSeconds=604800) Blazor chat demo using SignalR JS client with interop.
* [Blazor.Toaster](https://github.com/sotsera/sotsera.blazor.toaster) - ![GitHub stars](https://img.shields.io/github/stars/sotsera/sotsera.blazor.toaster?style=flat-square&cacheSeconds=604800) A Blazor port of Toastr.js.
* [Money](https://github.com/maraf/Money) - ![GitHub stars](https://img.shields.io/github/stars/maraf/Money?style=flat-square&cacheSeconds=604800) A money manager implemented using CQRS+ES. [Demo](https://app.money.neptuo.com/).
* [Runny](https://github.com/Suchiman/Runny) - ![GitHub stars](https://img.shields.io/github/stars/Suchiman/Runny?style=flat-square&cacheSeconds=604800) Prototype of running roslyn in the browser via Blazor. [Demo](https://runny.azurewebsites.net/).
* [Gitter](https://github.com/Blazored/Gitter) - ![GitHub stars](https://img.shields.io/github/stars/Blazored/Gitter?style=flat-square&cacheSeconds=604800) A Blazor Gitter client.
* [NethereumBlazor](https://github.com/Nethereum/NethereumBlazor) - ![GitHub stars](https://img.shields.io/github/stars/Nethereum/NethereumBlazor?style=flat-square&cacheSeconds=604800) Ethereum blockchain explorer and simple wallet.
* [Try F# on WebAssembly](https://github.com/fsbolero/TryFSharpOnWasm) - ![GitHub stars](https://img.shields.io/github/stars/fsbolero/TryFSharpOnWasm?style=flat-square&cacheSeconds=604800) The F# compiler running in WebAssembly with Bolero.
* [BlazingPizza (server side)](https://github.com/ADefWebserver/BlazingPizza) - ![GitHub stars](https://img.shields.io/github/stars/ADefWebserver/BlazingPizza?style=flat-square&cacheSeconds=604800) A server side Blazor version of the Blazing Pizza project from the [Blazor - app building workshop](https://github.com/dotnet-presentations/blazor-workshop/) ![GitHub stars](https://img.shields.io/github/stars/dotnet-presentations/blazor-workshop?style=flat-square&cacheSeconds=604800).
* [BlazorGraphExample](https://github.com/jburman/BlazorGraphExample) - ![GitHub stars](https://img.shields.io/github/stars/jburman/BlazorGraphExample?style=flat-square&cacheSeconds=604800) Example application for connecting to Graph API from Blazor.
* [WebSocketPage](https://github.com/Lupusa87/BlazorWebSocketHelper) - ![GitHub stars](https://img.shields.io/github/stars/Lupusa87/BlazorWebSocketHelper?style=flat-square&cacheSeconds=604800) Web Socket in Blazor. [demo](https://lupblazordemos.z13.web.core.windows.net/WebSocketPage).
* [StarshipTraveler](https://github.com/rstropek/StarshipTraveler) - ![GitHub stars](https://img.shields.io/github/stars/rstropek/StarshipTraveler?style=flat-square&cacheSeconds=604800) A starship traveler demo app built with Blazor for the DevOne 2019 conference.
* [Blazor Survey](https://github.com/nutshellit/Blazor-Survey) - ![GitHub stars](https://img.shields.io/github/stars/nutshellit/Blazor-Survey?style=flat-square&cacheSeconds=604800) A hybrid F#/C# blazor sample app to kick the tyres of
* [BlazorDynamicList](https://github.com/conficient/BlazorDynamicList) - ![GitHub stars](https://img.shields.io/github/stars/conficient/BlazorDynamicList?style=flat-square&cacheSeconds=604800) Dynamic component binding for a generic list. [Demo](https://blazordynamiclist.azurewebsites.net/).
* [Blazor + Sitecore](https://github.com/GoranHalvarsson/SitecoreBlazor) - ![GitHub stars](https://img.shields.io/github/stars/GoranHalvarsson/SitecoreBlazor?style=flat-square&cacheSeconds=604800) Example of dynamic pages and routes with SiteCore and [Helix](https://helix.sitecore.net/). 
* [BlazorServerTree](https://github.com/ctrl-alt-d/BlazorServerTree) - ![GitHub stars](https://img.shields.io/github/stars/ctrl-alt-d/BlazorServerTree?style=flat-square&cacheSeconds=604800) A simple Server-Side Blazor sample app to deal with hierarchical data.
* [BlazorBinding](https://github.com/SQL-MisterMagoo/BlazorBinding) - ![GitHub stars](https://img.shields.io/github/stars/SQL-MisterMagoo/BlazorBinding?style=flat-square&cacheSeconds=604800) Sample Blazor App demonstrating various data binding scenarios.
* [Beam](https://github.com/Dedac/Beam) - A social network demo application. This is the source code of the LinkedIn course "Blazor First Look".
* [C# Minifer](https://github.com/atifaziz/CSharpMinifierDemo) A client-side Blazor application demonstrating live minification of C# code using the [C# Minifier](https://github.com/atifaziz/CSharpMinifier) library. [Demo](https://atifaziz.github.io/CSharpMinifierDemo/).
* [BlazorClockCanvas](https://github.com/Lupusa87/BlazorClockCanvas) - Complex clock based on Canvas. [Demo](https://lupblazorclockcanvas.z20.web.core.windows.net/).
* [Blazor Spreadsheet](https://github.com/Lupusa87/BlazorSpreadsheet) - Spreadsheet app developed in Blazor. [Demo](https://lupblazorspreadsheet.z20.web.core.windows.net/).
* [Client-side RealWorld](https://github.com/burke166/blazor-client-side-realworld-example-app) - [RealWorld](https://github.com/gothinkster/realworld) implementation of Blazor Client-Side. [Demo](https://blazorclientside.computercodeblue.com).
* [BlazorClockSVG](https://github.com/Lupusa87/BlazorClockSVG) - Complex clock based on SVG. [Demo](https://lupblazorclocksvg.z20.web.core.windows.net/).
* [Server-side RealWorld](https://github.com/burke166/blazor-server-side-realworld-example-app) - [RealWorld](https://github.com/gothinkster/realworld) implementation of Blazor Server-Side. [Demo](https://blazorserverside.computercodeblue.com).
* [BlazorPasswordPattern](https://github.com/Lupusa87/BlazorPasswordPattern) - Password pattern based on SVG. [Demo](https://lupblazorpasswordpattern.z20.web.core.windows.net/).
* [BlazorRawHtmlRenderer](https://github.com/Lupusa87/BlazorRawHtmlRenderer) - Raw HTML rendering with Blazor. [Demo](https://lupblazorrawhtml.z20.web.core.windows.net/).
* [BlazePort](https://github.com/EdCharbeneau/BlazePort) - A futuristic ride share app for space travel written in full stack .NET with Blazor.
* [BlazorBeerCalculator](https://github.com/gpeipman/BlazorBeerCalculator) - Offline beer alc. vol. calculator built on Blazor. [Demo](https://gunnarpeipman.com/demos/blazoroffline/).
* [BlazorCalculator](https://github.com/Lupusa87/BlazorCalculator) - Simple calculator with history and ability to use previous results in new calculations. [Demo](https://lupblazorcalculator.z20.web.core.windows.net/).
* [Blazor calculator with expressions](https://github.com/khaledmousa/BlazorCalculator) - A sample numerical expression evaluator in Blazor utilizing an F# library that uses FsLex and FsYacc to parse expressions. [Demo](https://khaledmousa.github.io/).
* [Blazor Charts](https://github.com/SQL-MisterMagoo/Mister-Magoo-Goes-Charting) - Chart components for Blazor.
* [Blazor Converters](https://github.com/lohithgn/blazor-converters) - Blazor Converters is simple converter app written using Blazor, influenced by Windows 10 Calculator.
* [BlazorCRUD](https://github.com/thbst16/BlazorCrud) - Sample line of business application that illustrates key features of Blazor. [Demo](https://becksblazor.azurewebsites.net/).
* [BlazorFormsValidation](https://github.com/Dallas411/BlazorFormsValidation) - Blazor form validation sample.
* [BlazorPaint](https://github.com/Lupusa87/BlazorPaint) - A paint sample with Blazor ([demo](https://lupblazorpaint.z20.web.core.windows.net/)).
* [BlazorPages](https://github.com/fernandreu/blazor-pages) - A sample client-side Blazor app showcasing automatic deployment to GitHub Pages via Azure Pipelines.
* [BlazorServiceWorker](https://github.com/roboriaan/BlazorServiceWorker) - A client-side Blazor template with service worker caching.
* [Blazor Summernote](https://github.com/shawty/blazor.summernote) - Wrapper for the new MS Blazor framework, allowing the use of the Summernote Wysiwyg editor in a form. blazor.
* [Blazor Tree CRUD](https://github.com/ctrl-alt-d/TreeCrud) - CRUD operations with hierarchical data. Blazor Server + GraphQL + EF.
* [Blazor.Universal](https://github.com/pushqrdx/Blazor.Universal) - Example of using Blazor to build Xamarin based UWP application without WebAssembly.
* [BlazorUnmarshalledCanvas](https://github.com/jhwcn/BlazorUnmarshalledCanvas) - Unmarshalled invoking of Canvas 2d context from Blazor.
* [BlazorValidationControls](https://github.com/hishamco/BlazorValidationControls) - Blazor validation controls.
* [Blazor + Electron sample](https://github.com/aspnet/AspLabs/tree/master/src/ComponentsElectron) - Explore how a Blazor app can be used to build a cross-platform desktop app.
* [Data Driven Layout](https://github.com/hutchcodes/Blazor.DataDrivenLayout) - Two ways of driving the layout based on data in the page.
* [Pattern Maker](https://github.com/sapsari/website-blazor-demo) - C# code transformation demo that uses Roslyn and Monaco Editor. [Demo](https://patternmaker.netlify.com/).
* [Rudder Example](https://github.com/kjeske/rudder-example) - Sample application using Rudder state container for Blazor.
* [TaxiFareBlazorServer](https://github.com/EdCharbeneau/TaxiFareBlazorServer) - ML.NET TaxiFare Prediction Model with Blazor Server-Side front end.
* [Tulsa .NET User Group website](https://github.com/devsgarage/tulsa-dnug-website) - Tulsa .NET User Group website.
* [ZoraGen Blazor](https://github.com/friendlyanon/zoragen-blazor) - PWA capable Blazor UI for the [ZoraSharp](https://github.com/kabili207/zora-sharp) library.
* [Planning Poker](https://github.com/duracellko/planningpoker4azure) &ndash; An app to play Planning Poker for distributed teams. The app is implemented using Blazor and shows how to switch between client-side and server-side mode with a configuration change. [Demo](http://planningpoker.duracellko.net).
* [Gjallarhorn](https://github.com/haavamoa/Gjallarhorn) - Compare packages on different NuGet-sources. Demonstating Client-Side Blazor MVVM-style. 
* [C# Regex Tester online](https://github.com/lsvhome/regex-tester) - Online tool for verify .Net regex syntax. ([Demo](https://lsvhome.github.io/regex-tester/)).
* [CssBuilder](https://www.nuget.org/packages/BlazorComponentUtilities/) &ndash; A clean code approach to conditional CSS classes for Razor components in Blazor.
* [EncFS over Google Drive](https://encfs-gdrive.github.io) - Online tool written in Blazor for encrypt/decrypt files in Google Drive.

## Tutorials
* [Blazor workshop](https://github.com/dotnet-presentations/blazor-workshop/) - ![GitHub stars](https://img.shields.io/github/stars/dotnet-presentations/blazor-workshop?style=flat-square&cacheSeconds=604800) Blazor app building workshop by [.NET Foundation](https://www.dotnetfoundation.org/), Blazzing Pizza.
* [ASP.NET Core and Blazor Code Venture: Configuring Azure AD Authentication](https://www.codeproject.com/Articles/5164004/ASP-NET-Core-and-Blazor-Code-Venture-Configuring-A) - August 5, 2019 - ASP.NET Core and Blazor Code Venture: Configuring Azure AD Authentication, on Coe Project.
* [Realtime Blazor Tic-Tac-Toe Game - Bot Vs Multiplayer Using SignalR](https://www.c-sharpcorner.com/article/realtime-blazor-tic-tac-toe-game-bot-vs-multiplayer-using-signalr/) - July 17, 2019 - How to create a realtime bot vs. multiplayer tic-tac-toe game in Blazor using SignalR.
* [TSP with GeneticSharp and Blazor](http://diegogiacomelli.com.br/tsp-with-geneticsharp-and-blazor/) - July 10, 2019 - Using a Blazor client-side app and [GeneticSharp](https://github.com/giacomelli/GeneticSharp) ![GitHub stars](https://img.shields.io/github/stars/giacomelli/GeneticSharp?style=flat-square&cacheSeconds=604800) to solve the TSP (Travelling salesman problem).
* [Blazor client-side app with CRUD operations against a Web API endpoint](http://blog.medhat.ca/2019/05/blazor-app-with-crud-operations-from.html) - May 31, 2019 - Blazor client-side app with CRUD operations against a Web API endpoint. [Source code](https://github.com/medhatelmasry/BlazingSchool) ![GitHub stars](https://img.shields.io/github/stars/medhatelmasry/BlazingSchool?style=flat-square&cacheSeconds=604800). [Video](https://www.youtube.com/watch?v=wkSR3eo4Tek).
* [Get .NET Core 3 and Blazor running on a Raspberry PI](https://gist.github.com/shawty/a55f6d09edc2d381c8bd5bf2f639b2de) - April 24, 2019 - Instructions on how to get the latest .NET Core 3 (as of 24th April 2019) and Blazor running on a Raspberry PI.
* [Blazor TODO list](https://github.com/exceptionnotfound/BlazorToDoList) - ![GitHub stars](https://img.shields.io/github/stars/exceptionnotfound/BlazorToDoList?style=flat-square&cacheSeconds=604800) April 22, 2019 - Blazor TODO list.
* [Archives of 2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#tutorials)

## Libraries & Extensions
### Components
*Reusable components like buttons, inputs, grids and more.*
* [MatBlazor](https://github.com/SamProf/MatBlazor) - ![GitHub stars](https://img.shields.io/github/stars/SamProf/MatBlazor?style=flat-square&cacheSeconds=604800) Material Design components for Blazor. ([Demo](https://www.matblazor.com/)).
* [BlazorStrap](https://github.com/chanan/BlazorStrap) - ![GitHub stars](https://img.shields.io/github/stars/chanan/BlazorStrap?style=flat-square&cacheSeconds=604800) Bootstrap 4 components for Blazor ([Demo](https://chanan.github.io/BlazorStrap/)).
* [Blazorise](https://github.com/stsrki/Blazorise) - ![GitHub stars](https://img.shields.io/github/stars/stsrki/Blazorise?style=flat-square&cacheSeconds=604800) Components for Blazor with support for Bootstrap, Bulma and Material CSS. ([Demo](https://bootstrapdemo.blazorise.com/)).
* [BlazorMaterial](https://github.com/BlazorExtensions/BlazorMaterial) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/BlazorMaterial?style=flat-square&cacheSeconds=604800) Blazor components implementing Google's Material components for web.
* [Canvas](https://github.com/BlazorExtensions/Canvas) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/Canvas?style=flat-square&cacheSeconds=604800) HTML5 Canvas API implementation for Microsoft Blazor.
* [BlazorContextMenu](https://github.com/stavroskasidis/BlazorContextMenu) - ![GitHub stars](https://img.shields.io/github/stars/stavroskasidis/BlazorContextMenu?style=flat-square&cacheSeconds=604800) A context menu component for Blazor ([Demo](https://blazor-context-menu-demo.azurewebsites.net/)).
* [Blazor.FlexGrid](https://github.com/Mewriick/Blazor.FlexGrid) - ![GitHub stars](https://img.shields.io/github/stars/Mewriick/Blazor.FlexGrid?style=flat-square&cacheSeconds=604800) GridView component for Blazor.
* [DevExpress Blazor UI Components](https://github.com/DevExpress/RazorComponents) - ![GitHub stars](https://img.shields.io/github/stars/DevExpress/RazorComponents?style=flat-square&cacheSeconds=604800) UI components including Data Grid, Pivot Grid, and several data editors.
* [ChartJs.Blazor](https://github.com/mariusmuntean/ChartJs.Blazor) - ![GitHub stars](https://img.shields.io/github/stars/mariusmuntean/ChartJs.Blazor?style=flat-square&cacheSeconds=604800) ![Status](https://img.shields.io/static/v1?label=status&message=Not%20maintained%20anymore&color=lightgrey) Blazor Component that wraps ChartJS.
* [ChartJSBlazor](https://github.com/Joelius300/ChartJSBlazor) - ![GitHub stars](https://img.shields.io/github/stars/Joelius300/ChartJSBlazor?style=flat-square&cacheSeconds=604800) Blazor Component that wraps ChartJS. (New fork of [ChartJs.Blazor](https://github.com/mariusmuntean/ChartJs.Blazor) that is maintained).
* [Blazored.Toast](https://github.com/Blazored/Toast) - ![GitHub stars](https://img.shields.io/github/stars/Blazored/Toast?style=flat-square&cacheSeconds=604800) A JavaScript free toast library for Blazor and Razor Component applications.
* [BlazorComponents](https://github.com/muqeet-khan/BlazorComponents) - ![GitHub stars](https://img.shields.io/github/stars/muqeet-khan/BlazorComponents?style=flat-square&cacheSeconds=604800) Reusable components for Blazor. Starting with ChartJS interop.
* [Blazored.Modal](https://github.com/Blazored/Modal) - ![GitHub stars](https://img.shields.io/github/stars/Blazored/Modal?style=flat-square&cacheSeconds=604800) A JavaScript free modal library for Blazor and Razor Components applications.
* [Syncfusion Blazor UI Components](https://github.com/syncfusion/ej2-aspnet-core-blazor-samples) - ![GitHub stars](https://img.shields.io/github/stars/syncfusion/ej2-aspnet-core-blazor-samples?style=flat-square&cacheSeconds=604800) Robust UI components including [Data Grid](https://ej2.syncfusion.com/aspnet-core-razor-components/Grid/DefaultFunctionalities), [Charts](https://ej2.syncfusion.com/aspnet-core-razor-components/Charts/polar), [Scheduler](https://ej2.syncfusion.com/aspnet-core-razor-components/Schedule/TimelineResourceGroup), [Inputs](https://ej2.syncfusion.com/aspnet-core-razor-components/TextBox/DefaultFunctionalities) and several [Editor](https://ej2.syncfusion.com/aspnet-core-razor-components/RichTextEditor/DefaultFunctionalities) components.
* [BlazorGrid](https://github.com/AnkitSharma-007/BlazorGrid) - ![GitHub stars](https://img.shields.io/github/stars/AnkitSharma-007/BlazorGrid?style=flat-square&cacheSeconds=604800) This is a reusable grid component for Blazor which also supports client side pagination.
* [Sotsera.Blazor.Toaster](https://github.com/sotsera/sotsera.blazor.toaster) - ![GitHub stars](https://img.shields.io/github/stars/sotsera/sotsera.blazor.toaster?style=flat-square&cacheSeconds=604800) A Blazor port of Toastr.js. [Demo](https://blazor-toaster.sotsera.com/).
* [Blazor LoadingBar](https://github.com/jsakamoto/Toolbelt.Blazor.LoadingBar) - ![GitHub stars](https://img.shields.io/github/stars/jsakamoto/Toolbelt.Blazor.LoadingBar?style=flat-square&cacheSeconds=604800) Loading bar UI for Client-Side Blazor application.
* [Blazor-Charts](https://github.com/Misfits-Rebels-Outcasts/Blazor-Charts) - ![GitHub stars](https://img.shields.io/github/stars/Misfits-Rebels-Outcasts/Blazor-Charts?style=flat-square&cacheSeconds=604800) SVG charts for Blazor.
* [Grid.Blazor](https://github.com/gustavnavar/Grid.Blazor) - ![GitHub stars](https://img.shields.io/github/stars/gustavnavar/Grid.Blazor?style=flat-square&cacheSeconds=604800) Grid component for Blazor and ASP.NET MVC, supporting filtering, sorting, searching, paging, subgrids and others ([Demo](http://gridblazor.azurewebsites.net)).
* [Blazored.Menu](https://github.com/Blazored/Menu) - ![GitHub stars](https://img.shields.io/github/stars/Blazored/Menu?style=flat-square&cacheSeconds=604800) A JavaScript free menu library for Blazor and Razor Components applications.
* [Blazored.Typeahead](https://github.com/Blazored/Typeahead) - ![GitHub stars](https://img.shields.io/github/stars/Blazored/Typeahead?style=flat-square&cacheSeconds=604800) Auto-complete textbox with local and remote data source, for both Client-side and Server-Side Blazor.
* [NodaTimePicker](https://github.com/nheath99/NodaTimePicker) - ![GitHub stars](https://img.shields.io/github/stars/nheath99/NodaTimePicker?style=flat-square&cacheSeconds=604800) A Date/Time picker component library for Blazor using NodaTime. [Demo](https://nodatimepicker.azurewebsites.net/).
* [Radzen.Blazor](https://github.com/akorchev/razor.radzen.com) - ![GitHub stars](https://img.shields.io/github/stars/akorchev/razor.radzen.com?style=flat-square&cacheSeconds=604800) Native UI components for Blazor. DataGrid, DataList, Tabs, Dialog and more. ([Demo](https://razor.radzen.com/)).
* [BlazorStyled](https://github.com/chanan/BlazorStyled) - ![GitHub stars](https://img.shields.io/github/stars/chanan/BlazorStyled?style=flat-square&cacheSeconds=604800) CSS in Blazor Components ([Demo](https://chanan.github.io/BlazorStyled)).
* [BlazorBits](https://github.com/BlazorBits/BlazorBits) - ![GitHub stars](https://img.shields.io/github/stars/BlazorBits/BlazorBits?style=flat-square&cacheSeconds=604800) Components including [Monaco editor](https://github.com/Microsoft/monaco-editor) ![GitHub stars](https://img.shields.io/github/stars/Microsoft/monaco-editor?style=flat-square&cacheSeconds=604800).
* [BlazorVirtualGrid](https://github.com/Lupusa87/BlazorVirtualGrid) - ![GitHub stars](https://img.shields.io/github/stars/Lupusa87/BlazorVirtualGrid?style=flat-square&cacheSeconds=604800) Reusable, fully configurable component with rows and columns fast virtualization ([Demo](https://lupblazorvirtualgrid.z13.web.core.windows.net/)).
* [BlazorVirtualScrolling](https://github.com/SamProf/BlazorVirtualScrolling) - Virtual Scrolling Component for Blazor
 ([Demo](https://samprof.github.io/BlazorVirtualScrolling/)).
* [BlazorScrollbar](https://github.com/Lupusa87/BlazorScrollbar) - Reusable, fully configurable component with vertical and horizontal scrollbars ([Demo](https://lupblazorscrollbar.z20.web.core.windows.net/)).
* [BlazorSplitter](https://github.com/Lupusa87/BlazorSplitter) - Reusable, fully configurable component with vertical and horizontal splitters and diagonal resizer ([Demo](https://lupblazorsplitter.z20.web.core.windows.net/)).
* [BlazorConfirm](https://github.com/ctrl-alt-d/BlazorConfirm) - A Blazor Wrapper for JS's `Window.confirm()` and `onbeforeunload` as .Net Blazor Component ([Demo](https://ctrl-alt-d.github.io/BlazorConfirm/)).
* [BlazorQuery](https://github.com/kevinjpetersen/BlazorQuery) - jQuery for Blazor (Blazor Library that wraps jQuery completely in C# for use in Blazor).
* [Telerik UI for Blazor](https://www.telerik.com/blazor-ui) - A native set of UI components for Blazor, including grid, charting, and calendar components.
* [TwitterShareButton](https://github.com/jsakamoto/Toolbelt.Blazor.TwitterShareButton) - A Tweet Button component for Blazor.
* [Flexor](https://github.com/DerekChasse/Flexor) - Highly configurable components which let you take full advantage of Flexbox CSS.([Demo](http://flexor.azurewebsites.net/)).
* [Blazor.Validation.DataAnnotation](https://github.com/RemiBou/Blazor.Validation.DataAnnotation) - Library for validating form on a Blazor application using Data Annotation.
* [BlazorDateRangePicker](https://github.com/jdtcn/BlazorDateRangePicker) - A date range picker component library for Blazor. [Demo](https://BlazorDateRangePicker.azurewebsites.net/).
* [BlazorTypography](https://github.com/chanan/BlazorTypography) - A powerful toolkit for building websites with beautiful design ([Demo](https://chanan.github.io/BlazorTypography/)).
* [BlazorGoogleMaps](https://github.com/rungwiroon/BlazorGoogleMaps) - Blazor interop for GoogleMap library.
### Tools & Utilities
*Libraries and extensions for state management, cookies, local storage and other specific tools.*
* [Blazor-Redux](https://github.com/torhovland/blazor-redux) - ![GitHub stars](https://img.shields.io/github/stars/torhovland/blazor-redux?style=flat-square&cacheSeconds=604800) Connecting a Redux state store with Blazor.
* [SignalR](https://github.com/BlazorExtensions/SignalR) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/SignalR?style=flat-square&cacheSeconds=604800) SignalR Core implementation for Blazor. It uses the JavaScript client.
* [Blazor-Fluxor](https://github.com/mrpmorris/blazor-fluxor) - ![GitHub stars](https://img.shields.io/github/stars/mrpmorris/blazor-fluxor?style=flat-square&cacheSeconds=604800) A low-boilerplate Flux/Redux state library for Blazor.
* [Logging](https://github.com/BlazorExtensions/Logging) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/Logging?style=flat-square&cacheSeconds=604800) Microsoft Extension Logging implementation for Blazor.4
* [Storage](https://github.com/BlazorExtensions/Storage) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/Storage?style=flat-square&cacheSeconds=604800) HTML5 Storage API implementation for Microsoft Blazor.
* [Blazor-State](https://github.com/TimeWarpEngineering/blazor-state) - ![GitHub stars](https://img.shields.io/github/stars/TimeWarpEngineering/blazor-state?style=flat-square&cacheSeconds=604800) Manage client side state in Blazor using MediatR pipeline.
* [BlazorStorage](https://github.com/cloudcrate/BlazorStorage) - ![GitHub stars](https://img.shields.io/github/stars/cloudcrate/BlazorStorage?style=flat-square&cacheSeconds=604800) Local and session storage support for Blazor.
* [BlazorDB](https://github.com/chanan/BlazorDB) - ![GitHub stars](https://img.shields.io/github/stars/chanan/BlazorDB?style=flat-square&cacheSeconds=604800) In-memory, persisted to local storage, database for Blazor.
* [BlazorSignalR](https://github.com/csnewman/BlazorSignalR) - ![GitHub stars](https://img.shields.io/github/stars/csnewman/BlazorSignalR?style=flat-square&cacheSeconds=604800) SignalR Core .NET client library for Blazor. It uses the C# client.
* [Blazored.LocalStorage](https://github.com/Blazored/LocalStorage) - ![GitHub stars](https://img.shields.io/github/stars/Blazored/LocalStorage?style=flat-square&cacheSeconds=604800) A library to provide access to local storage in Blazor applications.
* [Blazor.Auth0](https://github.com/Pegazux/Blazor.Auth0) - ![GitHub stars](https://img.shields.io/github/stars/Pegazux/Blazor.Auth0?style=flat-square&cacheSeconds=604800) The library for using [Auth0](https://auth0.com/) in Blazor applications.
* [Notifications](https://github.com/BlazorExtensions/Notifications) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/Notifications?style=flat-square&cacheSeconds=604800) HTML5 Notifications API implementation for Microsoft Blazor.
* [Blazor.Polyfill](https://github.com/Daddoon/Blazor.Polyfill) - ![GitHub stars](https://img.shields.io/github/stars/Daddoon/Blazor.Polyfill?style=flat-square&cacheSeconds=604800) Polyfills for Blazor (for Internet Explorer 11 support and some other browsers).
* [CssBuilder](https://github.com/EdCharbeneau/CssBuilder) - ![GitHub stars](https://img.shields.io/github/stars/EdCharbeneau/CssBuilder?style=flat-square&cacheSeconds=604800) CssBuilder is a Builder pattern for CSS classes to be used with Razor Components.
* [Blazor I18n/Localization Text](https://github.com/jsakamoto/Toolbelt.Blazor.I18nText) - ![GitHub stars](https://img.shields.io/github/stars/jsakamoto/Toolbelt.Blazor.I18nText?style=flat-square&cacheSeconds=604800) Localizing contents text in Blazor ([Demo](https://jsakamoto.github.io/Toolbelt.Blazor.I18nText/)).
* [Blazor.Payments](https://github.com/philipblaquiere/Blazor.Payments) - ![GitHub stars](https://img.shields.io/github/stars/philipblaquiere/Blazor.Payments?style=flat-square&cacheSeconds=604800) Blazor Web Agent port of the Web Payment API standard developed by W3C .
* [Blazored.Localisation](https://github.com/Blazored/Localisation) - ![GitHub stars](https://img.shields.io/github/stars/Blazored/Localisation?style=flat-square&cacheSeconds=604800) A library to provide localisation in client-side Blazor applications.
* [Blazor.Geolocation](https://github.com/AspNetMonsters/Blazor.Geolocation) - ![GitHub stars](https://img.shields.io/github/stars/AspNetMonsters/Blazor.Geolocation?style=flat-square&cacheSeconds=604800) Blazor interop for browers Geolocation apis.
* [Blazor Time Zone Kit](https://github.com/jsakamoto/Toolbelt.Blazor.TimeZoneKit) - ![GitHub stars](https://img.shields.io/github/stars/jsakamoto/Toolbelt.Blazor.TimeZoneKit?style=flat-square&cacheSeconds=604800) A library to provide system time zones and local time zone initialization in Blazor apps.
* [EmbeddedBlazorContent](https://github.com/SamProf/EmbeddedBlazorContent) - ![GitHub stars](https://img.shields.io/github/stars/SamProf/EmbeddedBlazorContent?style=flat-square&cacheSeconds=604800) Library to load embedded content files (js and css) from Blazor libraries in server-side Blazor mode.
* [Blazor Svg Helper](https://github.com/Lupusa87/BlazorSvgHelper) - ![GitHub stars](https://img.shields.io/github/stars/Lupusa87/BlazorSvgHelper?style=flat-square&cacheSeconds=604800) Create SVG elements with children (circle, rectangle, image, text, and others) and render with RenderTreeBuilder.
* [Razor components resting library](https://github.com/egil/razor-components-testing-library) - Prototype testing library that renders Razor Components as HTML and compare the result to an expected result, using the XMLDiff library and Shouldly for writing out error messages. 
* [Blazor Analytics](https://github.com/isc30/blazor-analytics) - Blazor extensions for Analytics.
* [BlazorPrettyCode](https://github.com/chanan/BlazorPrettyCode) - Blazor Code Component for documentation sites. [Demo](https://chanan.github.io/BlazorPrettyCode/).
* [Blazor.EventAggregator](https://github.com/mikoskinen/Blazor.EventAggregator) - Lightweight Event Aggregator for Blazor (Razor Components).
* [Blazor Gamepad](https://github.com/jsakamoto/Toolbelt.Blazor.Gamepad) - Provides gamepad API access for Blazor.
* [Blazor Hotkeys](https://github.com/jsakamoto/Toolbelt.Blazor.Hotkeys) - A library to provide configuration-centric keyboard shortcuts for Blazor.
* [BlazorRealm](https://dworthen.github.io/BlazorRealm/docs/quickstart.html) - Redux state management for Blazor.
* [Blazor.LocalFiles](https://github.com/jburman/W8lessLabs.Blazor.LocalFiles) - Open files in your browser and load into Blazor.
* [Blazor.Sensors](https://github.com/AspNetMonsters/Blazor.Sensors) - Blazor interop for browers sensor apis.
* [Rudder](https://github.com/kjeske/rudder) - Efficient state container for Blazor with concepts similar to the ones in redux, including reducers and sagas.
* [BlazorIntersectionObserver](https://github.com/ljbc1994/BlazorIntersectionObserver) - A Blazor wrapper for the Intersection Observer API.
* [Blazor.SpeechSynthesis](https://github.com/jsakamoto/Toolbelt.Blazor.SpeechSynthesis) - A library to provide Speech Synthesis API access for Blazor.
* [Blazor BarCode](https://barcoderesource.com/blazorbarcode.shtml) &ndash; A barcode library for Blazor using barcode fonts.
### Others
* [Blazor Extensions Home](https://github.com/BlazorExtensions/Home) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/Home?style=flat-square&cacheSeconds=604800) Home for Blazor Extensions.
* [Bolero](https://github.com/fsbolero/Bolero) - ![GitHub stars](https://img.shields.io/github/stars/fsbolero/Bolero?style=flat-square&cacheSeconds=604800) Blazor for F# with hot reloaded templates, type-safe endpoints and routing, remoting, and much more.
* [BlazorMobile](https://github.com/Daddoon/BlazorMobile) - ![GitHub stars](https://img.shields.io/github/stars/Daddoon/BlazorMobile?style=flat-square&cacheSeconds=604800) Launch Blazor as a mobile application on iOS, Android & UWP.
* [NObservable](https://github.com/kekekeks/NObservable) - ![GitHub stars](https://img.shields.io/github/stars/kekekeks/NObservable?style=flat-square&cacheSeconds=604800) MobX-like observables and component instrumentation.
* [Blazor-Dashboard](https://github.com/Misfits-Rebels-Outcasts/Blazor-Dashboard) - ![GitHub stars](https://img.shields.io/github/stars/Misfits-Rebels-Outcasts/Blazor-Dashboard?style=flat-square&cacheSeconds=604800) Admin Dashboard Template Theme for Blazor.
* [BlazorOfficeUIFabric](https://github.com/BlazorExtensions/BlazorOfficeUIFabric) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/BlazorOfficeUIFabric?style=flat-square&cacheSeconds=604800) Microsoft Office Fabric UI port for Blazor.
* [BlazorEmbedLibrary](https://github.com/SQL-MisterMagoo/BlazorEmbedLibrary) - ![GitHub stars](https://img.shields.io/github/stars/SQL-MisterMagoo/BlazorEmbedLibrary?style=flat-square&cacheSeconds=604800) Provides Blazor-style embedded static content files for Razor Components projects.
* [WebSocketHelper](https://github.com/Lupusa87/BlazorWebSocketHelper) - ![GitHub stars](https://img.shields.io/github/stars/Lupusa87/BlazorWebSocketHelper?style=flat-square&cacheSeconds=604800) Helper for Web Socket in Blazor.
* [Bionic](https://bionicframework.github.io/Documentation/) - An Ionic CLI clone for Blazor projects.
* [BlazorFabric](https://github.com/limefrogyank/BlazorFabric) - Blazor port of Microsoft UI Fabric with fluent design. ([Demo](https://blazorfabric.azurewebsites.net/)).
* [BlazorFileSaver](https://github.com/IvanJosipovic/BlazorFileSaver) - Blazor Component wrapper for FileSaver.js. 

## Videos
* [Blazor StateHasChanged Community round up & BlazePort](https://www.twitch.tv/videos/474464917) - August 30, 2019 - Full stack app review. Blazor + MLNET + CosmosDB. [Source Code](https://github.com/EdCharbeneau/BlazePort) ![GitHub stars](https://img.shields.io/github/stars/EdCharbeneau/BlazePort?style=flat-square&cacheSeconds=604800).
* [Let’s Learn Blazor: Navigation in Blazor](https://brianlagunas.com/lets-learn-blazor-navigation-in-blazor) - August 28, 2019 - This video is about navigating in a Blazor application (how to use Blazor routes, pass parameters in routes, and how to handle query string parameters as well).
* [Exploring Blazor - Building Interactive Web Apps Using C#](https://www.youtube.com/watch?v=BjCgD7sW8FA) - August 25, 2019 - There’s been a ton of buzz in the .NET community lately around Blazor. Unlike many hyped technologies however, Blazor seems to have earned the attention. It earned it in part by delivering a solution that gives C# developers what they want but doing so in a way that relied on open web standards. In this session, Microsoft’s Jeremy Likness will go deeper into what Blazor is, how it works and how you can use it to build web apps.
* [Blazor Tips and Tricks](https://www.youtube.com/watch?v=KlPaM0yWWbQ) - August 22, 2019 - Ed Charbeneau shares and answers some of the most frequently asked questions he receives when showing folks Blazor.
* [Building Web Apps with Blazor](https://www.youtube.com/watch?v=dGU5x8hvtRQ) - August 16, 2019 - Building Web Apps with Blazor.
* [Let's learn Blazor!](https://www.twitch.tv/videos/463380254) - August 06, 2019 - Let's learn Blazor! about Blazor validation.
* [Create Blazor App From Scratch Using Oceanware NuGet Packages](https://www.youtube.com/watch?v=0ZLzjLpaNjE) - August 04, 2019 - This video is a live coding session creating a new Blazor server-side app and brining in the Ocean NuGet packages, have a forms app with two-way data binding and rich validation in a few minutes.
* [Demo Blazor App Validation](https://www.youtube.com/watch?v=pBWIafqBf3M) - August 04, 2019 - In this Demo Blazor App Validation for the Ocean Validation Library, I show a Blazor server-side app using the Ocean Validation Library.
* [Blazor StateHasChanged](https://www.twitch.tv/videos/461504625) - August 2, 2019 - Blazor StateHasChanged Community round up & BlazePort. [Source Code](https://github.com/EdCharbeneau/BlazePort) ![GitHub stars](https://img.shields.io/github/stars/EdCharbeneau/BlazePort?style=flat-square&cacheSeconds=604800).
* [Let's Learn Blazor: Dependency Injection](https://www.youtube.com/watch?v=7PsO_YXhy-M) - August 01, 2019 - Episode of the serie "Let's Learn Blazor" by Brian Lagunas, about the dependency injection.
* [Blazor StateHasChanged](https://www.twitch.tv/videos/460574001) - July 31, 2019 - Blazor StateHasChanged Community round up & BlazePort. [Source Code](https://github.com/EdCharbeneau/BlazePort) ![GitHub stars](https://img.shields.io/github/stars/EdCharbeneau/BlazePort?style=flat-square&cacheSeconds=604800).
* [Let's learn Blazor!](https://www.twitch.tv/videos/460080201) - July 30, 2019 - Let's learn Blazor!
* [Let's Learn Blazor: Getting Started](https://www.youtube.com/watch?v=zbXESHQQVsE) - July 29, 2019 - In this video, we install Blazor and create our first Blazor application. Watch as I try to understand how Blazor startup works, create bindings, and add event handlers.
* [Why use Blazor?](https://clips.twitch.tv/WealthyDeliciousNeanderthalPhilosoraptor) - July 24, 2019 - Why use Blazor? Live on Twitch by Jeffrey T. Fritz.
* [ASP.NET Community Standup](https://www.youtube.com/watch?v=hZyjKGgmWWA&list=PL1rZQsJPBU2StolNg0aqvQswETPcYnNKL&index=2) - July 23, 2019 - Last ASP.NET Community Standup about ASP.NET Core 3.0 Preview 7.
* [Build Your First Web Application with Blazor](https://www.youtube.com/watch?v=aqSinXoStAU) - July 22, 2019 - Join Jeff Fritz as he takes you through the steps to build your first application that runs IN the browser with C# and Blazor. By the end of this video, you'll learn how to build a next-generation SPA (single-page application) using HTML, CSS, JavaScript interop, and Blazor.
* [Reporting with a CSS grid and converting to Blazor Client-Side technology](https://www.twitch.tv/videos/455920947) - July 21, 2019 - Reporting with a CSS grid and converting to Blazor Client-Side technology.
* [Razor: Into the Razor'verse](https://www.youtube.com/watch?v=cQeSTdgmPGQ) - July 19, 2019 - The Razor template markup syntax is used throughout ASP.NET. In the next version of ASP.NET, Core Razor is evolving into multiple Razor adaptations such as Razor Tag Helpers, Razor Pages, Blazor, and Razor Components . Learn in this video the key differences between theses variations and see where they align in the ASP.NET road map.
* [Blazor Workshop!](https://www.twitch.tv/videos/454955014) - July 19, 2019 - Blazor Workshop! Learn about WebAssembly and C# in this all day event.
* [Blazor Two-Way Binding](https://www.youtube.com/watch?v=Y9a6rJPrFFI&list=PLvmaC-XMqeBYPTwcm478vs8Rujq2tiVJo&index=4) - July 17, 2019 - Blazor Two-Way Binding, from the Telerik UI for Blazor serie.
* [Blazor Component Events using EventCallback](https://www.youtube.com/watch?v=vdEQBhPoTes&list=PLvmaC-XMqeBYPTwcm478vs8Rujq2tiVJo&index=3) - July 17, 2019 - Blazor Component Events using EventCallback, from the Telerik UI for Blazor serie.
* [Blazor Component Basics](https://www.youtube.com/watch?v=z9BOkBFDbc0&list=PLvmaC-XMqeBYPTwcm478vs8Rujq2tiVJo&index=2) - July 17, 2019 - Blazor Component Basics, from the Telerik UI for Blazor serie.
* [Blazor Quick Start Guide](https://www.youtube.com/watch?v=aaRAZYaJ4xc&list=PLvmaC-XMqeBYPTwcm478vs8Rujq2tiVJo&index=1) - July 17, 2019 - Blazor Quick Start Guide, from the Telerik UI for Blazor serie.
* [Building a Raffle App with C#, Blazor, and Twilio](https://www.twitch.tv/videos/451354500) - July 11, 2019 - Building a Raffle App with C#, Blazor, and Twilio.
* [The Freeze Team - A Blazor Console](https://www.twitch.tv/videos/447594138) - July 3, 2019 -  - The Freeze Team - A Blazor Console.
* [The Freeze Team - A Blazor CLI](https://www.twitch.tv/videos/444377657) - June 26, 2019 - The Freeze Team - A Blazor CLI.
* [Blazor StateHasChanged: BlazePort part 5](https://www.twitch.tv/videos/443598774) - June 24, 2019 - Blazor StateHasChanged: BlazePort part  5, about creating BlazePort, a futuristic ride share app for space travel written in full stack .NET with Blazor. [Source Code](https://github.com/EdCharbeneau/BlazePort) ![GitHub stars](https://img.shields.io/github/stars/EdCharbeneau/BlazePort?style=flat-square&cacheSeconds=604800).
* [Blazor StateHasChanged: BlazePort part 4](https://www.twitch.tv/videos/442689869) - June 22, 2019 - Blazor StateHasChanged: BlazePort part  4, about creating BlazePort, a futuristic ride share app for space travel written in full stack .NET with Blazor. [Source Code](https://github.com/EdCharbeneau/BlazePort) ![GitHub stars](https://img.shields.io/github/stars/EdCharbeneau/BlazePort?style=flat-square&cacheSeconds=604800).
* [Working Through the Blazor Workshop From Scratch](https://www.youtube.com/watch?v=QkVQ6XdIsE0) - June 21, 2019 - Working Through the Blazor Workshop From Scratch, by Ardalis.
* [Blazor, a new framework for browser-based .NET apps](https://www.youtube.com/watch?v=uW-Kk7Qpv5U) - June 20, 2019 - Blazor, a new framework for browser-based .NET apps by Steve Sanderson at the NDC Oslo 2019. [Demo's source code](https://github.com/SteveSandersonMS/presentation-2019-06-NDCOslo) ![GitHub stars](https://img.shields.io/github/stars/SteveSandersonMS/presentation-2019-06-NDCOslo?style=flat-square&cacheSeconds=604800).
* [.NET Core 3.0 with Scott Hunter](https://channel9.msdn.com/Shows/On-NET/NET-Core-30-with-Scott-Hunter) - June 20, 2019 - In this episode, Richard Lander and Scott Hunter get together to discuss some of the highlights that developers can look forward to in this new release of .NET Core.
* [Server-side Blazor in .NET Core 3.0](https://channel9.msdn.com/Shows/On-NET/Server-side-Blazor-in-NET-Core-30) - June 18, 2019 - Server-side Blazor in .NET Core 3.0.
* [ASP.NET Community Standup - .NET Core 3.0 Preview 6](https://www.youtube.com/watch?v=SKnIzX6WFfI&list=PL1rZQsJPBU2StolNg0aqvQswETPcYnNKL&index=0) - June 18, 2019 - ASP.NET Community Standup - .NET Core 3.0 Preview 6.
* [Blazor StateHasChanged: BlazePort part 3](https://www.twitch.tv/videos/440348759) - June 17, 2019 - Blazor StateHasChanged: BlazePort part  3. Video about creating BlazePort, a futuristic ride share app for space travel written in full stack .NET with Blazor. [Source Code](https://github.com/EdCharbeneau/BlazePort) ![GitHub stars](https://img.shields.io/github/stars/EdCharbeneau/BlazePort?style=flat-square&cacheSeconds=604800).
* [Blazor with Material Design Framework, part 1](https://www.youtube.com/watch?v=X4QYcVX6NCw) - June 16, 2019 - Blazor with Material Design Framework - MatBlazor (Part - 1).
* [Blazor StateHasChanged: BlazePort part 2](https://www.twitch.tv/videos/438942939) - June 14, 2019 - Blazor StateHasChanged: BlazePort part  2. Second video about creating BlazePort, a futuristic ride share app for space travel written in full stack .NET with Blazor. [Source Code](https://github.com/EdCharbeneau/BlazePort) ![GitHub stars](https://img.shields.io/github/stars/EdCharbeneau/BlazePort?style=flat-square&cacheSeconds=604800).
* [Blazing Pizza Deep Dive with Daniel Roth](https://www.youtube.com/watch?v=HxZTD0isAxQ) - June 11, 2019 - ASP.NET Community Standup - June 11th, 2019 - Blazing Pizza Deep Dive with Daniel Roth.
* [Blazor - You Want To Run .NET Where?!](https://www.youtube.com/watch?v=t9g-GogZDeo) - June 11, 2019 - Blazor - You Want To Run .NET Where?!.
* [Blazor SPA Framework C# with MongoDB - Part 1](https://www.youtube.com/watch?v=XHbOyEFoPV0) - June 9, 2019 - Blazor SPA Framework C# with MongoDB - Part 1.
* [Blazor in the cloud: Hosting a C# SPA app as a static website in Azure Storage](https://channel9.msdn.com/Shows/Azure-Friday/Blazor-in-the-cloud-Hosting-a-C-SPA-app-as-a-static-website-in-Azure-Storage) - June 7, 2019 - Blazor in the cloud: Hosting a C# SPA app as a static website in Azure Storage.
* [Building a C# Interactive shell in a browser with Blazor (WebAssembly) and Roslyn](https://www.strathweb.com/2019/06/building-a-c-interactive-shell-in-a-browser-with-blazor-webassembly-and-roslyn/) - June 7, 2019 - Building a C# Interactive shell in a browser with Blazor (WebAssembly) and Roslyn.
* [Blazor - Getting Started with Daniel and Mehul](https://www.youtube.com/watch?v=93OtjA8VUgc) - June 6, 2019 - Blazor - Getting Started with Daniel Roth and Mehul Harry, published by DevExpress.
* [Blazor client-side app with CRUD operations against a Web API endpoint](https://www.youtube.com/watch?v=wkSR3eo4Tek) - June 1, 2019 - Blazor client-side app with CRUD operations against a Web API endpoint.
* [Blazor StateHasChanged: BlazePort part 1](https://www.twitch.tv/videos/430658092) - May 27, 2019 - First video about creating BlazePort, a futuristic ride share app for space travel written in full stack .NET with Blazor. [Source Code](https://github.com/EdCharbeneau/BlazePort) ![GitHub stars](https://img.shields.io/github/stars/EdCharbeneau/BlazePort?style=flat-square&cacheSeconds=604800).
* [Blazor CRUD app tutorial - SPA Framework for .NET developers (Part - 2)](https://www.youtube.com/watch?v=TMiFNM_1oZI) - May 22, 2019 - Blazor CRUD app tutorial - SPA Framework for .NET developers (Part - 2).
* [Blazor application state management basics](https://www.youtube.com/watch?v=1o-_78ONM1s) - May 14, 2019 - Blazor application state management basics.
* [Blazor Q/A Live with Daniel Roth from Microsoft Build 2019](https://www.youtube.com/watch?v=zp9wQt8J6hY) - May 14, 2019 - Blazor Q/A Live with Daniel Roth from Microsoft Build 2019.
* [Upgrading to Blazor Preview 4 and Hacking SEO in Client-side Blazor](https://www.youtube.com/watch?v=i2eVseMWidQ) - May 14, 2019 - Upgrading to Blazor Preview 4 and Hacking SEO in Client-side Blazor.
* [.NET is now your Browser OS with Blazor](https://www.recallact.com/presentation/net-now-your-browser-os-blazor) - May 13, 2019 - Talk by Jeremy Likness at the Atlanta DotNetSouth 2019.
* [Continuation of the Tulsa .NET User Group website](https://www.twitch.tv/videos/422982467) - May 10, 2019 - Continuation of the Tulsa .NET User Group website. [Source code](https://github.com/devsgarage/tulsa-dnug-website) ![GitHub stars](https://img.shields.io/github/stars/devsgarage/tulsa-dnug-website?style=flat-square&cacheSeconds=604800) here.
* [Scott Hunter Demos Telerik UI for Blazor](https://clips.twitch.tv/SpookyProudPineapplePeanutButterJellyTime) - May 10, 2019 - Scott Hunter Demos Telerik UI for Blazor.
* [Blazor: C# running in the browser via WebAssembly](https://www.youtube.com/watch?v=8De8DlrCzoY) - May 8, 2019 - "Blazor: C# running in the browser via WebAssembly" by Scott Sauber at the NDC Conference Minnesota. Slides and source code [here](https://scottsauber.com/2019/05/08/ndc-minnesota-talk-blazor-c-running-in-the-browser-via-webassembly/).
* [WebAssembly: Into the WASM'verse](https://www.youtube.com/watch?v=P8rSdOXiyEc) - May 8, 2019 - WebAssembly: Into the WASM'verse.
* [Full stack web development with ASP.NET Core 3.0 and Blazor](https://mybuild.techcommunity.microsoft.com/sessions/77033) - May 7, 2019 - Microsoft Build 2019: Full stack web development with ASP.NET Core 3.0 and Blazor.
* [Serverless web apps with Blazor, Azure Functions, and Azure Storage](https://mybuild.techcommunity.microsoft.com/sessions/77336) - May 6, 2019 - Microsoft Build 2019: Serverless web apps with Blazor, Azure Functions, and Azure Storage.
* [SPA revolution with WebAssembly and ASP.NET Blazor](https://www.youtube.com/watch?v=_gYgkZ1UBQ4) - April 23, 2019 - DevOneConf 2019 - Rainer Stropek - SPA revolution with WebAssembly and ASP.NET Blazor.
* [ASP.NET Community Standup](https://www.youtube.com/watch?v=ap60h3eQE5Y) - April 16, 2019 - ASP.NET Community Standup - Blazor Updates with Dan Roth and Steve Sanderson.
* [ASP NET Core + Blazor](https://www.youtube.com/watch?v=AXwD9S4rOFM) - April 12, 2019 - ASP NET Core + Blazor at the philly.NET Code Camp.
* [Continuation of the Tulsa .NET User Group website](https://www.twitch.tv/videos/409976640) - April 12, 2019 - Continuation of the Tulsa .NET User Group website. [Source code](https://github.com/devsgarage/tulsa-dnug-website) ![GitHub stars](https://img.shields.io/github/stars/devsgarage/tulsa-dnug-website?style=flat-square&cacheSeconds=604800) here.
* [Continuation of the Tulsa .NET User Group website](https://www.twitch.tv/videos/409075153) - April 10, 2019 - Continuation of the Tulsa .NET User Group website. [Source code](https://github.com/devsgarage/tulsa-dnug-website) ![GitHub stars](https://img.shields.io/github/stars/devsgarage/tulsa-dnug-website?style=flat-square&cacheSeconds=604800) here.
* [Blazor tutorial - SPA framework for .NET developers (Part - 1)](https://www.youtube.com/watch?v=hYAOWoL3mmA) - April 10, 2019 - Blazor tutorial - SPA framework for .NET developers (Part - 1).
* [Blazor StateHasChanged: Blazor radio buttons and NuGet packages](https://www.youtube.com/watch?v=GBUGjmZlr7o) - April 9, 2019 - Blazor radio buttons and NuGet packages.
* [What’s Coming with .NET Core 3.0](https://channel9.msdn.com/Events/Visual-Studio/Visual-Studio-2019-Launch-Event/Whats-Coming-with-NET-Core-30) - April 2, 2019 - What’s Coming with .NET Core 3.0.
* [Blazor StateHasChanged: Blazor Shell apps](https://www.youtube.com/watch?v=dNQ7MgPZby4) - March 30, 2019 - Blazor Shell apps.
* [Build amazing web apps with .NET Core](https://channel9.msdn.com/Events/Visual-Studio/Visual-Studio-2019-Launch-Event/VSL107) - March 26, 2019 - Build amazing web apps with .NET Core.
* [ASP.NET Community Standup](https://www.youtube.com/watch?v=WmDXgO0f-MQ) - February 5, 2019 - ASP.NET Community Standup.
* [A New Framework for Browser-based .NET Apps (DevReach 2018)](https://www.youtube.com/watch?v=BnH2h_RJ-d8) - January 14, 2019 - A New Framework for Browser-based .NET Apps (DevReach 2018).
* [Blazor StateHasChanged](https://www.youtube.com/watch?v=sQJfLfA1TQs) - January 7, 2019 - Blazor StateHasChanged using Fluent Validation.
* [Archives of 2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#videos)
* [Archives of 2017](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2017.md#videos)

## Articles
* [Containerising Blazor Applications With Docker (Part 4)](https://chrissainty.com/containerising-blazor-applications-with-docker-deploying-containerised-apps-to-azure-web-app-for-containers/) - September 10, 2019 - Containerising Blazor Applications With Docker (Part 4). [Source code](https://github.com/chrissainty/BlazorServerWithDocker).
* [Combining Razor and Blazor Pages in a Single ASP.NET Core 3 Application](https://mikaelkoskinen.net/post/combining-razor-blazor-pages-single-asp-net-core-3-application) - September 09, 2019 - Combining Razor and Blazor Pages in a Single ASP.NET Core 3 Application. [Source code](https://github.com/mikoskinen/blog/tree/master/blazor-pages-razor-pages-single-app).
* [Blazor Components - DataGrid and Scheduler Enhancements](https://community.devexpress.com/blogs/aspnet/archive/2019/09/09/blazor-components-datagrid-and-scheduler-enhancements-available-in-beta-3.aspx) - September 09, 2019 - Blazor Components - DataGrid and Scheduler Enhancements (available in Beta #3), by DevExpress.
* [A Blazor Application Updater](http://blazorhelpwebsite.com/Blog/tabid/61/EntryId/4352/A-Blazor-Application-Updater.aspx) - September 06, 2019 - A Blazor Application Updater.
* [ASP.NET Core and Blazor updates in .NET Core 3.0 Preview 9](https://devblogs.microsoft.com/aspnet/asp-net-core-and-blazor-updates-in-net-core-3-0-preview-9/) - September 04, 2019 - ASP.NET Core and Blazor updates in .NET Core 3.0 Preview 9.
* [Integrating FluentValidation with Blazor](http://blog.stevensanderson.com/2019/09/04/blazor-fluentvalidation/) - September 04, 2019 - An example of integrating a custom third-party validation system with Blazor's forms, by Steve Sanderson.
* [What's New for ASP.NET Core and Blazor in Final Preview of .NET Core 3.0](https://visualstudiomagazine.com/articles/2019/09/04/aspnet-core-updates.aspx) - September 04, 2019 - What's New for ASP.NET Core and Blazor in Final Preview of .NET Core 3.0.
* [Containerising Blazor Applications With Docker (Part 3)](https://chrissainty.com/containerising-blazor-applications-with-docker-publishing-to-azure-container-registry-using-azure-pipelines/) - September 03, 2019 - Containerising Blazor Applications With Docker (Part 3). [Source code](https://github.com/chrissainty/BlazorServerWithDocker).
* [Using the Refit REST Library With Client-Side Blazor](https://dzone.com/articles/the-refit-rest-library-and-client-side-blazor) - September 03, 2019 - Using the Refit REST Library With Client-Side Blazor, let's see the magic of Refit and Blazor working together.
* [Unit testing Blazor components - a prototype](http://blog.stevensanderson.com/2019/08/29/blazor-unit-testing-prototype/) - August 29, 2019 - A possible approach for testing Blazor components that's as fast as unit testing and as high-level as browser automation, by Steve Sanderson.
* [Using JSON for polymorphic types in C#](https://www.oxfordcc.co.uk/news/using-json-for-polymorphic-types-in-csharp/) - August 28, 2019 - Using Blazor, code written for the front-end has access to all the language features of C#. In particular, it may be useful to have a type hierarchy and make use of polymorphism.
* [Blazor Components - Free Anchor Navigation Tool, by DevExpress](https://community.devexpress.com/blogs/aspnet/archive/2019/08/28/blazor-components-free-anchor-navigation-tool.aspx) - August 28, 2019 - As you may know, Blazor does not currently support navigation via anchors. In addition, Blazor does not support hyperlinks that only include anchor IDs within the href attribute (<a href=”#MyAnchor1”>some text</a>). To help address these limitations, we created a free navigation tool for both client-side and server-side Blazor projects.
* [Containerising Blazor Applications With Docker (Part 2)](https://chrissainty.com/containerising-blazor-applications-with-docker-containerising-a-blazor-webassembly-app/) - August 27, 2019 - Containerising Blazor Applications With Docker (Part 2). [Source code](https://github.com/chrissainty/BlazorServerWithDocker).
* [Blazor – on the server or on the client](https://csharp.christiannagel.com/2019/08/27/blazorserverandclient/) - August 27, 2019 - Blazor, on the server or on the client.
* [How To Build a PDF Viewer With Blazor](https://www.pdftron.com/blog/webviewer/add-webviewer-to-blazor/) - August 23, 2019 - How To Build a PDF Viewer With Blazor. [Source code](https://github.com/PDFTron/webviewer-blazor-sample).
* [Containerising Blazor Applications With Docker (Part 1)](https://chrissainty.com/containerising-blazor-applications-with-docker-containerising-a-blazor-server-app/) - August 21, 2019 - Containerising Blazor Applications With Docker (Part 1). [Source code](https://github.com/chrissainty/BlazorServerWithDocker).
* [ASP.NET Core Blazor — JavaScript Interop](https://medium.com/@maddydeep28/asp-net-core-blazor-javascript-interop-a85086e721b7) - August 21, 2019 - Blazor is here, Will JavaScript be dead? I would say that the answer is NO at-least for now.
* [ASP.NET Core and Blazor updates in .NET Core 3.0 Preview 8](https://devblogs.microsoft.com/aspnet/asp-net-core-and-blazor-updates-in-net-core-3-0-preview-8/) - August 13, 2019 - ASP.NET Core and Blazor updates in .NET Core 3.0 Preview 8.
* [Investigating Drag and Drop with Blazor](https://chrissainty.com/investigating-drag-and-drop-with-blazor/) - August 13, 2019 - Investigating Drag and Drop with Blazor. [Source code](https://github.com/chrissainty/SimpleDragAndDropWithBlazor).
* [How does Blazor works ? Part 2 : building](https://remibou.github.io/Blazor-how-it-works-part-2) - August 10, 2019 - This blog post is the 2nd part of a serie about how blazor (client side) works, from the build process to the update of the UI. The first part started with a "simple" command "dotnet run" and ended with generated classes representing the razor files. This post is about the rest of the building process and the part of it that handle integration with monowasm.
* [Using npm packages with Blazor](https://medium.com/swlh/using-npm-packages-with-blazor-2b0310279320) - August 09, 2019 - Using npm packages with Blazor.
* [Blazor Binding, Events and Parameters](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/4350/Blazor-Binding-Events-and-Parameters.aspx) - August 06, 2019 - Three things that you will usually find yourself using on every Blazor page, Binding, Events, and Parameters, are covered in this article who shows how to build a series of pages including a few that will allow a user to build and edit a list of To Do items.
* [Using Razor Components in a Razor Page](https://www.mikesdotnetting.com/article/338/using-razor-components-in-a-razor-page) - August 05, 2019 - Blog post about how to include a Blazor/Razor component in a Razor Pages application in .NET Core 3.0.
* [IndexedDB in Blazor](https://blog.stevensanderson.com/2019/08/03/blazor-indexeddb/) - August 03, 2019 - Exploring the Reshiru.Blazor.IndexedDB package, by Steve Sanderson.
* [Deploying a Server Side Blazor application to Azure](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/4349/Deploying-A-Server-Side-Blazor-Application-To-Azure.aspx) - August 3, 2019 - Deploying a Server Side Blazor application to Azure.
* [Using a Code-Behind Approach to Blazor Components](https://www.telerik.com/blogs/using-a-code-behind-approach-to-blazor-components) - July 31, 2019 - In this article we'll look into when it's helpful to use a code-behind in your Blazor development, how we benefit and what to expect when re-factoring existing components.
* [Configuring Policy-based Authorization with Blazor](https://chrissainty.com/securing-your-blazor-apps-configuring-policy-based-authorization-with-blazor/) - July 30, 2019 - Part 4 of the serie "Securing Your Blazor Apps", by Chris Sainty.
* [Blazor Components - New Blazor Scheduler Control, Data Grid Enhancements and more (available in Beta #1)](https://community.devexpress.com/blogs/aspnet/archive/2019/07/29/blazor-components-new-blazor-scheduler-control-data-grid-enhancements-and-more-available-in-beta-1.aspx) - July 29, 2019 - The first beta of the DevExpress Blazor UI components includes a new Scheduler component along with a myriad of enhancements designed to improve the overall capabilities of our Blazor product line.
* [Authentication in server-side Blazor applications](https://gunnarpeipman.com/blazor/server-side-blazor-authentication/) - July 25, 2019 - Preview 6 version of ASP.NET Core 3.0 is released and one interesting new feature is authentication and authorization for server-side Blazor applications. This blog post goes through work currently done and shows how authentication works with server-side Blazor applications.
* [ASP.NET Core and Blazor updates in .NET Core 3.0 Preview 7](https://devblogs.microsoft.com/aspnet/asp-net-core-and-blazor-updates-in-net-core-3-0-preview-7/) - July 23, 2019 - ASP.NET Core and Blazor updates in .NET Core 3.0 Preview 7.
* [Configuring Role-based Authorization with client-side Blazor](https://chrissainty.com/securing-your-blazor-apps-configuring-role-based-authorization-with-client-side-blazor/) - July 23, 2019 - Configuring Role-based Authorization with client-side Blazor.
* [Exploring authentication in Blazor](https://www.oqtane.org/Resources/Blog/PostId/527/exploring-authentication-in-blazor) - July 22, 2019 - Exploring authentication in Blazor.
* [How to Dynamically Build the UI in Blazor Components](https://visualstudiomagazine.com/articles/2019/07/19/how-to-dynamically-build.aspx) - July 22, 2019 - You have two tools for generating your initial UI in a Blazor component: ASP.NET's Razor and Blazor's RenderFragment. Here's how to use both to integrate with your C# code (and a warning about what you can't do).
* [Client Side Blazor Authentication with Azure Functions and EasyAuth](https://medium.com/@hurtertyjoil/client-side-blazor-authentication-with-azure-functions-and-easyauth-c454faad657b) - July 20, 2019 - Client Side Blazor Authentication with Azure Functions and EasyAuth.
* [Authentication in server-side Blazor applications](https://gunnarpeipman.com/blazor/server-side-blazor-authentication/) - July 17, 2019 - Authentication in server-side Blazor applications.
* [What is Blazor and why is it important for .Net developers and the web](https://www.onmsft.com/dev-cat/what-is-blazor-and-why-is-it-important-for-net-developers-and-the-web) - July 15, 2019 - What is Blazor and why is it important for .Net developers and the web.
* [Authentication with client-side Blazor using WebAPI and ASP.NET Core Identity](https://chrissainty.com/securing-your-blazor-apps-authentication-with-clientside-blazor-using-webapi-aspnet-core-identity/) - July 10, 2019 - Authentication with client-side Blazor using WebAPI and ASP.NET Core Identity.
* [A Blazor Community Update](https://edcharbeneau.com/blazor-community-update/) - July 9, 2019 - A Blazor Community Update, by Ed Charbeneau.
* [Bringing your Blazor apps to the Desktop with ElectronNET.Blazor](https://medium.com/cloudnimble/bringing-your-blazor-apps-to-the-desktop-with-electronnet-blazor-67701bff82f7) - July 8, 2019 - Harness the power of ASP.NET MVC to build Desktop apps that run on any OS.
* [Creating DEV's offline page using Blazor](https://dev.to/azure/creating-dev-s-offline-page-using-blazor-29dl) - July 5, 2019 - Creating DEV's offline page using Blazor.
* [Introduction to Authentication with Blazor](https://chrissainty.com/securing-your-blazor-apps-introduction-to-authentication-with-blazor/) - July 3, 2019 - Introduction to Authentication with Blazor.
* [Configuring a Server-side Blazor app with Azure App Configuration](https://devblogs.microsoft.com/aspnet/configuring-a-server-side-blazor-app-with-azure-app-configuration/) - July 1, 2019 - Configuring a Server-side Blazor app with Azure App Configuration.
* [Creating a step-by-step end-to-end database Server-Side Blazor application](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/4318/Server-Side-Blazor-Reading-And-Inserting-Data-Into-A-Database-End-To-End.aspx) - June 28, 2019 - Creating a step-by-step end-to-end database Server-Side Blazor application.
* [Using Blazor Components In An Existing MVC Application](https://chrissainty.com/using-blazor-components-in-an-existing-mvc-application/) - June 25, 2019 - Using Blazor Components In An Existing MVC Application.
* [What Is Blazor](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/4336/What-Is-Blazor.aspx) - June 23, 2019 - What Is Blazor.
* [Working with local storage in Blazor](http://danpatrascu.com/working-with-local-storage-in-blazor/) - June 19, 2019 - Working with local storage in Blazor.
* [Blazor setTimeout](https://mrpmorris.blogspot.com/2019/06/blazor-settimeout.html) - June 19, 2019 - About the equivalent of JavaScript's setTimeout in Blazor.
* [Authentication in server-side Blazor applications](https://gunnarpeipman.com/blazor/server-side-blazor-authentication/) - June 17, 2019 - Authentication in server-side Blazor applications.
* [Facebook Authentication And Authorization In Server-Side Blazor App](https://ankitsharmablogs.com/facebook-authentication-and-authorization-in-server-side-blazor-app/) - June 17, 2019 - Authentication And Authorization With Facebook In Server-Side Blazor.
* [Google Authentication And Authorization In Server-Side Blazor App](https://ankitsharmablogs.com/google-authentication-and-authorization-in-server-side-blazor-app/) - June 15, 2019 - Authentication And Authorization With Google In Server-Side Blazor.
* [Blazor Gets Authentication and Authorization in ASP.NET Core 3 Preview 6](https://visualstudiomagazine.com/articles/2019/06/13/aspnet-core-preview-6.aspx) - June 13, 2019 - Blazor Gets Authentication and Authorization in ASP.NET Core 3 Preview 6.
* [ASP.NET Core and Blazor updates in .NET Core 3.0 Preview 6](https://devblogs.microsoft.com/aspnet/asp-net-core-and-blazor-updates-in-net-core-3-0-preview-6/) - June 12, 2019 - ASP.NET Core and Blazor updates in .NET Core 3.0 Preview 6.
* [Prerendering a Client-side Blazor Application](https://chrissainty.com/prerendering-a-client-side-blazor-application/) - June 12, 2019 - Prerendering a Client-side Blazor Application.
* [Web assembly and Blazor: state of art](https://dev.to/samueleresca/web-assembly-and-blazor-state-of-art-3nk2) - June 11, 2019 - Web assembly and Blazor: state of art.
* [Progress Telerik .NET Dev Tools Add Native Blazor UI Components](https://visualstudiomagazine.com/articles/2019/06/07/telerik-blazor.aspx) - June 7, 2019 - Progress Telerik .NET Dev Tools Add Native Blazor UI Components.
* [Getting Started With Blazored Typeahead](https://chrissainty.com/getting-started-with-blazored-typeahead/) - June 5, 2019 - Getting Started With Blazored Typeahead.
* [10 Top Blazor Tools Just a NuGet Away](https://visualstudiomagazine.com/articles/2019/06/04/blazor-nuget.aspx) - June 4, 2019 - 10 Top Blazor Tools Just a NuGet Away.
* [Integrating Blazor into Existing ASP.NET Core Applications](https://visualstudiomagazine.com/articles/2019/05/01/integrating-blazor-aspnet-core.aspx) - June 4, 2019 - Integrating Blazor into Existing ASP.NET Core Applications.
* [What’s new in Azure SignalR 1.1.0 Preview 1](https://devblogs.microsoft.com/aspnet/whats-new-in-azure-signalr-1-1-0-preview-1/) - June 3, 2019 - What’s new in Azure SignalR 1.1.0 Preview 1.
* [Forwarding Refs in Blazor](https://www.samprof.com/2019/06/03/blazor-forwardref) - June 3, 2019 - Technique for automatically passing a ElementRef through a component to one of its children or back from children to parent or among independent components.
* [Building Cross-Platform Desktop Apps using Blazor and Electron.NET](https://maherjendoubi.io/blazor-electron/) - June 1, 2019 - Building Cross-Platform Desktop Apps using Blazor and Electron.NET.
* [WebAssembly and Blazor: A Decades Old Problem Solved](https://www.infoq.com/articles/webassembly-blazor) - May 30, 2019 - WebAssembly and Blazor: A Decades Old Problem Solved.
* [How does Blazor works ? Part 1 : building class from .razor](https://remibou.github.io/Blazor-how-it-works-part-1/) - May 29, 2019 - How does Blazor works ? Part 1 : building class from .razor.
* [Calling gRPC Services With Server-side Blazor](https://chrissainty.com/calling-grpc-services-with-server-side-blazor) - May 29, 2019 - Calling gRPC Services With Server-side Blazor.
* [Architecting Blazor applications: an Angular approach](http://danpatrascu.com/architecting-blazor-applications-an-angular-approach/) - May 29, 2019 - Architecting Blazor applications: an Angular approach.
* [Using MediatR with Blazor](https://talkdotnet.wordpress.com/2019/05/29/using-mediatr-with-blazor/) - May 29, 2019 - Using MediatR with Blazor.
* [Using reference objects in Blazor server-side](https://www.billbogaiv.com/posts/using-reference-objects-in-blazor-server-side) - May 26, 2019 - Using reference objects in Blazor server-side.
* [Why WebAssembly Matters?](https://byterot.blogspot.com/2019/05/why-webassembly-matters.html) - May 18, 2019 - Why WebAssembly Matters?
* [Dynamic components in Blazor](https://www.oqtane.org/Resources/Blog/PostId/522/dynamic-components-in-blazor) - May 16, 2019 - Dynamic components in Blazor.
* [Custom routing in Blazor](https://www.oqtane.org/Resources/Blog/PostId/521/custom-routing-in-blazor) - May 16, 2019 - Custom routing in Blazor.
* [A detailed look at data binding in Blazor](https://chrissainty.com/a-detailed-look-at-data-binding-in-blazor/) - May 15, 2019 - A detailed look at data binding in Blazor.
* [Simple Blazor Game Development Using .NET Core 3.0 Preview, Web API, And Visual Studio 2019](https://www.c-sharpcorner.com/article/asp-net-core-blazor-simple-game-development-using-net-core-3-0-preview-web-api/) - May 14, 2019 - Simple Blazor Game Development Using .NET Core 3.0 Preview, Web API, And Visual Studio 2019.
* [WebAssembly-ifying .NET with Blazor](https://www.telerik.com/blogs/webassembly-ifying-net-with-blazor) - May 14, 2019 - WebAssembly-ifying .NET with Blazor.
* [Exploring Blazor by Making An HTML Table Sortable in .NET Core](https://exceptionnotfound.net/exploring-blazor-by-making-an-html-table-sortable-in-net-core/) - May 13, 2019 - Exploring Blazor by Making An HTML Table Sortable in .NET Core.
* [Data binding in blazor](https://coderethinked.com/data-binding-in-blazor/) - May 13, 2019 - Data binding in blazor.
* [Progressive Web Apps and Blazor is combination you should not miss!](https://medium.com/@janne_mattila/progressive-web-apps-and-blazor-is-combination-you-should-not-miss-c59d9ae91d42) - May 12, 2019 - Progressive Web Apps and Blazor is combination you should not miss.
* [Separating code and presentation of Blazor pages](https://gunnarpeipman.com/blazor/blazor-code-behind/) - May 10, 2019 - Separating code and presentation of Blazor pages.
* [Implementing a List/Details Page in Blazor](https://www.telerik.com/blogs/implementing-a-list-details-page-in-blazor) - May 9, 2019 - Implementing a List/Details Page in Blazor.
* [Blazor Bites Updated and Build 2019 Blazor Roundup](https://chrissainty.com/blazor-bites-updated-and-build-2019-blazor-roundup/) - May 8, 2019 - Blazor Bites Updated and Build 2019 Blazor Roundup.
* [Creating a Database Driven Module For Blazor Oqtane](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/4331/Creating-a-Database-Driven-Module-For-Blazor-Oqtane.aspx) - May 8, 2019 - Creating a Database Driven Module For Blazor Oqtane.
* [Creating a Hello World Module For Blazor Oqtane](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/4330/Creating-a-Hello-World-Module-For-Blazor-Oqtane.aspx) - May 7, 2019 - Creating a Hello World Module For Blazor Oqtane.
* [.NET Core is the Future of .NET](https://devblogs.microsoft.com/dotnet/net-core-is-the-future-of-net/) - May 6, 2019 - .NET Core is the Future of .NET.
* [Unified .NET 5 Unveiled: 'Just One .NET Going Forward'](https://visualstudiomagazine.com/articles/2019/05/06/net-5.aspx) - May 6, 2019 - Unified .NET 5 Unveiled: 'Just One .NET Going Forward'.
* [Comparing Native Blazor Components to Wrapped JavaScript Components](https://www.telerik.com/blogs/comparing-native-blazor-components-to-wrapped-javascript-components) - May 6, 2019 - Comparing Native Blazor Components to Wrapped JavaScript Components.
* [Building a Wizard in Blazor with components and MVVM](https://itnext.io/building-a-wizard-in-blazor-with-components-and-mvvm-96219a7b221c) - May 5, 2019 - Building a Wizard in Blazor with components and MVVM.
* [Announcing Oqtane a modular application framework for Blazor](https://www.oqtane.org/Resources/Blog/PostId/520/announcing-oqtane-a-modular-application-framework-for-blazor) - May 5, 2019 - Announcing Oqtane a modular application framework for Blazor.
* [Unable to find debuggable browser tab in Blazor](https://coderethinked.com/unable-to-find-debuggable-browser-tab-in-blazor/) - May 4, 2019 - Unable to find debuggable browser tab in Blazor.
* [Introducing Telerik UI for Blazor 1.0.0](https://www.telerik.com/blogs/introducing-telerik-ui-for-blazor-1-0-0) - May 2, 2019 - Introducing Telerik UI for Blazor 1.0.0.
* [Get Some Sass Into Your Blazor App](https://chrissainty.com/get-some-sass-into-your-blazor-app/) - May 1, 2019 - Get Some Sass Into Your Blazor App.
* [Blazor on the Server: The Good and the Unfortunate](https://visualstudiomagazine.com/articles/2019/04/01/razor-components.aspx) - April 30, 2019 - Blazor on the Server: The Good and the Unfortunate.
* [Using Blazor to Build a Client-Side Single-Page App with .NET Core](https://exceptionnotfound.net/using-blazor-to-build-a-client-side-single-page-app-with-net-core) - April 22, 2019 - Using Blazor to Build a Client-Side Single-Page App with .NET Core.
* [Working with the View in Blazor MVVM](https://itnext.io/working-with-the-view-in-blazor-mvvm-functions-vs-code-behind-vs-viewmodel-ed3508dba86a) - April 20, 2019 - Working with the View in Blazor MVVM : functions{} vs code behind vs ViewModel.
* [Blazor now in official preview!](https://devblogs.microsoft.com/aspnet/blazor-now-in-official-preview/) - April 18, 2019 - Blazor now in official preview!
* [ASP.NET Core updates in .NET Core 3.0 Preview 4](https://devblogs.microsoft.com/aspnet/asp-net-core-updates-in-net-core-3-0-preview-4/) - April 18, 2019 - ASP.NET Core updates in .NET Core 3.0 Preview 4.
* [Updated Razor support in Visual Studio Code, now with Blazor support](https://devblogs.microsoft.com/aspnet/updated-razor-support-in-visual-studio-code-now-with-blazor-support/) - April 18, 2019 - Updated Razor support in Visual Studio Code, now with Blazor support.
* [Why Blazor Grid Templates will make you question everything](https://www.telerik.com/blogs/why-blazor-grid-templates-will-make-you-question-everything) - April 18, 2019 - Why Blazor Grid Templates will make you question everything.
* [Blazor Update: 'The End of the Experiment Is in Sight'](https://visualstudiomagazine.com/articles/2019/04/18/blazor-update.aspx) - April 18, 2019 - Blazor Update: 'The End of the Experiment Is in Sight'.
* [3 Ways to Communicate Between Components in Blazor](https://chrissainty.com/3-ways-to-communicate-between-components-in-blazor/) - April 17, 2019 - 3 Ways to Communicate Between Components in Blazor.
* [Adding features to a simple Blazor MVVM client with composition](https://itnext.io/adding-features-to-a-simple-blazor-mvvm-client-with-composition-f31bfb01e20a) - April 12, 2019 - Adding features to a simple Blazor MVVM client with composition.
* [Introducing Syncfusion’s ASP.NET Core Blazor / Razor Components](https://blog.syncfusion.com/post/introducing-syncfusions-asp-net-core-blazor-razor-components.aspx) - April 10, 2019 - Introducing Syncfusion’s ASP.NET Core Blazor / Razor Components.
* [Getting Started with TypeScript for JSInterop in Blazor](https://chrissainty.com/getting-started-with-typescript-for-jsinterop-in-blazor/) - April 9, 2019 - Getting Started with TypeScript for JSInterop in Blazor.
* [Using The Blazor Form Validation](https://remibou.github.io/Using-the-Blazor-form-validation/) - April 9, 2019 - Using The Blazor Form Validation.
* [Pure HTML Validation in Blazor](https://shawtyds.wordpress.com/2019/04/05/pure-html-validation-in-blazor/) - April 5, 2019 - Pure HTML Validation in Blazor.
* [Building Components Manually via RenderTreeBuilder](https://chrissainty.com/building-components-via-rendertreebuilder/) - April 3, 2019 - Building Components Manually via RenderTreeBuilder.
* [How to localize texts in your Blazor App?](https://dev.to/j_sakamoto/how-to-localize-texts-in-your-blazor-app-phn) - April 2, 2019 - Localizing contents text in Blazor.
* [Client-side or Server-side](https://thefreezeteam.com/blazor/) - March 31, 2019 - Client-side or Server-side.
* [Managing Page Layouts in Blazor](https://visualstudiomagazine.com/articles/2019/03/01/managing-page-layouts-in-blazor.aspx) - March 29, 2019 - Managing Page Layouts in Blazor.
* [Using FluentValidation for Forms Validation in Razor Components](https://chrissainty.com/using-fluentvalidation-for-forms-validation-in-razor-components/) - March 26, 2019 - Using FluentValidation for Forms Validation in Razor Components.
* [Implementing Client Side Search As You Type Using bind-value-oninput](https://scottsauber.com/2019/03/25/blazor-implementing-client-side-search-as-you-type-using-bind-value-oninput/) - March 25, 2019 - Blazor: Implementing Client Side Search As You Type Using bind-value-oninput.
* [What is Blazor and what is Razor Components?](https://www.hanselman.com/blog/WhatIsBlazorAndWhatIsRazorComponents.aspx) - March 19, 2019 - What is Blazor and what is Razor Components?
* [Using JavaScript Interop in Razor Components and Blazor](https://chrissainty.com/using-javascript-interop-in-razor-components-and-blazor/) - March 19, 2019 - Using JavaScript Interop in Razor Components and Blazor.
* [Deploying Blazor Apps Using Azure Pipelines](https://chrissainty.com/deploying-blazor-apps-using-azure-pipelines/) - March 12, 2019 - Deploying Blazor Apps Using Azure Pipelines.
* [Blazor 0.9.0 experimental release now available](https://devblogs.microsoft.com/aspnet/blazor-0-9-0-experimental-release-now-available/) - March 7, 2019 - Blazor 0.9.0 experimental release now available.
* [Full Stack C# with Blazor](https://msdn.microsoft.com/magazine/mt833288) - March 7, 2019, Full Stack C# with Blazor.
* [Understanding cascading values & cascading parameters](https://chrissainty.com/understanding-cascading-values-and-cascading-parameters/) - February 26, 2019 - Understanding cascading values & cascading parameters.
* [What’s the Difference Between Razor and Blazor?](https://espressocoder.com/2019/02/21/whats-the-difference-between-razor-and-blazor/) - February 21, 2019 - What’s the Difference Between Razor and Blazor?
* [No need to duel! Use Blazor Components Dynamic Dual Mode!](https://thefreezeteam.com/razor-components-dynamic-dual-mode/) - February 20, 2019 - No need to duel! Use Blazor Components Dynamic Dual Mode!
* [Configuring a Blazor app](https://remibou.github.io/Configuring-a-Blazor-app/) - February 18, 2019 - Configuring a Blazor app.
* [Microsoft updates Blazor, now built on Razor Components](https://visualstudiomagazine.com/articles/2019/02/13/blazor-0-8-0.aspx) - February 13, 2019 - Microsoft updates Blazor, now built on Razor Components.
* [Dealing with Forms in Blazor](https://msdn.microsoft.com/en-us/magazine/mt833274.aspx) - February 8, 2019 - Dealing with Forms in Blazor.
* [Blazor 0.8.0 experimental release now available](https://blogs.msdn.microsoft.com/webdev/2019/02/05/blazor-0-8-0-experimental-release-now-available/) - February 5, 2019 - Blazor 0.8.0 experimental release now available.
* [Blazored modal released](https://chrissainty.com/blazored-modal-released/) - February 5, 2019 - Blazored modal released.
* [Event Aggregator for ASP.NET Core 3 Razor Components / Blazor](https://mikaelkoskinen.net/post/blazor-event-aggregator-razor-components) - February 4, 2019 - Blazor.EventAggregator - Event Aggregator for ASP.NET Core 3 Razor Components / Blazor.
* [ASP.NET Core updates in .NET Core 3.0 Preview 2](https://blogs.msdn.microsoft.com/webdev/2019/01/29/aspnet-core-3-preview-2/) - January 29, 2019 - ASP.NET Core updates in .NET Core 3.0 Preview 2.
* [Blazor Notes from NDC London](https://edcharbeneau.com/blazor-ndc-london) - January 29, 2019 - Blazor Notes from NDC London.
* [Creating a Reusable, JavaScript-Free Blazor Modal](https://www.telerik.com/blogs/creating-a-reusable-javascript-free-blazor-modal) - January 28, 2019 - Creating a Reusable, JavaScript-Free Blazor Modal.
* [Google authentication in Server-Side Blazor](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/4323/Google-Authentication-in-Server-Side-Blazor-Razor-Components.aspx) - January 21, 2019 - Google authentication in Server-Side Blazor (Razor components).
* [Announcing Blazored and Blazored Toast](https://chrissainty.com/announcing-blazored-and-blazored-toast) - January 21, 2019 - Announcing Blazored and Blazored Toast.
* [Blazor Full-Stack Web Dev in ASP .NET Core](https://wakeupandcode.com/blazor-full-stack-web-dev-in-asp-net-core/) - January 16, 2019 - Blazor Full-Stack Web Dev in ASP .NET Core.
* [Introducing the Telerik UI for Blazor Early Preview](https://www.telerik.com/blogs/introducing-the-telerik-ui-for-blazor-early-preview) - January 16, 2019 - Introducing the Telerik UI for Blazor Early Preview.
* [Creating a top menu search bar in Blazor](https://streamwriter.net/creating-a-top-menu-search-bar-in-blazor/) - January 12, 2019 - Creating a top menu search bar in Blazor.
* [Exception Handling In Blazor](https://remibou.github.io/Exception-handling-in-Blazor/) - January 10, 2019 - Exception Handling In Blazor.
* [Zero to Azure Hero with ASP.NET Core, Blazor, Azure DevOps, Cognitive Services, SonarCloud and App Services](https://stevenknox.net/zero-to-azure-hero-with-asp-net-core-blazor-azure-devops-cognitive-services-and-app-services/) - January 5, 2019 - Zero to Azure Hero with ASP.NET Core, Blazor, Azure DevOps, Cognitive Services, SonarCloud and App Services.
* [MVVM Support in Blazor](https://blog.jeremylikness.com/blog/2019-01-04_mvvm-support-in-blazor) - January 4, 2019 - MVVM Support in Blazor.
* [From Angular to Blazor: The Health App](https://blog.jeremylikness.com/from-angular-to-blazor-the-health-app-2e36077d641c) - January 3, 2019 - From Angular to Blazor: The Health App.
* [An Introduction to Templated Components in Blazor](https://visualstudiomagazine.com/articles/2018/12/01/blazor-templated-components.aspx) - January 3, 2019 - An Introduction to Templated Components in Blazor.
* [Archives of 2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#articles)
* [Archives of 2017](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2017.md#articles)
  
## Podcasts
* [Blazor with Daniel Roth](https://devchat.tv/adventures-in-dotnet/net-003-blazor-with-daniel-roth/) - September 03, 2019 - Daniel Roth starts by introducing Web Assembly and how this changed web development. Blazor allows full-stack development through .NET with C#. The panel asks Dan about Blazor's capabilities and future. Dan shares Blazor’s origin story.
* [What is WebAssembly](https://cynicaldeveloper.com/podcast/122/) - September 02, 2019 - What is WebAssembly, episode 122 of the Cynical Developer podcast.
* [Building Applications using Server-Side Blazor with Shaun Walker](https://www.dotnetrocks.com/default.aspx?ShowNum=1649) - August 22, 2019 - .NET Rocks! podcast, episode 1649: Building Applications using Server-Side Blazor with Shaun Walker.
* [Daniel Roth on Blazor](http://azuredevopspodcast.clear-measure.com/daniel-roth-on-blazor-devops-episode-47) - July 29, 2019 - Azure DevOps Podcast, Episode 47: Daniel Roth on Blazor DevOps. 
* [Blazor with Ed Charbeneau](http://codingafterwork.se/2019/07/17/episode-43-blazor-with-ed-charbeneau/) - July 17, 2019 - Coding After Work podcast, Episode 43 – Blazor with Ed Charbeneau.
* [MS Dev Show - Blazor with Ed Charbeneau](https://msdevshow.com/2019/06/blazor-with-ed-charbeneau/) - June 24, 2019 - MS Dev Show - Blazor with Ed Charbeneau.
* [.NET Core Show Podcast, Episode 27 - Blazored with Chris Sainty](https://dotnetcore.show/episode-27-blazroed-with-chris-sainty/) - June 14, 2019 - .NET Core Show Podcast, Episode 27 - Blazored with Chris Sainty.
* [Blazor with Ed Charbeneau](https://6figuredev.com/podcast/episode-095-blazor-with-ed-charbeneau/) - June 10, 2018 - The 6 Figure Developer Podcast, Episode 095 – Blazor with Ed Charbeneau.
* [Blazor - You Want To Run .NET Where?!](https://dotnetcore.show/episode-25-blazor-you-want-to-run-net-where/) - May 17, 2019 - .NET Core Show - Episode 25 - Blazor - You Want To Run .NET Where?!
* [The Cynical Developer - Blazor](https://cynicaldeveloper.com/podcast/108) - February 18, 2019 - Episode 108 of The Cynical Developer - Blazor.
* [Blazor in 2019 with Steve Sanderson and Dan Roth](https://player.fm/series/net-rocks-2353294/blazor-in-2019-with-steve-sanderson-and-dan-roth) - February 14, 2019 - .NET Rocks, Blazor in 2019 with Steve Sanderson and Dan Roth.
* [Archives of 2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#podcasts)
* [Archives of 2017](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2017.md#podcasts)

## Presentations slides
* [Blazor, a new framework for browser-based .NET apps](https://github.com/SteveSandersonMS/presentation-2019-06-NDCOslo) - ![GitHub stars](https://img.shields.io/github/stars/SteveSandersonMS/presentation-2019-06-NDCOslo?style=flat-square&cacheSeconds=604800) June 20, 2019 - Blazor, a new framework for browser-based .NET apps, by Steve Sanderson at the NDC Oslo.
* [Hidden gems in ASP.Core and .NET Core 3.0](https://speakerdeck.com/davidfowl/hidden-gems-in-asp-dot-core-and-net-core-3-dot-0) - June 19, 2019 - Hidden gems in ASP.Core and .NET Core 3.0, by David Fowler and Damian Edwards at the NDC Oslo.
* [Meet the production-ready Blazor aka Razor Components](https://codecamp.ro/timisoaraSpring) - May 25, 2019 - Slides: [PPTX](https://codecampro.blob.core.windows.net/sessions-upload/1306-CCBlazor.pptx).
* [Iowa .NET User Group – Blazor: C# Running in the Browser via WebAssembly](https://scottsauber.com/2019/05/02/iowa-net-user-group-blazor-c-running-in-the-browser-via-webassembly/) - May 2, 2019 - Slides: [PDF](https://scottsauber.files.wordpress.com/2019/05/blazor.pdf) or [PPTX](https://scottsauber.files.wordpress.com/2019/05/blazor.pptx). Code: [Blazor ToDoMVC](https://github.com/scottsauber/BlazorToDoMVC) ![GitHub stars](https://img.shields.io/github/stars/scottsauber/BlazorToDoMVC?style=flat-square&cacheSeconds=604800) and [Blazor on Electron](https://github.com/SteveSandersonMS/BlazorElectronExperiment.Sample) ![GitHub stars](https://img.shields.io/github/stars/SteveSandersonMS/BlazorElectronExperiment.Sample?style=flat-square&cacheSeconds=604800).
* [WebAssembly, C#, and Blazor at CodeStock 2019](https://blog.jeremylikness.com/presentation-webassembly-c-and-blazor-at-codestock-2019-ab2f8636356) - April 16, 2019 - Slides: [PDF](https://jlikme.blob.core.windows.net/presentations/ATaleOfShortLinks.pdf). Demo's source code: [GitHub](https://github.com/JeremyLikness/blazor-wasm) ![GitHub stars](https://img.shields.io/github/stars/JeremyLikness/blazor-wasm?style=flat-square&cacheSeconds=604800).
* [Archives of 2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#presentations-slides)

## Tooling
* [ASP.NET Core Blazor Language Services](https://marketplace.visualstudio.com/items?itemName=aspnet.blazor) - ![Status](https://img.shields.io/static/v1?label=status&message=obsolete&color=lightgrey) Provides Visual Studio support for ASP.NET Core Blazor. Note: this Blazor Visual Studio extension is obsolete and no longer required to use Blazor since Visual Studio 2019 Preview 16.3.0.
* [BlazorFiddle](https://blazorfiddle.com) - Blazor .Net Developer Playground and Code Editor in the Browser.
* [Blazor Minimum Project Templates](https://github.com/jsakamoto/BlazorMinimumTemplates) - ![GitHub stars](https://img.shields.io/github/stars/jsakamoto/BlazorMinimumTemplates?style=flat-square&cacheSeconds=604800) A project templates package of Blazor apps without JavaScript and CSS libraries.
* [Blazor Snippets Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=ScottSauber.blazorsnippets) - A Visual Studio Code extension that offers Blazor and Razor snippets.
* [BlazorSourceMangler](https://github.com/Lupusa87/BlazorSourceMangler) - ![GitHub stars](https://img.shields.io/github/stars/Lupusa87/BlazorSourceMangler?style=flat-square&cacheSeconds=604800) A console app to mangle blazor dlls. Check this [YouTube video](https://www.youtube.com/watch?v=nlXax81b1UE) for more details. You can also check this [Blazor TODO app](https://lupblazortodo.z20.web.core.windows.net/) to see result of this app (downloaded blazortodos.dll is mangled and decompilation shows uglyfied code).
* [.NET Core](https://www.microsoft.com/net/download/dotnet-core) - .NET Core.
* [Razor+ Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=austincummings.razor-plus) - A Visual Studio Code extension that offers improved Razor support.
* [Visual Studio](https://www.visualstudio.com/vs/preview) - Latest preview of Visual Studio.
* [Visual Studio Code](https://code.visualstudio.com/) - Visual Studio Code, free, open source and cross-platform code editor.

## Books
* [Blazor Revealed](https://www.apress.com/gp/book/9781484243428) - Blazor Revealed, Building Web Applications in .NET(Published February, 2019).
* [Blazor Quick Start Guide: Build web applications using Blazor, EF Core, and SQL Server](https://www.amazon.in/gp/product/178934414X/ref=awesome_blazor) - Blazor Quick Start Guide: Build web applications using Blazor, EF Core, and SQL Server (Published October 31, 2018).

## E-Books
* [An Introduction to Building Applications with Blazor](https://www.amazon.com/Introduction-Building-Applications-Blazor-applications-ebook/dp/B07WPQTT6H) - August 24, 2019 - An Introduction to Building Applications with Blazor: How to get started creating applications using this exciting easy to use Microsoft C# framework
* [Dockerizing ASP.NET Core and Blazor Applications on Mac](https://www.c-sharpcorner.com/ebooks/dockerizing-asp-net-core-and-blazor-applications-on-mac) - October 30, 2018 - Dockerizing ASP.NET Core and Blazor Applications on Mac.

## Courses
* [Blazor First Look on LinkedIn Learning](https://www.linkedin.com/learning/blazor-first-look) - Blazor First Look on LinkedIn Learning. [Source code](https://github.com/Dedac/Beam) ![GitHub stars](https://img.shields.io/github/stars/Dedac/Beam?style=flat-square&cacheSeconds=604800).
* [Free Blazor Training Course](https://www.devexpress.com/support/training/blazor/) - DevExpress Blazor free training course [Source code](https://github.com/DevExpress/blazor-training-samples) ![GitHub stars](https://img.shields.io/github/stars/DevExpress/blazor-training-samples?style=flat-square&cacheSeconds=604800).
  
## Community
* [Awesome Blazor on Twitter](https://twitter.com/awesomeblazor) - This repository's Twitter feed.
* [Gitter](https://gitter.im/aspnet/Blazor) - Blazor discussion on Gitter.
* [Learn Blazor](https://learn-blazor.com/) - Community documentation on Blazor.
* [LightSwitch Help Website](https://lightswitchhelpwebsite.com/Blog/tabid/61/tagid/66/Blazor.aspx) - Blogs and code samples primarily covering server-side Blazor (Razor Components).
* [Practical samples of Blazor](https://github.com/dodyg/practical-aspnetcore/tree/master/projects/blazor) - Practical samples of Blazor.
* [Practical samples of Blazor Server-Side](https://github.com/dodyg/practical-aspnetcore/tree/master/projects/blazor-ss) - Practical samples of Blazor Server-Side.
* [Stack Overflow](https://stackoverflow.com/questions/tagged/blazor) - Blazor questions feed on Stack Overflow.
* [Twitter](https://twitter.com/hashtag/blazor) - Hashtag on Twitter.
* [WebAssemblyMan](https://www.webassemblyman.com/) - Man page for Blazor and WebAssembly.

## Other Languages
* [Blaze of Code](https://blazeofcode.com/) - [Portuguese] Blog about Blazor.
* [Blazor.ru](https://blazor.ru/) - [Russian] Old official documentation website translated in russian.
* [DevApps.be's podcast #44](http://devapps.be/podcast/blazor-webassembly/) - [French] DevApps.be's podcast #44: "Blazor et WebAssembly vont-ils tuer JavaScript ?".
* [DevApps.be's podcast #47](http://devapps.be/podcast/47-typescript-uno-angular-docfx/) - [French] DevApps.be's podcast #47: "Actualités : TypeScript, Uno, Angular, DocFX, Database".
* [Modern web apps with Blazor](https://media.aspitalia.com/events/VS2019-Blazor.media) - [Italian] Video about Blazor.
* [Playlist - Programando en Blazor](https://www.youtube.com/playlist?list=PL0kIvpOlieSNdIPZbn-mO15YIjRHY2wI9) - [Spanish] Series of videos about Blazor.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Adrien Torris has waived all copyright and related or neighboring rights to this work.
