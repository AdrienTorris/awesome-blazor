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
More information on the [official Blazor website](https://blazor.net).

### Get started

To get started with Blazor, follow the instructions in the [Blazor Get Started](https://docs.microsoft.com/aspnet/core/blazor/get-started) documentation.

To open Blazor projects in Visual Studio, you must have [Visual Studio 2019 16.3](https://www.visualstudio.com/vs/) or later and the [.NET Core 3.0 SDK](https://dot.net/get-core3).

Note: the Blazor Visual Studio extension is no longer required since .NET Core 3.0 Preview 7. Uninstall the extension if you still have it installed.

## General
* [ASP.NET Blog's archives](https://devblogs.microsoft.com/aspnet/category/blazor/) - Archives of the ASP.NET blog about Blazor.
* [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/client) - Official website of Blazor, from Microsoft.
* [Blazor bites](https://chrissainty.com/blazor-bites/) - Blazor bites series by Chris Sainty.
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
* [BlazorBoilerplate](https://github.com/enkodellc/blazorboilerplate) - ![GitHub stars](https://img.shields.io/github/stars/enkodellc/blazorboilerplate?style=flat-square&cacheSeconds=604800) Real World Admin Dashboard / Starter kit with IdentityServer4 Material Design. [Demo](https://blazorboilerplate.com).
* [BlazorWithIdentity](https://github.com/stavroskasidis/BlazorWithIdentity) - ![GitHub stars](https://img.shields.io/github/stars/stavroskasidis/BlazorWithIdentity?style=flat-square&cacheSeconds=604800) A sample project showcasing a Blazor app using EF Core with Identity authentication.
* [Blazor.JWTTest](https://github.com/shawty/blazor.jwttest) - ![GitHub stars](https://img.shields.io/github/stars/shawty/blazor.jwttest?style=flat-square&cacheSeconds=604800) JWT authentication for a Blazor hosted (Client/Server-side) app with API and Authentication.
* [Blazor.OpenId](https://github.com/jbomhold3/Blazor.Openid) - Easy authentication and client refresh using OpenId.
* [BlazorAuthenticationSample](https://github.com/christiansparre/BlazorAuthenticationSample) - A sample showing some of the ASP.NET Core Blazor authentication features (also some testing...).
### CMS
* [BlogCore](https://github.com/thangchung/blog-core) - ![GitHub stars](https://img.shields.io/github/stars/thangchung/blog-core?style=flat-square&cacheSeconds=604800) Modern CMS on Domain-driven Design and Clean Architecture patterns.
* [WordDaze](https://github.com/chrissainty/worddaze) - ![GitHub stars](https://img.shields.io/github/stars/chrissainty/worddaze?style=flat-square&cacheSeconds=604800) Blogging application written using Blazor with a WebAPI backend.
* [RapidCMS](https://github.com/ThomasBleijendaal/RapidCMS) - A code-first, extensible Blazor app that generates a CMS for your own database.
### Games
* [AsteroidsWasm](https://github.com/aesalazar/AsteroidsWasm) - ![GitHub stars](https://img.shields.io/github/stars/aesalazar/AsteroidsWasm?style=flat-square&cacheSeconds=604800) A mixed bag of C# projects to see if a single .NET Standard base can run across all common platforms include WebAssembly. [Demo](https://aesalazar.github.io/AsteroidsWasm/).
* [BlazorQuiz](https://github.com/Amine-Smahi/BlazorQuiz) - ![GitHub stars](https://img.shields.io/github/stars/Amine-Smahi/BlazorQuiz?style=flat-square&cacheSeconds=604800) Simple quiz using Blazor.NET and WebAssembly.
* [Blagario](https://github.com/ctrl-alt-d/Blagario) - ![GitHub stars](https://img.shields.io/github/stars/ctrl-alt-d/Blagario?style=flat-square&cacheSeconds=604800) Experimental lab to test Blazor server side as multiplayer game engine.
* [BlazorChess](https://github.com/Lupusa87/BlazorChess) - Chess engine implemented with Blazor. [Demo](https://lupblazorchess.z20.web.core.windows.net/).
* [Tzaar](https://github.com/paularundel/tzaar) - Implementation of the board game Tzaar with Blazor and SignalR. [Demo](https://tzaar.azurewebsites.net/).
* [BlazorGameSnake](https://github.com/Lupusa87/BlazorGameSnake) - 2D game snake with customizations, path finding algorithm, and sound effects using SVG. [Demo](https://lupblazorsnake.z20.web.core.windows.net/).
* [Blazor20Questions](https://github.com/MetalMichael/blazor-20-questions) - Client/Server game using Websockets (SignalR) & MongoDB API, with Docker (docker-compose).
* [BlazorDestinationGame](https://github.com/SharePointSean/BlazorDestinationGame) - Quiz about places in the world. [Demo](https://blazordestinationgame.azurewebsites.net/).
* [BlazorDice](https://github.com/shahedc/BlazorDemos/tree/master/BlazorDice) - Roll the dice.
* [BlazorPong](https://github.com/MACEL94/BlazorPong) - Pong in Blazor server side using SignalR Core. [Demo](https://blazorpong-dev-as.azurewebsites.net).
* [BlazorTictactoe](https://github.com/kodebot/BlazorTicTacToe) - Tic-tac-toe in Blazor WebAssembly. [Demo](https://tic-tac-toe.kodebot.com/).
* [DiabloBlazor](https://github.com/n-stefan/diabloblazor) - Blazor port of DiabloWeb, making it a double WebAssembly app: a WebAssembly (C#) SPA hosting a WebAssembly (C++) game. [Demo](https://n-stefan.github.io/diabloblazor).
### Machine Learning
* [Scalable sentiment analysis](https://github.com/dotnet/machinelearning-samples/tree/master/samples/csharp/end-to-end-apps/ScalableSentimentAnalysisBlazorWebApp) - ![GitHub stars](https://img.shields.io/github/stars/dotnet/machinelearning-samples?style=flat-square&cacheSeconds=604800) A sample ables to make sentiment analysis prediction/detection of what the user is writing in a very UI interactive app (Blazor based) in the client side and running an ML.NET model (Sentiment analysis based on binary-classification) in the server side.
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
* [BlazeDown](https://github.com/EdCharbeneau/BlazeDown) - ![GitHub stars](https://img.shields.io/github/stars/EdCharbeneau/BlazeDown?style=flat-square&cacheSeconds=604800) BlazeDown, online Markdown editor. [Demo](https://edcharbeneau.com/BlazeDown/).
* [BlazorChatSample](https://github.com/conficient/blazorchatsample) - ![GitHub stars](https://img.shields.io/github/stars/conficient/blazorchatsample?style=flat-square&cacheSeconds=604800) Blazor chat demo using SignalR JS client with interop.
* [Blazor.Toaster](https://github.com/sotsera/sotsera.blazor.toaster) - ![GitHub stars](https://img.shields.io/github/stars/sotsera/sotsera.blazor.toaster?style=flat-square&cacheSeconds=604800) A Blazor port of Toastr.js.
* [Money](https://github.com/maraf/Money) - ![GitHub stars](https://img.shields.io/github/stars/maraf/Money?style=flat-square&cacheSeconds=604800) A money manager implemented using CQRS+ES. [Demo](https://app.money.neptuo.com/).
* [Tour of Heroes](https://github.com/lohithgn/blazor-tour-of-heroes) - ![GitHub stars](https://img.shields.io/github/stars/lohithgn/blazor-tour-of-heroes?style=flat-square&cacheSeconds=604800) Blazor implementation of Angular Tour of Heroes.
* [Runny](https://github.com/Suchiman/Runny) - ![GitHub stars](https://img.shields.io/github/stars/Suchiman/Runny?style=flat-square&cacheSeconds=604800) Prototype of running roslyn in the browser via Blazor. [Demo](https://runny.azurewebsites.net/).
* [Gitter](https://github.com/Blazored/Gitter) - ![GitHub stars](https://img.shields.io/github/stars/Blazored/Gitter?style=flat-square&cacheSeconds=604800) A Blazor Gitter client.
* [NethereumBlazor](https://github.com/Nethereum/NethereumBlazor) - ![GitHub stars](https://img.shields.io/github/stars/Nethereum/NethereumBlazor?style=flat-square&cacheSeconds=604800) Ethereum blockchain explorer and simple wallet.
* [BlazorGraphExample](https://github.com/jburman/BlazorGraphExample) - ![GitHub stars](https://img.shields.io/github/stars/jburman/BlazorGraphExample?style=flat-square&cacheSeconds=604800) Example application for connecting to Graph API from Blazor.
* [BlazingPizza (server side)](https://github.com/ADefWebserver/BlazingPizza) - ![GitHub stars](https://img.shields.io/github/stars/ADefWebserver/BlazingPizza?style=flat-square&cacheSeconds=604800) A server side Blazor version of the Blazing Pizza project from the [Blazor - app building workshop](https://github.com/dotnet-presentations/blazor-workshop/) ![GitHub stars](https://img.shields.io/github/stars/dotnet-presentations/blazor-workshop?style=flat-square&cacheSeconds=604800).
* [Try F# on WebAssembly](https://github.com/fsbolero/TryFSharpOnWasm) - ![GitHub stars](https://img.shields.io/github/stars/fsbolero/TryFSharpOnWasm?style=flat-square&cacheSeconds=604800) The F# compiler running in WebAssembly with Bolero.
* [BlazorDynamicList](https://github.com/conficient/BlazorDynamicList) - ![GitHub stars](https://img.shields.io/github/stars/conficient/BlazorDynamicList?style=flat-square&cacheSeconds=604800) Dynamic component binding for a generic list. [Demo](https://blazordynamiclist.azurewebsites.net/).
* [BlazorBinding](https://github.com/SQL-MisterMagoo/BlazorBinding) - ![GitHub stars](https://img.shields.io/github/stars/SQL-MisterMagoo/BlazorBinding?style=flat-square&cacheSeconds=604800) Sample Blazor App demonstrating various data binding scenarios.
* [StarshipTraveler](https://github.com/rstropek/StarshipTraveler) - ![GitHub stars](https://img.shields.io/github/stars/rstropek/StarshipTraveler?style=flat-square&cacheSeconds=604800) A starship traveler demo app built with Blazor for the DevOne 2019 conference.
* [BlazorServerTree](https://github.com/ctrl-alt-d/BlazorServerTree) - ![GitHub stars](https://img.shields.io/github/stars/ctrl-alt-d/BlazorServerTree?style=flat-square&cacheSeconds=604800) A simple Server-Side Blazor sample app to deal with hierarchical data.
* [Blazor Weather](https://github.com/danroth27/BlazorWeather) - ![GitHub stars](https://img.shields.io/github/stars/danroth27/BlazorWeather?style=flat-square&cacheSeconds=604800) A Blazor Weather sample app that shows the current weather for your current location and a collection of pinned locations. Demonstrated at .NET Conf 2019 by Daniel Roth. [Demo](https://aka.ms/blazorweather).
* [Blazor + Sitecore](https://github.com/GoranHalvarsson/SitecoreBlazor) - ![GitHub stars](https://img.shields.io/github/stars/GoranHalvarsson/SitecoreBlazor?style=flat-square&cacheSeconds=604800) Example of dynamic pages and routes with SiteCore and [Helix](https://helix.sitecore.net/). 
* [WebSocketPage](https://github.com/Lupusa87/BlazorWebSocketHelper) - ![GitHub stars](https://img.shields.io/github/stars/Lupusa87/BlazorWebSocketHelper?style=flat-square&cacheSeconds=604800) Web Socket in Blazor. [demo](https://lupblazordemos.z13.web.core.windows.net/WebSocketPage).
* [Blazor Survey](https://github.com/nutshellit/Blazor-Survey) - ![GitHub stars](https://img.shields.io/github/stars/nutshellit/Blazor-Survey?style=flat-square&cacheSeconds=604800) A hybrid F#/C# Blazor sample app to kick the tyres of
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
* [Blazor FIRE Calculators](https://github.com/bradwellsb/blazor-fire-calculators) - Client-side financial calculators built using Blazor WebAssembly. Demonstrates offline Progressive Web App (PWA) functionality. [Demo](https://fire.wellsb.com/).
* [BlazorFormsValidation](https://github.com/Dallas411/BlazorFormsValidation) - Blazor form validation sample.
* [BlazorPaint](https://github.com/Lupusa87/BlazorPaint) - A paint sample with Blazor ([demo](https://lupblazorpaint.z20.web.core.windows.net/)).
* [BlazorPages](https://github.com/fernandreu/blazor-pages) - A sample client-side Blazor app showcasing automatic deployment to GitHub Pages via Azure Pipelines.
* [BlazorServiceWorker](https://github.com/roboriaan/BlazorServiceWorker) - A client-side Blazor template with service worker caching.
* [Blazor Summernote](https://github.com/shawty/blazor.summernote) - Wrapper for the new MS Blazor framework, allowing the use of the Summernote WYSIWYG editor in a form.
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
* [Gjallarhorn](https://github.com/haavamoa/Gjallarhorn) - Compare packages on different NuGet-sources. Demonstrating Client-Side Blazor MVVM-style. 
* [C# Regex Tester online](https://github.com/lsvhome/regex-tester) - Online tool for verify .Net regex syntax. ([Demo](https://lsvhome.github.io/regex-tester/)).
* [CssBuilder](https://www.nuget.org/packages/BlazorComponentUtilities/) &ndash; A clean code approach to conditional CSS classes for Razor components in Blazor.
* [EncFS over Google Drive](https://encfs-gdrive.github.io) - Online tool written in Blazor for encrypt/decrypt files in Google Drive.
* [BlazorPoint](https://github.com/smjltd/BlazorPoint) - Sample App to help you get started with hosting Blazor on SharePoint Pages, Completely Client Side. 
* [BlazorGrpc](https://github.com/razfriman/BlazorGrpc) - Sample project that demonstrates how you can use the power of Blazor, ASP.NET Core, and gRPC to create a web application which can communicate with a backend that uses gRPC.
* [Return](https://github.com/Sebazzz/Return) - Realtime retrospective tool built in ASP.NET Core and Blazor.

## Tutorials
* [Blazor workshop](https://github.com/dotnet-presentations/blazor-workshop/) - ![GitHub stars](https://img.shields.io/github/stars/dotnet-presentations/blazor-workshop?style=flat-square&cacheSeconds=604800) Blazor app building workshop by [.NET Foundation](https://www.dotnetfoundation.org/), Blazzing Pizza.
* [Creating A Step-By-Step End-To-End Database Server-Side Blazor Application](http://blazorhelpwebsite.com/Blog/tabid/61/EntryId/4318/Creating-A-Step-By-Step-End-To-End-Database-Server-Side-Blazor-Application.aspx) - October 06, 2019 - Creating A Step-By-Step End-To-End Database Server-Side Blazor Application. [Video here](https://www.youtube.com/watch?v=dSW23gkQLP4&feature=youtu.be).
* [Tour of Heroes](https://github.com/rstropek/BlazorHeroTutorial) - September, 2019 - Angular's Heroes tutorial implemented using Blazor.
* [ASP.NET Core and Blazor Code Venture: Configuring Azure AD Authentication](https://www.codeproject.com/Articles/5164004/ASP-NET-Core-and-Blazor-Code-Venture-Configuring-A) - August 5, 2019 - ASP.NET Core and Blazor Code Venture: Configuring Azure AD Authentication, on Coe Project.
* [Realtime Blazor Tic-Tac-Toe Game - Bot Vs Multiplayer Using SignalR](https://www.c-sharpcorner.com/article/realtime-blazor-tic-tac-toe-game-bot-vs-multiplayer-using-signalr/) - July 17, 2019 - How to create a realtime bot vs. multiplayer tic-tac-toe game in Blazor using SignalR.
* [TSP with GeneticSharp and Blazor](http://diegogiacomelli.com.br/tsp-with-geneticsharp-and-blazor/) - July 10, 2019 - Using a Blazor client-side app and [GeneticSharp](https://github.com/giacomelli/GeneticSharp) ![GitHub stars](https://img.shields.io/github/stars/giacomelli/GeneticSharp?style=flat-square&cacheSeconds=604800) to solve the TSP (Travelling salesman problem).
* [Blazor client-side app with CRUD operations against a Web API endpoint](http://blog.medhat.ca/2019/05/blazor-app-with-crud-operations-from.html) - May 31, 2019 - Blazor client-side app with CRUD operations against a Web API endpoint. [Source code](https://github.com/medhatelmasry/BlazingSchool) ![GitHub stars](https://img.shields.io/github/stars/medhatelmasry/BlazingSchool?style=flat-square&cacheSeconds=604800). [Video](https://www.youtube.com/watch?v=wkSR3eo4Tek).
* [Archives](https://github.com/AdrienTorris/awesome-blazor/tree/master/Archives) - [2019](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2019.md#tutorials), [2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#tutorials).

## Libraries & Extensions
### Components
*Reusable components like buttons, inputs, grids and more.*
* [MatBlazor](https://github.com/SamProf/MatBlazor) - ![GitHub stars](https://img.shields.io/github/stars/SamProf/MatBlazor?style=flat-square&cacheSeconds=604800) Material Design components for Blazor. ([Demo](https://www.matblazor.com/)).
* [Blazorise](https://github.com/stsrki/Blazorise) - ![GitHub stars](https://img.shields.io/github/stars/stsrki/Blazorise?style=flat-square&cacheSeconds=604800) Components for Blazor with support for Bootstrap, Bulma and Material CSS. ([Demo](https://bootstrapdemo.blazorise.com/)).
* [BlazorStrap](https://github.com/chanan/BlazorStrap) - ![GitHub stars](https://img.shields.io/github/stars/chanan/BlazorStrap?style=flat-square&cacheSeconds=604800) Bootstrap 4 components for Blazor ([Demo](https://chanan.github.io/BlazorStrap/)).
* [BlazorMaterial](https://github.com/BlazorExtensions/BlazorMaterial) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/BlazorMaterial?style=flat-square&cacheSeconds=604800) Blazor components implementing Google's Material components for web.
* [Canvas](https://github.com/BlazorExtensions/Canvas) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/Canvas?style=flat-square&cacheSeconds=604800) HTML5 Canvas API implementation for Microsoft Blazor.
* [BlazorContextMenu](https://github.com/stavroskasidis/BlazorContextMenu) - ![GitHub stars](https://img.shields.io/github/stars/stavroskasidis/BlazorContextMenu?style=flat-square&cacheSeconds=604800) A context menu component for Blazor ([Demo](https://blazor-context-menu-demo.azurewebsites.net/)).
* [Blazor.FlexGrid](https://github.com/Mewriick/Blazor.FlexGrid) - ![GitHub stars](https://img.shields.io/github/stars/Mewriick/Blazor.FlexGrid?style=flat-square&cacheSeconds=604800) GridView component for Blazor.
* [DevExpress Blazor UI Components](https://github.com/DevExpress/RazorComponents) - ![GitHub stars](https://img.shields.io/github/stars/DevExpress/RazorComponents?style=flat-square&cacheSeconds=604800) UI components including Data Grid, Pivot Grid, and several data editors.
* [Blazored.Toast](https://github.com/Blazored/Toast) - ![GitHub stars](https://img.shields.io/github/stars/Blazored/Toast?style=flat-square&cacheSeconds=604800) A JavaScript free toast library for Blazor and Razor Component applications.
* [Blazored.Modal](https://github.com/Blazored/Modal) - ![GitHub stars](https://img.shields.io/github/stars/Blazored/Modal?style=flat-square&cacheSeconds=604800) A JavaScript free modal library for Blazor and Razor Components applications.
* [Syncfusion Blazor UI Components](https://github.com/syncfusion/ej2-aspnet-core-blazor-samples) - ![GitHub stars](https://img.shields.io/github/stars/syncfusion/ej2-aspnet-core-blazor-samples?style=flat-square&cacheSeconds=604800) Robust UI components including [Data Grid](https://ej2.syncfusion.com/aspnet-core-razor-components/Grid/DefaultFunctionalities), [Charts](https://ej2.syncfusion.com/aspnet-core-razor-components/Charts/polar), [Scheduler](https://ej2.syncfusion.com/aspnet-core-razor-components/Schedule/TimelineResourceGroup), [Inputs](https://ej2.syncfusion.com/aspnet-core-razor-components/TextBox/DefaultFunctionalities) and several [Editor](https://ej2.syncfusion.com/aspnet-core-razor-components/RichTextEditor/DefaultFunctionalities) components.
* [Sotsera.Blazor.Toaster](https://github.com/sotsera/sotsera.blazor.toaster) - ![GitHub stars](https://img.shields.io/github/stars/sotsera/sotsera.blazor.toaster?style=flat-square&cacheSeconds=604800) A Blazor port of Toastr.js. [Demo](https://blazor-toaster.sotsera.com/).
* [BlazorComponents](https://github.com/muqeet-khan/BlazorComponents) - ![GitHub stars](https://img.shields.io/github/stars/muqeet-khan/BlazorComponents?style=flat-square&cacheSeconds=604800) Reusable components for Blazor. Starting with ChartJS interop.
* [Radzen.Blazor](https://github.com/akorchev/razor.radzen.com) - ![GitHub stars](https://img.shields.io/github/stars/akorchev/razor.radzen.com?style=flat-square&cacheSeconds=604800) Native UI components for Blazor. DataGrid, DataList, Tabs, Dialog and more. ([Demo](https://razor.radzen.com/)).
* [Blazored.Typeahead](https://github.com/Blazored/Typeahead) - ![GitHub stars](https://img.shields.io/github/stars/Blazored/Typeahead?style=flat-square&cacheSeconds=604800) Auto-complete textbox with local and remote data source, for both Client-side and Server-Side Blazor.
* [Grid.Blazor](https://github.com/gustavnavar/Grid.Blazor) - ![GitHub stars](https://img.shields.io/github/stars/gustavnavar/Grid.Blazor?style=flat-square&cacheSeconds=604800) Grid component for Blazor and ASP.NET MVC, supporting filtering, sorting, searching, paging, subgrids and others ([Demo](http://gridblazor.azurewebsites.net)).
* [Blazor LoadingBar](https://github.com/jsakamoto/Toolbelt.Blazor.LoadingBar) - ![GitHub stars](https://img.shields.io/github/stars/jsakamoto/Toolbelt.Blazor.LoadingBar?style=flat-square&cacheSeconds=604800) Loading bar UI for Client-Side Blazor application.
* [BlazorStyled](https://github.com/chanan/BlazorStyled) - ![GitHub stars](https://img.shields.io/github/stars/chanan/BlazorStyled?style=flat-square&cacheSeconds=604800) CSS in Blazor Components ([Demo](https://chanan.github.io/BlazorStyled)).
* [BlazorGrid](https://github.com/AnkitSharma-007/BlazorGrid) - ![GitHub stars](https://img.shields.io/github/stars/AnkitSharma-007/BlazorGrid?style=flat-square&cacheSeconds=604800) This is a reusable grid component for Blazor which also supports client side pagination.
* [Blazored.Menu](https://github.com/Blazored/Menu) - ![GitHub stars](https://img.shields.io/github/stars/Blazored/Menu?style=flat-square&cacheSeconds=604800) A JavaScript free menu library for Blazor and Razor Components applications.
* [Blazor-Charts](https://github.com/Misfits-Rebels-Outcasts/Blazor-Charts) - ![GitHub stars](https://img.shields.io/github/stars/Misfits-Rebels-Outcasts/Blazor-Charts?style=flat-square&cacheSeconds=604800) SVG charts for Blazor.
* [NodaTimePicker](https://github.com/nheath99/NodaTimePicker) - ![GitHub stars](https://img.shields.io/github/stars/nheath99/NodaTimePicker?style=flat-square&cacheSeconds=604800) A Date/Time picker component library for Blazor using NodaTime. [Demo](https://nodatimepicker.z13.web.core.windows.net/).
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
* [Blazor.LoadingIndicator](https://github.com/h3x4d3c1m4l/Blazor.LoadingIndicator) - Simple to use loading indicator helper library.
* [BlazorDateRangePicker](https://github.com/jdtcn/BlazorDateRangePicker) - A date range picker component library for Blazor. [Demo](https://BlazorDateRangePicker.azurewebsites.net/).
* [BlazorTypography](https://github.com/chanan/BlazorTypography) - A powerful toolkit for building websites with beautiful design ([Demo](https://chanan.github.io/BlazorTypography/)).
* [BlazorGoogleMaps](https://github.com/rungwiroon/BlazorGoogleMaps) - Blazor interop for GoogleMap library.
* [Razor.SweetAlert2](https://github.com/Basaingeal/Razor.SweetAlert2) - Blazor component implementing the popular SweetAlert2 JavaScript Library. 
* [Blazor.SpinKit](https://github.com/faso/Faso.Blazor.SpinKit) - Blazor components for [SpinKit](https://tobiasahlin.com/spinkit/) spinners.
* [ChartJs.Blazor](https://github.com/mariusmuntean/ChartJs.Blazor) - ![GitHub stars](https://img.shields.io/github/stars/mariusmuntean/ChartJs.Blazor?style=flat-square&cacheSeconds=604800) ![Status](https://img.shields.io/static/v1?label=status&message=Not%20maintained%20anymore&color=lightgrey) Blazor Component that wraps ChartJS.
* [ChartJSBlazor](https://github.com/Joelius300/ChartJSBlazor) - ![GitHub stars](https://img.shields.io/github/stars/Joelius300/ChartJSBlazor?style=flat-square&cacheSeconds=604800) ![Status](https://img.shields.io/static/v1?label=status&message=archived&color=lightgrey) Blazor Component that wraps ChartJS. (New fork of [ChartJs.Blazor](https://github.com/mariusmuntean/ChartJs.Blazor) that is maintained).

### Tools & Utilities
*Libraries and extensions for state management, cookies, local storage and other specific tools.*
* [Blazor-Redux](https://github.com/torhovland/blazor-redux) - ![GitHub stars](https://img.shields.io/github/stars/torhovland/blazor-redux?style=flat-square&cacheSeconds=604800) Connecting a Redux state store with Blazor.
* [Blazor-Fluxor](https://github.com/mrpmorris/blazor-fluxor) - ![GitHub stars](https://img.shields.io/github/stars/mrpmorris/blazor-fluxor?style=flat-square&cacheSeconds=604800) A low-boilerplate Flux/Redux state library for Blazor.
* [SignalR](https://github.com/BlazorExtensions/SignalR) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/SignalR?style=flat-square&cacheSeconds=604800) SignalR Core implementation for Blazor. It uses the JavaScript client.
* [Blazor-State](https://github.com/TimeWarpEngineering/blazor-state) - ![GitHub stars](https://img.shields.io/github/stars/TimeWarpEngineering/blazor-state?style=flat-square&cacheSeconds=604800) Manage client side state in Blazor using MediatR pipeline.
* [Storage](https://github.com/BlazorExtensions/Storage) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/Storage?style=flat-square&cacheSeconds=604800) HTML5 Storage API implementation for Microsoft Blazor.
* [Logging](https://github.com/BlazorExtensions/Logging) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/Logging?style=flat-square&cacheSeconds=604800) Microsoft Extension Logging implementation for Blazor.
* [Blazored.LocalStorage](https://github.com/Blazored/LocalStorage) - ![GitHub stars](https://img.shields.io/github/stars/Blazored/LocalStorage?style=flat-square&cacheSeconds=604800) A library to provide access to local storage in Blazor applications.
* [BlazorStorage](https://github.com/cloudcrate/BlazorStorage) - ![GitHub stars](https://img.shields.io/github/stars/cloudcrate/BlazorStorage?style=flat-square&cacheSeconds=604800) Local and session storage support for Blazor.
* [BlazorDB](https://github.com/chanan/BlazorDB) - ![GitHub stars](https://img.shields.io/github/stars/chanan/BlazorDB?style=flat-square&cacheSeconds=604800) In-memory, persisted to local storage, database for Blazor.
* [BlazorSignalR](https://github.com/csnewman/BlazorSignalR) - ![GitHub stars](https://img.shields.io/github/stars/csnewman/BlazorSignalR?style=flat-square&cacheSeconds=604800) SignalR Core .NET client library for Blazor. It uses the C# client.
* [Blazor.Auth0](https://github.com/Pegazux/Blazor.Auth0) - ![GitHub stars](https://img.shields.io/github/stars/Pegazux/Blazor.Auth0?style=flat-square&cacheSeconds=604800) The library for using [Auth0](https://auth0.com/) in Blazor applications.
* [Notifications](https://github.com/BlazorExtensions/Notifications) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/Notifications?style=flat-square&cacheSeconds=604800) HTML5 Notifications API implementation for Microsoft Blazor.
* [Blazor.Polyfill](https://github.com/Daddoon/Blazor.Polyfill) - ![GitHub stars](https://img.shields.io/github/stars/Daddoon/Blazor.Polyfill?style=flat-square&cacheSeconds=604800) Polyfills for Blazor (for Internet Explorer 11 support and some other browsers).
* [Blazor I18n/Localization Text](https://github.com/jsakamoto/Toolbelt.Blazor.I18nText) - ![GitHub stars](https://img.shields.io/github/stars/jsakamoto/Toolbelt.Blazor.I18nText?style=flat-square&cacheSeconds=604800) Localizing contents text in Blazor ([Demo](https://jsakamoto.github.io/Toolbelt.Blazor.I18nText/)).
* [CssBuilder](https://github.com/EdCharbeneau/CssBuilder) - ![GitHub stars](https://img.shields.io/github/stars/EdCharbeneau/CssBuilder?style=flat-square&cacheSeconds=604800) CssBuilder is a Builder pattern for CSS classes to be used with Razor Components.
* [Blazor.Payments](https://github.com/philipblaquiere/Blazor.Payments) - ![GitHub stars](https://img.shields.io/github/stars/philipblaquiere/Blazor.Payments?style=flat-square&cacheSeconds=604800) Blazor Web Agent port of the Web Payment API standard developed by W3C .
* [Blazored.Localisation](https://github.com/Blazored/Localisation) - ![GitHub stars](https://img.shields.io/github/stars/Blazored/Localisation?style=flat-square&cacheSeconds=604800) A library to provide localisation in client-side Blazor applications.
* [Blazor.Geolocation](https://github.com/AspNetMonsters/Blazor.Geolocation) - ![GitHub stars](https://img.shields.io/github/stars/AspNetMonsters/Blazor.Geolocation?style=flat-square&cacheSeconds=604800) Blazor interop for browser Geolocation APIs.
* [EmbeddedBlazorContent](https://github.com/SamProf/EmbeddedBlazorContent) - ![GitHub stars](https://img.shields.io/github/stars/SamProf/EmbeddedBlazorContent?style=flat-square&cacheSeconds=604800) Library to load embedded content files (js and css) from Blazor libraries in server-side Blazor mode.
* [Blazor Time Zone Kit](https://github.com/jsakamoto/Toolbelt.Blazor.TimeZoneKit) - ![GitHub stars](https://img.shields.io/github/stars/jsakamoto/Toolbelt.Blazor.TimeZoneKit?style=flat-square&cacheSeconds=604800) A library to provide system time zones and local time zone initialization in Blazor apps.
* [Blazor SVG Helper](https://github.com/Lupusa87/BlazorSvgHelper) - ![GitHub stars](https://img.shields.io/github/stars/Lupusa87/BlazorSvgHelper?style=flat-square&cacheSeconds=604800) Create SVG elements with children (circle, rectangle, image, text, and others) and render with RenderTreeBuilder.
* [Razor components testing library](https://github.com/egil/razor-components-testing-library) - A library for testing Razor Components that renders the components as HTML and compares the result to an expected result, using the XMLDiff library and Shouldly for writing out error messages. 
* [Blazor Analytics](https://github.com/isc30/blazor-analytics) - Blazor extensions for Analytics.
* [BlazorPrettyCode](https://github.com/chanan/BlazorPrettyCode) - Blazor Code Component for documentation sites. [Demo](https://chanan.github.io/BlazorPrettyCode/).
* [Blazor.EventAggregator](https://github.com/mikoskinen/Blazor.EventAggregator) - Lightweight Event Aggregator for Blazor (Razor Components).
* [Blazor Gamepad](https://github.com/jsakamoto/Toolbelt.Blazor.Gamepad) - Provides gamepad API access for Blazor.
* [Blazor Hotkeys](https://github.com/jsakamoto/Toolbelt.Blazor.Hotkeys) - A library to provide configuration-centric keyboard shortcuts for Blazor.
* [BlazorRealm](https://dworthen.github.io/BlazorRealm/docs/quickstart.html) - Redux state management for Blazor.
* [Blazor.LocalFiles](https://github.com/jburman/W8lessLabs.Blazor.LocalFiles) - Open files in your browser and load into Blazor.
* [Blazor.Sensors](https://github.com/AspNetMonsters/Blazor.Sensors) - Blazor interop for browser sensor APIs.
* [Rudder](https://github.com/kjeske/rudder) - Efficient state container for Blazor with concepts similar to the ones in redux, including reducers and sagas.
* [BlazorIntersectionObserver](https://github.com/ljbc1994/BlazorIntersectionObserver) - A Blazor wrapper for the Intersection Observer API.
* [Blazor.SpeechSynthesis](https://github.com/jsakamoto/Toolbelt.Blazor.SpeechSynthesis) - A library to provide Speech Synthesis API access for Blazor.
* [Blazor BarCode](https://barcoderesource.com/blazorbarcode.shtml) &ndash; A barcode library for Blazor using barcode fonts.
* [BlazorState.Redux](https://github.com/BerserkerDotNet/BlazorState.Redux) - Develop Blazor apps with Redux.
* [BlazorLeaflet](https://github.com/Mehigh17/BlazorLeaflet) - BlazorLeaflet is a wrapper offering easy-to-use Blazor components that expose the Leaflet API in C#.
### Others
* [Blazor Extensions Home](https://github.com/BlazorExtensions/Home) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/Home?style=flat-square&cacheSeconds=604800) Home for Blazor Extensions.
* [Bolero](https://github.com/fsbolero/Bolero) - ![GitHub stars](https://img.shields.io/github/stars/fsbolero/Bolero?style=flat-square&cacheSeconds=604800) Blazor for F# with hot reloaded templates, type-safe endpoints and routing, remoting, and much more.
* [BlazorMobile](https://github.com/Daddoon/BlazorMobile) - ![GitHub stars](https://img.shields.io/github/stars/Daddoon/BlazorMobile?style=flat-square&cacheSeconds=604800) Launch Blazor as a mobile application on iOS, Android & UWP.
* [NObservable](https://github.com/kekekeks/NObservable) - ![GitHub stars](https://img.shields.io/github/stars/kekekeks/NObservable?style=flat-square&cacheSeconds=604800) MobX-like observables and component instrumentation.
* [BlazorOfficeUIFabric](https://github.com/BlazorExtensions/BlazorOfficeUIFabric) - ![GitHub stars](https://img.shields.io/github/stars/BlazorExtensions/BlazorOfficeUIFabric?style=flat-square&cacheSeconds=604800) Microsoft Office Fabric UI port for Blazor.
* [Blazor-Dashboard](https://github.com/Misfits-Rebels-Outcasts/Blazor-Dashboard) - ![GitHub stars](https://img.shields.io/github/stars/Misfits-Rebels-Outcasts/Blazor-Dashboard?style=flat-square&cacheSeconds=604800) Admin Dashboard Template Theme for Blazor.
* [BlazorEmbedLibrary](https://github.com/SQL-MisterMagoo/BlazorEmbedLibrary) - ![GitHub stars](https://img.shields.io/github/stars/SQL-MisterMagoo/BlazorEmbedLibrary?style=flat-square&cacheSeconds=604800) Provides Blazor-style embedded static content files for Razor Components projects.
* [WebSocketHelper](https://github.com/Lupusa87/BlazorWebSocketHelper) - ![GitHub stars](https://img.shields.io/github/stars/Lupusa87/BlazorWebSocketHelper?style=flat-square&cacheSeconds=604800) Helper for Web Socket in Blazor.
* [Bionic](https://bionicframework.github.io/Documentation/) - An Ionic CLI clone for Blazor projects.
* [BlazorFabric](https://github.com/limefrogyank/BlazorFabric) - Blazor port of Microsoft UI Fabric with fluent design. ([Demo](https://blazorfabric.azurewebsites.net/)).
* [BlazorFileSaver](https://github.com/IvanJosipovic/BlazorFileSaver) - Blazor Component wrapper for FileSaver.js. 
* [Blazor.DynamicJavascriptRuntime.Evaluator](https://github.com/jameschch/Blazor.DynamicJavascriptRuntime.Evaluator) - Execute dynamic object expressions as Javascript in Blazor client-side apps.
* [Blazor.AdaptiveCards](https://github.com/mikoskinen/Blazor.AdaptiveCards) - Adaptive Cards for Blazor. [Documentation](https://adaptivecardsblazor.com/).

## Videos
* [OceanNumericInput Component](https://www.youtube.com/watch?v=HHPcjEeSiSc) - October 19, 2019 - Overview about the OceanNumericInput Component usage and why it's needed in Blazor line of business applications. [OceanNumericInput Component source code](https://github.com/OceanLibrary/Ocean/blob/master/Source/Ocean.Blazor/OceanNumericInput.cs). [NuGet package](https://www.nuget.org/packages?q=OCEANWARE).
* [Episode 582: Jeremy Likness on Blazor](https://www.youtube.com/watch?v=A_zhrjSHSpE) - October 17, 2019 - Technology and Friends, Episode 582: Jeremy Likness on Blazor. Blazor is a framework for building full-stack web apps in the browser using C#. Jeremy Likness describes how it works and how to use it.
* [Blazor StateHasChanged: Responsive and Adaptive web rendering](https://www.twitch.tv/videos/493138351) - October 11, 2019 - Responsive and Adaptive web rendering.
* [All Linux and .NET development - Let's build a Blazor-based Follower Train widget](https://www.twitch.tv/videos/491014980) - October 07, 2019 - All Linux and .NET development - Let's build a Blazor-based Follower Train widget.
* [All Linux and .NET development - Let's build a Blazor-based Follower Train widget](https://www.twitch.tv/videos/490078631) - October 05, 2019 - All Linux and .NET development - Let's build a Blazor-based Follower Train widget.
* [Blazor StateHasChanged: Community round up & BlazePort](https://www.twitch.tv/videos/490114563) - October 04, 2019 - Blazor StateHasChanged: Community round up & BlazePort. [Source Code](https://github.com/EdCharbeneau/BlazePort) ![GitHub stars](https://img.shields.io/github/stars/EdCharbeneau/BlazePort?style=flat-square&cacheSeconds=604800).
* [Techorama NL 2019: Web Development Revolution with WebAssembly and ASP.NET Blazor](https://www.youtube.com/watch?v=Y4Zu6w_4LN4) - October 01, 2019 - Techorama NL 2019: Web Development Revolution with WebAssembly and ASP.NET Blazor.
* [The Future of Blazor on the Client](https://channel9.msdn.com/Events/dotnetConf/NET-Conf-2019/B202) - September 25, 2019 - The Future of Blazor on the Client, by Daniel Roth on Channel 9.
* [Building Full-stack C# Web Apps with Blazor in .NET Core 3.0](https://channel9.msdn.com/Events/dotnetConf/NET-Conf-2019/B106) - September 24, 2019 - Session of the .NET Conf 2019, Building Full-stack C# Web Apps with Blazor in .NET Core 3.0, by Daniel Roth.
* [Blazor and Azure Functions for Serverless Websites](https://www.youtube.com/watch?v=noG3rxt38VI) - September 24, 2019 - Blazor and Azure Functions for Serverless Websites, from the .NET Conf 2019.
* [Blazor, HTML, CSS, JavaScript InterOp, .NET Core 3, Chat and Stuff](https://www.twitch.tv/videos/483511319) - September 20, 2019 - Blazor, HTML, CSS, JavaScript InterOp, .NET Core 3, Chat and Stuff
* [Talking about Blazor with ASP.NET Web Forms developers](https://www.youtube.com/watch?v=a-NXfAvkp6I&feature=youtu.be) - September 19, 2019 - It's .NET ROCKS! Talking about Blazor with ASP.NET Web Forms developers.
* [Blazor OwningComponentBase Lifecycle](https://www.youtube.com/watch?v=-zyCAN7jfX0) - September 17, 2019 - Short video about the lifecycle of services managed by OwningComponentBase.
* [Integrating JavaScript and C# with Blazor](https://www.twitch.tv/videos/480856229) - September 13, 2019 - Integrating JavaScript and C# with Blazor.
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
* [Archives](https://github.com/AdrienTorris/awesome-blazor/tree/master/Archives) - [2019](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2019.md#videos), [2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#videos), [2017](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2017.md#videos).

## Articles
* [Introduction to Routing in Blazor](https://chrissainty.com/introduction-to-routing-in-blazor/) - October 22, 2019 - Introduction to Routing in Blazor.
* [Create PWA using Blazor](https://wellsb.com/csharp/aspnet/create-pwa-from-blazor-app/) - October 17, 2019 - How to convert a Blazor app into an installable PWA.
* [Uploading files in Blazor](https://www.mikesdotnetting.com/article/341/uploading-files-in-blazor) - October 17, 2019 - Uploading files in Blazor.
* [Blazor pages get partial class support](https://gunnarpeipman.com/blazor-partial-page-class/) - October 16, 2019 - Blazor pages get partial class support.
* [Goodbye Javascript! Build an Authenticated Web App in C# with Blazor + ASP.NET Core 3.0 ](https://developer.okta.com/blog/2019/10/16/csharp-blazor-authentication) - October 16, 2019 - Goodbye Javascript! Build an Authenticated Web App in C# with Blazor + ASP.NET Core 3.0 .
* [ASP.NET Core updates in .NET Core 3.1 Preview 1](https://devblogs.microsoft.com/aspnet/asp-net-core-updates-in-net-core-3-1-preview-1/) - October 15, 2019 - ASP.NET Core updates in .NET Core 3.1 Preview 1 by Daniel Roth. Interesting stuff for Blazor developers: partial class support and the ability to pass parameters to top-level components.
* [Blazor Server in .NET Core 3.0 scenarios and performance](https://devblogs.microsoft.com/aspnet/blazor-server-in-net-core-3-0-scenarios-and-performance/) - October 10, 2019 - Blazor Server in .NET Core 3.0 scenarios and performance, by Daniel Roth.
* [3 Ways to Bind Blazor Data to DOM](https://wellsb.com/csharp/aspnet/3-ways-to-bind-blazor-variables-to-dom/) - October 07, 2019 - One of the most useful Blazor features is the ability to pass data between your front-end DOM elements and back-end C# code. In this tutorial, you will learn techniques for binding C# variables such that they can be displayed in the browser or modified via user input in the browser.
* [Blazor Security Docs and Blog Posts](https://oceanware.wordpress.com/2019/10/06/blazor-security-docs-and-blog-posts/) - October 06, 2019 - List of security resources about Blazor.
* [Blazor Roundup From .NET Conf 2019](https://chrissainty.com/blazor-roundup-from-dot-net-conf-2019/) - October 01, 2019 - Blazor Roundup From .NET Conf 2019.
* [Getting Started with Blazor WebAssembly](https://wellsb.com/csharp/aspnet/getting-started-blazor-webassembly/) - September 30, 2019 - With the launch of .NET Core 3.0 and Visual Studio 16.3.0, support for creating web apps using the Blazor template is now natively enabled. This makes it easy for you to run your C# libraries directly in the browser.
* [Blazor Simple CQRS with MediatR](https://oceanware.wordpress.com/2019/09/29/blazor-simple-cqrs-with-mediatr/) - September 29, 2019 - Blazor Simple CQRS with MediatR.
* [Make it all dynamic in Blazor – Routing, Pages and Components](https://www.linkedin.com/pulse/make-all-dynamic-blazor-routing-pages-components-göran-halvarsson) - September 27, 2019 - Make it all dynamic in Blazor – Routing, Pages and Components.
* [The Future of Client-Side Blazor: PWAs, Desktop/Mobile, Native (and even Flutter?)](https://visualstudiomagazine.com/articles/2019/09/26/blazor-future.aspx) - September 26, 2019 - The Future of Client-Side Blazor: PWAs, Desktop/Mobile, Native (and even Flutter?), by Visual Studio Magazine.
* [Migrate Protogen To Blazor](https://remibou.github.io/Migrate-protogen-to-Blazor/) - September 26, 2019 - Migrate Protogen To Blazor.
* [Telerik UI for Blazor 2.1.0](https://www.telerik.com/blogs/telerik-ui-for-blazor-2.1.0-asp.net-core-3.0-compatibility-scatter-scatter-line-and-bubble-charts!) - September 25, 2019 - Telerik UI for Blazor 2.1.0 – ASP.NET Core 3.0 Compatibility, Scatter, Scatter Line and Bubble Charts!
* [What's new in ASP.NET Core 3.0](https://docs.microsoft.com/en-us/aspnet/core/release-notes/aspnetcore-3.0?view=aspnetcore-3.0) - September 23, 2019 - What's new in ASP.NET Core 3.0.
* [Telerik and Kendo UI R3 Release 2019 is Here!](https://www.telerik.com/blogs/telerik-and-kendo-ui-r3-release-2019-is-here!) - September 18, 2019 - Telerik and Kendo UI R3 Release 2019 is Here!
* [An Introduction to OwningComponentBase](https://chrissainty.com/an-introduction-to-owningcomponentbase/) - September 17, 2019 - This post  explores the OwningComponentBase class, which was added to Blazor in .NET Core 3 Preview 9. This class has a single purpose, create a service provider scope.
* [ASP.NET Core and Blazor updates in .NET Core 3.0 Release Candidate 1](https://devblogs.microsoft.com/aspnet/asp-net-core-and-blazor-updates-in-net-core-3-0-release-candidate-1/) - September 16, 2019 - ASP.NET Core and Blazor updates in .NET Core 3.0 Release Candidate 1.
* [Quick Tip: Blazor App Hosted as Azure Static Website in Blob Storage](https://visualstudiomagazine.com/blogs/data-driver/2019/09/blazor-app.aspx) - September 13, 2019 - Quick Tip: Blazor App Hosted as Azure Static Website in Blob Storage.
* [Containerising Blazor Applications With Docker (Part 4)](https://chrissainty.com/containerising-blazor-applications-with-docker-deploying-containerised-apps-to-azure-web-app-for-containers/) - September 10, 2019 - Containerising Blazor Applications With Docker (Part 4). [Source code](https://github.com/chrissainty/BlazorServerWithDocker).
* [Combining Razor and Blazor Pages in a Single ASP.NET Core 3 Application](https://mikaelkoskinen.net/post/combining-razor-blazor-pages-single-asp-net-core-3-application) - September 09, 2019 - Combining Razor and Blazor Pages in a Single ASP.NET Core 3 Application. [Source code](https://github.com/mikoskinen/blog/tree/master/blazor-pages-razor-pages-single-app).
* [Blazor Components - DataGrid and Scheduler Enhancements](https://community.devexpress.com/blogs/aspnet/archive/2019/09/09/blazor-components-datagrid-and-scheduler-enhancements-available-in-beta-3.aspx) - September 09, 2019 - Blazor Components - DataGrid and Scheduler Enhancements (available in Beta #3), by DevExpress.
* [A Blazor Application Updater](http://blazorhelpwebsite.com/Blog/tabid/61/EntryId/4352/A-Blazor-Application-Updater.aspx) - September 06, 2019 - A Blazor Application Updater.
* [ASP.NET Core and Blazor updates in .NET Core 3.0 Preview 9](https://devblogs.microsoft.com/aspnet/asp-net-core-and-blazor-updates-in-net-core-3-0-preview-9/) - September 04, 2019 - ASP.NET Core and Blazor updates in .NET Core 3.0 Preview 9.
* [Integrating FluentValidation with Blazor](http://blog.stevensanderson.com/2019/09/04/blazor-fluentvalidation/) - September 04, 2019 - An example of integrating a custom third-party validation system with Blazor's forms, by Steve Sanderson.
* [What's New for ASP.NET Core and Blazor in Final Preview of .NET Core 3.0](https://visualstudiomagazine.com/articles/2019/09/04/aspnet-core-updates.aspx) - September 04, 2019 - What's New for ASP.NET Core and Blazor in Final Preview of .NET Core 3.0.
* [Quantum Messaging with Q# and Blazor](https://msdn.microsoft.com/magazine/mt833512) - September 03, 2019 - Build an MVVM based Blazor app that leverages Q# and the remarkable phenomenon of quantum entanglement to instantly transfer half a message across potentially vast distances, while eliminating the risk of eavesdropping.
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
* [Pros and cons of Blazor for web development](https://scientificprogrammer.net/2019/08/18/pros-and-cons-of-blazor-for-web-development/) - August 18, 2019 - Pros and cons of Blazor for web development .
* [ASP.NET Core and Blazor updates in .NET Core 3.0 Preview 8](https://devblogs.microsoft.com/aspnet/asp-net-core-and-blazor-updates-in-net-core-3-0-preview-8/) - August 13, 2019 - ASP.NET Core and Blazor updates in .NET Core 3.0 Preview 8.
* [Investigating Drag and Drop with Blazor](https://chrissainty.com/investigating-drag-and-drop-with-blazor/) - August 13, 2019 - Investigating Drag and Drop with Blazor. [Source code](https://github.com/chrissainty/SimpleDragAndDropWithBlazor).
* [How does Blazor works ? Part 2 : building](https://remibou.github.io/Blazor-how-it-works-part-2) - August 10, 2019 - This blog post is the 2nd part of a series about how Blazor (client side) works, from the build process to the update of the UI. The first part started with a "simple" command "dotnet run" and ended with generated classes representing the razor files. This post is about the rest of the building process and the part of it that handle integration with monowasm.
* [Using npm packages with Blazor](https://medium.com/swlh/using-npm-packages-with-blazor-2b0310279320) - August 09, 2019 - Using npm packages with Blazor.
* [Build Data-Driven Web Apps Blazing Fast with Blazor and OData](https://blog.jeremylikness.com/blog/build-data-driven-apps-blazing-fast-with-blazor-and-odata) - August 09, 2019 - Build Data-Driven Web Apps Blazing Fast with Blazor and OData. Step aside GraphQL, this is WCF RIA reborn!
* [Blazor Binding, Events and Parameters](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/4350/Blazor-Binding-Events-and-Parameters.aspx) - August 06, 2019 - Three things that you will usually find yourself using on every Blazor page, Binding, Events, and Parameters, are covered in this article who shows how to build a series of pages including a few that will allow a user to build and edit a list of To Do items.
* [Using Razor Components in a Razor Page](https://www.mikesdotnetting.com/article/338/using-razor-components-in-a-razor-page) - August 05, 2019 - Blog post about how to include a Blazor/Razor component in a Razor Pages application in .NET Core 3.0.
* [IndexedDB in Blazor](https://blog.stevensanderson.com/2019/08/03/blazor-indexeddb/) - August 03, 2019 - Exploring the Reshiru.Blazor.IndexedDB package, by Steve Sanderson.
* [Deploying a Server Side Blazor application to Azure](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/4349/Deploying-A-Server-Side-Blazor-Application-To-Azure.aspx) - August 3, 2019 - Deploying a Server Side Blazor application to Azure.
* [Using a Code-Behind Approach to Blazor Components](https://www.telerik.com/blogs/using-a-code-behind-approach-to-blazor-components) - July 31, 2019 - In this article we'll look into when it's helpful to use a code-behind in your Blazor development, how we benefit and what to expect when re-factoring existing components.
* [Configuring Policy-based Authorization with Blazor](https://chrissainty.com/securing-your-blazor-apps-configuring-policy-based-authorization-with-blazor/) - July 30, 2019 - Part 4 of the series "Securing Your Blazor Apps", by Chris Sainty.
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
* [Data binding in Blazor](https://coderethinked.com/data-binding-in-blazor/) - May 13, 2019 - Data binding in Blazor.
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
* [Archives](https://github.com/AdrienTorris/awesome-blazor/tree/master/Archives) - [2019](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2019.md#articles), [2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#articles), [2017](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2017.md#articles).
  
## Podcasts
* [.NET Core 3 Launch with Scott Hunter](https://www.dotnetrocks.com/?show=1654) - September 26, 2019 - .NET Rocks Podcast, episode 1654: .NET Core 3 Launch with Scott Hunter.
* [Moving from Web Forms to Blazor with Jeff Fritz](https://www.dotnetrocks.com/default.aspx?ShowNum=1652) - September 12, 2019 - .NET Rocks Podcast, episode 1652: Moving from Web Forms to Blazor with Jeff Fritz.
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
* [Archives](https://github.com/AdrienTorris/awesome-blazor/tree/master/Archives) - [2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#podcasts), [2017](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2017.md#podcasts).

## Presentations slides
* [Blazor, a new framework for browser-based .NET apps](https://github.com/SteveSandersonMS/presentation-2019-06-NDCOslo) - ![GitHub stars](https://img.shields.io/github/stars/SteveSandersonMS/presentation-2019-06-NDCOslo?style=flat-square&cacheSeconds=604800) June 20, 2019 - Blazor, a new framework for browser-based .NET apps, by Steve Sanderson at the NDC Oslo.
* [Hidden gems in ASP.Core and .NET Core 3.0](https://speakerdeck.com/davidfowl/hidden-gems-in-asp-dot-core-and-net-core-3-dot-0) - June 19, 2019 - Hidden gems in ASP.Core and .NET Core 3.0, by David Fowler and Damian Edwards at the NDC Oslo.
* [Meet the production-ready Blazor aka Razor Components](https://codecamp.ro/timisoaraSpring) - May 25, 2019 - Slides: [PPTX](https://codecampro.blob.core.windows.net/sessions-upload/1306-CCBlazor.pptx).
* [Iowa .NET User Group – Blazor: C# Running in the Browser via WebAssembly](https://scottsauber.com/2019/05/02/iowa-net-user-group-blazor-c-running-in-the-browser-via-webassembly/) - May 2, 2019 - Slides: [PDF](https://scottsauber.files.wordpress.com/2019/05/blazor.pdf) or [PPTX](https://scottsauber.files.wordpress.com/2019/05/blazor.pptx). Code: [Blazor ToDoMVC](https://github.com/scottsauber/BlazorToDoMVC) ![GitHub stars](https://img.shields.io/github/stars/scottsauber/BlazorToDoMVC?style=flat-square&cacheSeconds=604800) and [Blazor on Electron](https://github.com/SteveSandersonMS/BlazorElectronExperiment.Sample) ![GitHub stars](https://img.shields.io/github/stars/SteveSandersonMS/BlazorElectronExperiment.Sample?style=flat-square&cacheSeconds=604800).
* [WebAssembly, C#, and Blazor at CodeStock 2019](https://blog.jeremylikness.com/presentation-webassembly-c-and-blazor-at-codestock-2019-ab2f8636356) - April 16, 2019 - Slides: [PDF](https://jlikme.blob.core.windows.net/presentations/ATaleOfShortLinks.pdf). Demo's source code: [GitHub](https://github.com/JeremyLikness/blazor-wasm) ![GitHub stars](https://img.shields.io/github/stars/JeremyLikness/blazor-wasm?style=flat-square&cacheSeconds=604800).
* [Archives](https://github.com/AdrienTorris/awesome-blazor/tree/master/Archives) - [2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#presentations-slides).

## Tooling
* [BlazorFiddle](https://blazorfiddle.com) - Blazor .Net Developer Playground and Code Editor in the Browser.
* [Blazor Minimum Project Templates](https://github.com/jsakamoto/BlazorMinimumTemplates) - ![GitHub stars](https://img.shields.io/github/stars/jsakamoto/BlazorMinimumTemplates?style=flat-square&cacheSeconds=604800) A project templates package of Blazor apps without JavaScript and CSS libraries.
* [Blazor Snippets Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=ScottSauber.blazorsnippets) - A Visual Studio Code extension that offers Blazor and Razor snippets.
* [BlazorSourceMangler](https://github.com/Lupusa87/BlazorSourceMangler) - ![GitHub stars](https://img.shields.io/github/stars/Lupusa87/BlazorSourceMangler?style=flat-square&cacheSeconds=604800) A console app to mangle Blazor DLLs. Check this [YouTube video](https://www.youtube.com/watch?v=nlXax81b1UE) for more details. You can also check this [Blazor TODO app](https://lupblazortodo.z20.web.core.windows.net/) to see result of this app (downloaded blazortodos.dll is mangled and decompilation shows uglyfied code).
* [.NET Core](https://www.microsoft.com/net/download/dotnet-core) - .NET Core.
* [Razor+ Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=austincummings.razor-plus) - A Visual Studio Code extension that offers improved Razor support.
* [Visual Studio](https://www.visualstudio.com/vs/preview) - Latest preview of Visual Studio.
* [Visual Studio Code](https://code.visualstudio.com/) - Visual Studio Code, free, open source and cross-platform code editor.

## Books
* [Blazor Revealed](https://www.apress.com/gp/book/9781484243428) - Blazor Revealed, Building Web Applications in .NET(Published February, 2019).
* [Blazor Quick Start Guide: Build web applications using Blazor, EF Core, and SQL Server](https://www.amazon.in/gp/product/178934414X/ref=awesome_blazor) - Blazor Quick Start Guide: Build web applications using Blazor, EF Core, and SQL Server (Published October 31, 2018).

## E-Books
* [Blazor for ASP.NET Web Forms developers](https://dotnet.microsoft.com/learn/aspnet/architecture#blazor-for-web-forms-devs-ebook-swim) - Blazor for ASP.NET Web Forms developers, a free e-book from Microsoft.
* [An Introduction to Building Applications with Blazor](https://www.amazon.com/Introduction-Building-Applications-Blazor-applications-ebook/dp/B07WPQTT6H) - August 24, 2019 - An Introduction to Building Applications with Blazor: How to get started creating applications using this exciting easy to use Microsoft C# framework
* [Archives](https://github.com/AdrienTorris/awesome-blazor/tree/master/Archives) - [2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#e-books).

## Courses
* [Blazor and Razor Components in a nutshell](https://www.udemy.com/course/blazor-and-razor-components-in-a-nutshell/) - October 2019 - Learn how to use a framework that allows you to run your compiled code directly in the browser on top of WebAssembly, a course on Udemy.
* [Blazor on ASP.NET Core 3.0](https://www.skillshare.com/site/join?teacherRef=102575464&t=Blazor-on-ASP.NET-Core-3.0&sku=1662883580) - October 2019 - Blazor on ASP.NET Core 3.0, a course on SkillShare.
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
* [Blazor.ru](https://blazor.ru/) - [Russian] Old official documentation website translated in Russian.
* [DevApps.be's podcast #44](http://devapps.be/podcast/blazor-webassembly/) - [French] DevApps.be's podcast #44: "Blazor et WebAssembly vont-ils tuer JavaScript ?".
* [DevApps.be's podcast #47](http://devapps.be/podcast/47-typescript-uno-angular-docfx/) - [French] DevApps.be's podcast #47: "Actualités : TypeScript, Uno, Angular, DocFX, Database".
* [Modern web apps with Blazor](https://media.aspitalia.com/events/VS2019-Blazor.media) - [Italian] Video about Blazor.
* [Playlist - Programando en Blazor](https://www.youtube.com/playlist?list=PL0kIvpOlieSNdIPZbn-mO15YIjRHY2wI9) - [Spanish] Series of videos about Blazor.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Adrien Torris has waived all copyright and related or neighboring rights to this work.
