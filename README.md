# Awesome Blazor [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A collection of awesome Blazor resources.

Inspired by [awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet) and [awesome-dotnet-core](https://github.com/thangchung/awesome-dotnet-core).

The goal is to build a categorized community-driven collection of very well-known resources about Blazor.

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
* [Tooling](#tooling)
* [Books](#books)
* [E-Books](#e-books)
* [Courses](#courses)
* [Community](#community)

## Introduction
### What is Blazor
Blazor is a .NET web framework to build client web apps with C#.
Blazor lets you build interactive web UIs using C# instead of JavaScript. Blazor apps are composed of reusable web UI components implemented using C#, HTML, and CSS. Both client and server code is written in C#, allowing you to share code and libraries.
More information on the [official website](https://dotnet.microsoft.com/apps/aspnet/web-apps/client).

### Requirements
Please note that if you want to open Blazor projects in Visual Studio, you must have [Visual Studio 15.7 Preview 1](https://www.visualstudio.com/vs/preview/) or later and the [.NET Core 2.1 Preview 1 SDK](https://www.microsoft.com/net/download/dotnet-core/sdk-2.1.300-preview1).
Recommanded: [Visual Studio 2019 Preview](https://visualstudio.microsoft.com/) and the [latest .NET Core Framework](https://dotnet.microsoft.com/download/dotnet-core/3.0).

## General
* [ASP.NET Blog's archives](https://devblogs.microsoft.com/aspnet/category/blazor/) - Archives of the ASP.NET blog about Blazor.
* [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/client) - Official website of Blazor, from Microsoft.
* [Blazor bites](https://chrissainty.com/blazor-bites/) - Blazor bites series by chris Sainty.
* [Blazor-Dev gallery on .NET Foundation](https://dotnet.myget.org/gallery/blazor-dev) - Daily builds of the 'dev' branch of Blazor.
* [Blazor Extensions](https://github.com/BlazorExtensions) - Curated extensions for Microsoft ASP.Net Core Blazor.
* [Demo](https://blazor-demo.github.io/) - Official demo website.
* [FAQ](https://github.com/aspnet/Blazor/wiki/FAQ) - FAQ.
* [GitHub repository](https://github.com/aspnet/Blazor) - The official Blazor repository.
* ['Hello World' sample](https://github.com/dodyg/practical-aspnetcore/tree/master/projects/blazor) - 'Hello World' sample.
* [Introduction to ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/) - Introduction to ASP.NET Core.
* [Learn Blazor](https://learn-blazor.com) - An unofficial documentation website ([source code here](https://github.com/software-architects/learn-blazor)).
* [Workshop](https://github.com/dotnet-presentations/blazor-workshop/) - Blazor workshop.

## Sample Projects
* [ASP.NET Core Blazor CRUD](https://code.msdn.microsoft.com/vstudio/ASPNET-Core-Blazor-122b108a) - ASP.NET Core Blazor Master/Detail CRUD with Filtering and Sorting using EF.
* [AsteroidsWasm](https://github.com/aesalazar/AsteroidsWasm) - A mixed bag of C# projects to see if a single .NET Standard base can run across all common platforms include WebAssembly. [Demo](https://aesalazar.github.io/AsteroidsWasm/).
* [Beam](https://github.com/Dedac/Beam) - A social network demo application. This is the source code of the LinkedIn course "Blazor First Look".
* [Blangular](https://github.com/danroth27/Blangular) - Blazor + Angular, by Daniel Roth.
* [BlazeDown](https://github.com/EdCharbeneau/BlazeDown) - BlazeDown, online Markdown editor. [Demo](https://edcharbeneau.com/BlazeDown/).
* [Blazing Chuck](https://davidpine.net/blog/blazing-chuck/) - An example Blazor app that displays random "nerdy" Chuck Norris jokes. [Demo](http://ievangelistblazingchuck.azurewebsites.net/).
* [BlazingPizza (server side)](https://github.com/ADefWebserver/BlazingPizza) - A server side Blazor version of the Blazing Pizza project from the [Blazor - app building workshop](https://github.com/dotnet-presentations/blazor-workshop/).
* [BlazorAdvancedTodo](https://github.com/EdCharbeneau/BlazorAdvancedTodo) - A Blazor to-do app with state and undo function.
* [BlazorAzureSignalRService](https://github.com/danroth27/BlazorAzureSignalRService) - Blazor + Azure SignalR Service.
* [BlazorBinding](https://github.com/SQL-MisterMagoo/BlazorBinding) - Sample Blazor App demonstrating various data binding scenarios.
* [BlazorBricks](https://www.codeproject.com/Articles/1241210/WebAssembly-with-Blazor) - BlazorBricks, a Blazor implementation of the game Tetris.
* [BlazorCalculator](https://github.com/Lupusa87/BlazorCalculator) - Simple calculator with history and ability to use previous results in new calculations. [Demo](https://lupblazorcalculator.z20.web.core.windows.net/).
* [Blazor calculator with expressions](https://github.com/khaledmousa/BlazorCalculator) - A sample numerical expression evaluator in Blazor utilizing an F# library that uses FsLex and FsYacc to parse expressions. [Demo](https://khaledmousa.github.io/).
* [BlazorChat](https://github.com/danroth27/BlazorChat) - Real-time chat app using ASP.NET Core and Blazor, from Daniel Roth.
* [BlazorChatSample](https://github.com/conficient/blazorchatsample) - Blazor chat demo using SignalR JS client with interop.
* [BlazorChess](https://github.com/Lupusa87/BlazorChess) - Chess engine implemented with Blazor. [Demo](https://lupblazorchess.z20.web.core.windows.net/).
* [BlazorClockCanvas](https://github.com/Lupusa87/BlazorClockCanvas) - Complex clock based on Canvas. [Demo](https://lupblazorclockcanvas.z20.web.core.windows.net/).
* [BlazorClockSVG](https://github.com/Lupusa87/BlazorClockSVG) - Complex clock based on SVG. [Demo](https://lupblazorclocksvg.z20.web.core.windows.net/).
* [Blazor Contoso University](https://github.com/lohithgn/blazor-contoso-university) - Contoso University in Blazor.
* [Blazor Converters](https://github.com/lohithgn/blazor-converters) - Blazor Converters is simple converter app written using Blazor, influenced by Windows 10 Calculator.
* [Blazor.DataDrivenLayout](https://github.com/hutchcodes/Blazor.DataDrivenLayout) - Two example of how to do data driven layouts in Server-side Blazor.
* [BlazorDestinationGame](https://github.com/SharePointSean/BlazorDestinationGame) - Quizz about places in the world. [Demo](https://blazordestinationgame.azurewebsites.net/).
* [BlazorDice](https://github.com/shahedc/BlazorDemos/tree/master/BlazorDice) - Roll the dice.
* [BlazorDynamicList](https://github.com/conficient/BlazorDynamicList) - Dynamic component binding for a generic list. [Demo](https://blazordynamiclist.azurewebsites.net/).
* [BlazorElectronExperiment](https://github.com/SteveSandersonMS/BlazorElectronExperiment.Sample) - Exploring how a Blazor could be used to build a cross-platform desktop application using [Electron](https://electronjs.org/).
* [BlazorFileReader](https://github.com/Tewr/BlazorFileReader) - Read-only File streams in Blazor. [Demo](https://tewr.github.io/BlazorFileReader/).
* [BlazorFormsValidation](https://github.com/Dallas411/BlazorFormsValidation) - Blazor form validation sample.
* [BlazorGameSnake](https://github.com/Lupusa87/BlazorGameSnake) - 2D game snake with customizations, path finding algorithm, and sound effects using SVG. [Demo](https://lupblazorsnake.z20.web.core.windows.net/).
* [BlazorGeolocation](https://github.com/EdCharbeneau/BlazorGeolocation) - An example of using Geolocation with Blazor.
* [BlazorGraphExample](https://github.com/jburman/BlazorGraphExample) - Example application for connecting to Graph API from Blazor.
* [Blazor.JWTTest](https://github.com/shawty/blazor.jwttest) - JWT authentication for a blazor hosted (Client/Serverside) app with API and Authentication.
* [BlazorMobile](https://github.com/Daddoon/BlazorMobile) - Launch a Blazor application as a standalone application.
* [BlazorNasaImages](https://github.com/ncarandini/BlazorNasaImages) - A sample Blazor app that fetches the Nasa Astronomy Picture of the Day.
* [BlazorPaint](https://github.com/Lupusa87/BlazorPaint) - A paint sample with Blazor ([demo](https://lupblazorpaint.z20.web.core.windows.net/)).
* [BlazorPass](https://github.com/ebekker/BlazorPass) - Blazor UI and ASP.NET Core API to manage Active Directory credentials.
* [BlazorPasswordPattern](https://github.com/Lupusa87/BlazorPasswordPattern) - Password pattern based on SVG. [Demo](https://lupblazorpasswordpattern.z20.web.core.windows.net/).
* [BlazorPong](https://github.com/ctrl-alt-d/blazorpong) - 8 bits pong with blazor and signalR. Warning: Blazor Pong is not finished and is stopped with a knowed SignalR issue with Blazor, more info [here](https://github.com/AdrienTorris/awesome-blazor/pull/19).
* [BlazorQuiz](https://github.com/Amine-Smahi/BlazorQuiz) - Simple quiz using Blazor.NET and Webassembly.
* [BlazorRawHtmlRenderer](https://github.com/Lupusa87/BlazorRawHtmlRenderer) - Raw HTML rendering with Blazor. [Demo](https://lupblazorrawhtml.z20.web.core.windows.net/).
* [BlazorServerTree](https://github.com/ctrl-alt-d/BlazorServerTree) - A simple Server-Side Blazor sample app to deal with hierarchical data.
* [BlazorServiceWorker](https://github.com/roboriaan/BlazorServiceWorker) - A client-side Blazor template with service worker caching.
* [Blazorships](https://github.com/bjorndaniel/Blazorships) - Blazorships, a Blazor implementation of Battleship using SignalR.
* [Blazor Spreadsheet](https://github.com/Lupusa87/BlazorSpreadsheet) - Spreadsheet app developed in Blazor. [Demo](https://lupblazorspreadsheet.z20.web.core.windows.net/).
* [Blazor Summernote](https://github.com/shawty/blazor.summernote) - Wrapper for the new MS Blazor framework, allowing the use of the Summernote Wysiwyg editor in a form.
* [Blazor Survey](https://github.com/nutshellit/Blazor-Survey) - A hybrid F#/C# blazor sample app to kick the tyres of blazor.
* [Blazor Sushi](https://github.com/lohithgn/blazor-sushi) - Kendo UI Sushi SPA recreated in Blazor.
* [BlazorTasks](https://github.com/BorowskiKamil/blazor-tasks) - To-Do App.
* [Blazor.Toaster](https://github.com/sotsera/sotsera.blazor.toaster) - A Blazor port of Toastr.js.
* [Blazor Tree CRUD](https://github.com/ctrl-alt-d/TreeCrud) - CRUD operations with hierarchical data. Blazor Server + GraphQL + EF.
* [Blazor.Universal](https://github.com/pushqrdx/Blazor.Universal) - Example of using Blazor to build Xamarin based UWP application without WebAssembly.
* [BlazorUnmarshalledCanvas](https://github.com/jhwcn/BlazorUnmarshalledCanvas) - Unmarshalled invoking of Canvas 2d context from Blazor.
* [BlazorValidationControls](https://github.com/hishamco/BlazorValidationControls) - Blazor validation controls.
* [Blazor.Xamarin](https://github.com/Appizeo/Blazor.Xamarin) - A Xamarin template for launch and interop a Blazor app on mobile.
* [Blazor + Electron sample](https://github.com/aspnet/AspLabs/tree/master/src/ComponentsElectron) - Explore how a Blazor app can be used to build a cross-platform desktop app.
* [Blazor + Sitecore](https://github.com/GoranHalvarsson/SitecoreBlazor) - Example of dynamic pages and routes with SiteCore and [Helix](https://helix.sitecore.net/).
* [Blazume](https://github.com/Amine-Smahi/Blazume) - A simple portfolio/Resume template using Blazor.
* [Bolero.TodoMVC](https://github.com/fsbolero/TodoMVC) - A TodoMVC clone using Bolero.
* [Calamari Blog](https://github.com/thewebchameleon/calamari-blog-blazor) - A simple blog and portfolio site running on Squidex.
* [CRUD sample with EF](https://code.msdn.microsoft.com/vstudio/ASPNET-Core-Blazor-122b108a) - ASP.NET Core Blazor Master/Detail CRUD with Filtering and Sorting using EF.
* [CssBuilder](https://www.nuget.org/packages/BlazorComponentUtilities/) &ndash; A clean code approach to conditional CSS classes for Razor components in Blazor.
* [Data Driven Layout](https://github.com/hutchcodes/Blazor.DataDrivenLayout) - Two ways of driving the layout based on data in the page.
* [Demo](https://github.com/blazor-demo/blazor-demo.github.io) - Code of the official demo website.
* [Do](https://github.com/jamie-lord/do) - To Do app.
* [Flight Finder](https://github.com/aspnet/samples/tree/master/samples/aspnetcore/blazor) - Flight Finder.
* [FMRL](https://github.com/ebekker/FMRL) - Ephemeral Message Service. Messages sent are encrypted, securely transferred, and automatically deleted when they are retrieved.
* [Gitter](https://github.com/Blazored/Gitter) - A Blazor Gitter client.
* [Hacker News Clone](https://github.com/lohithgn/blazor-hackernews-clone) - Hacker News Clone. [Demo](http://blazorhackernews.surge.sh/).
* [Money](https://github.com/maraf/Money) - A money manager implemented using CQRS+ES. [Demo](https://app.money.neptuo.com/).
* [NethereumBlazor](https://github.com/Nethereum/NethereumBlazor) - Ethereum blockchain explorer and simple wallet.
* [Planning Poker](https://github.com/duracellko/planningpoker4azure) ([Demo](http://planningpoker.duracellko.net)) &ndash; An app to play Planning Poker for distributed teams. The app is implemented using Blazor and shows how to switch between client-side and server-side mode with a configuration change.
* [Quick CMS](https://github.com/robertsundstrom/quick-cms) - Personal blog engine.
* [Randify](https://github.com/tinyioda/Randify) - Spotify Playlist randomizer.
* [Realworld](https://github.com/torhovland/blazor-realworld-example-app) - Blazor realworld example app. [Demo](http://blazor-realworld.azurewebsites.net/).
* [Runny](https://github.com/Suchiman/Runny) - Prototype of running roslyn in the browser via Blazor. [Demo](https://runny.azurewebsites.net/).
* [RSS Reader](https://github.com/lohithgn/blazor-rss-reader) - RSS Reader built using Blazor.
* [RxBlazor](https://github.com/bmsantos/RxBlazor) - Rx.NET based MessageService demo for Blazor Framework.
* [StarshipTraveler](https://github.com/rstropek/StarshipTraveler) - A starship traveler demo app built with Blazor for the DevOne 2019 conference.
* [TaxiFareBlazorServer](https://github.com/EdCharbeneau/TaxiFareBlazorServer) - ML.NET TaxiFare Prediction Model with Blazor Server-Side front end.
* [Tour of Heroes](https://github.com/lohithgn/blazor-tour-of-heroes) - Blazor implementation of Angular Tour of Heroes.
* [Toss.Blazor](https://github.com/RemiBou/Toss.Blazor) - Twitter-like web application using Blazor.
* [TrendTv](https://github.com/MattMarked/TrendTv) - Fetch video list from YouTube and "zap" in real time between trending videos, filtered by country or category.
* [Try F# on WebAssembly](https://github.com/fsbolero/TryFSharpOnWasm) - The F# compiler running in WebAssembly with Bolero.
* [Tulsa .NET User Group website](https://github.com/devsgarage/tulsa-dnug-website) - Tulsa .NET User Group website.
* [Tzaar](https://github.com/paularundel/tzaar) - Implementation of the board game Tzaar with Blazor and SignalR. [Demo](https://tzaar.azurewebsites.net/).
* [VocaDB lyrics](https://github.com/riipah/vocadb-lyrics-blazor-proto) - VocaDB lyrics display Blazor proto. [Demo](https://lyrics-proto.vocadb.net/).
* [WebSocketPage](https://github.com/Lupusa87/BlazorWebSocketHelper) - Web Socket in Blazor. [demo](https://lupblazordemos.z13.web.core.windows.net/WebSocketPage).
* [WordDaze](https://github.com/chrissainty/worddaze) - Blogging application written using Blazor with a WebAPI backend.
* [ZoraGen Blazor](https://github.com/friendlyanon/zoragen-blazor) - PWA capable Blazor UI for the [ZoraSharp](https://github.com/kabili207/zora-sharp) library.

## Tutorials
* [Get .NET Core 3 and Blazor running on a Raspberry PI](https://gist.github.com/shawty/a55f6d09edc2d381c8bd5bf2f639b2de) - April 24, 2019 - Instructions on how to get the latest .NET Core 3 (as of 24th April 2019) and Blazor running on a Raspberry PI.
* [Blazor TODO list](https://github.com/exceptionnotfound/BlazorToDoList) - April 22, 2019 - Blazor TODO list.
* [A Nicer Looking Blazor Loading Page](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/4315/A-Nicer-Looking-Blazor-Loading-Page.aspx) - October 14, 2018 - Customize the Blazor loading page using [SpinKit](https://github.com/tobiasahlin/SpinKit).
* [Blazor workshop](https://github.com/dotnet-presentations/blazor-workshop/) - Blazor app building workshop by [.NET Foundation](https://www.dotnetfoundation.org/), Blazzing Pizza.
* [Data Driven Layout](https://github.com/hutchcodes/Blazor.DataDrivenLayout) - September 24, 2018 - Two ways of driving the layout based on data in the page.
* [ASP.NET Core Blazor CRUD](https://code.msdn.microsoft.com/vstudio/ASPNET-Core-Blazor-122b108a) - August 20, 2018 - A master/detail HTML CRUD example with sorting and filtering using Entity Framework and Web API.
* [Blazing Chuck](https://davidpine.net/blog/blazing-chuck/) - August 20, 2018 - An example Blazor app that displays random "nerdy" Chuck Norris jokes. [Demo](http://ievangelistblazingchuck.azurewebsites.net/).
* [Blazor + Sitecore](https://visionsincode.wordpress.com/2018/06/30/time-travel-into-the-future-blazor-sitecore-helix/) - June 30, 2018 - Time travel into the future – Blazor + Sitecore + Helix.
* [Blazor Bricks](https://www.codeproject.com/Articles/1241210/WebAssembly-with-Blazor) - May 11, 2018 - A bricks game developed with C# and Blazor.

## Libraries & Extensions
* [Bionic](https://bionicframework.github.io/Documentation/) - An Ionic CLI clone for Blazor projects.
* [Blazor Analytics](https://github.com/isc30/blazor-analytics) - Blazor extensions for Analytics.
* [Blazor BarCode](https://barcoderesource.com/blazorbarcode.shtml) &ndash; A barcode library for Blazor using barcode fonts.
* [Blazor Extensions Home](https://github.com/BlazorExtensions/Home) - Home for Blazor Extensions.
* [Blazor Gamepad](https://github.com/jsakamoto/Toolbelt.Blazor.Gamepad) - Provides gamepad API access for Blazor.
* [Blazor Hotkeys](https://github.com/jsakamoto/Toolbelt.Blazor.Hotkeys) - A library to provide configuration-centric keyboard shortcuts for Blazor.
* [Blazor LoadingBar](https://github.com/jsakamoto/Toolbelt.Blazor.LoadingBar) - Loading bar UI for Client-Side Blazor application.
* [Blazor Svg Helper](https://github.com/Lupusa87/BlazorSvgHelper) - Create SVG elements with children (circle, rectangle, image, text, and others) and render with RenderTreeBuilder ([Demo](https://lupblazordemos.z13.web.core.windows.net/)).
* [Blazor Time Zone Kit](https://github.com/jsakamoto/Toolbelt.Blazor.TimeZoneKit) - A library to provide system time zones and local time zone initialization in Blazor apps.
* [Blazor-Charts](https://github.com/Misfits-Rebels-Outcasts/Blazor-Charts) - SVG charts for Blazor.
* [Blazor-Dashboard](https://github.com/Misfits-Rebels-Outcasts/Blazor-Dashboard) - Admin Dashboard Template Theme for Blazor.
* [Blazor-Fluxor](https://github.com/mrpmorris/blazor-fluxor) - A low-boilerplate Flux/Redux state library for Blazor.
* [Blazor-Redux](https://github.com/torhovland/blazor-redux) - Connecting a Redux state store with Blazor.
* [Blazor-State](https://github.com/TimeWarpEngineering/blazor-state) - Manage client side state in Blazor using MediatR pipeline.
* [Blazor.Auth0](https://github.com/Pegazux/Blazor.Auth0) - Library for Blazor authentication with OIDC Authorization Code-Grant and Implicit-Grant flows, using Auth0's Universal Login and Silent Login.
* [Blazor.EventAggregator](https://github.com/mikoskinen/Blazor.EventAggregator) - Lightweight Event Aggregator for Blazor (Razor Components).
* [Blazor.FlexGrid](https://github.com/Mewriick/Blazor.FlexGrid) - GridView component for Blazor.
* [Blazor.Geolocation](https://github.com/AspNetMonsters/Blazor.Geolocation) - Blazor interop for browers Geolocation apis.
* [Blazor.LocalFiles](https://github.com/jburman/W8lessLabs.Blazor.LocalFiles) - Open files in your browser and load into Blazor.
* [Blazor.Payments](https://github.com/philipblaquiere/Blazor.Payments) - Blazor Web Agent port of the Web Payment API standard developed by W3C .
* [Blazor.Polyfill](https://github.com/Daddoon/Blazor.Polyfill) - Polyfills for Blazor (for Internet Explorer 11 support and some other browsers).
* [Blazor.Sensors](https://github.com/AspNetMonsters/Blazor.Sensors) - Blazor interop for browers sensor apis.
* [Blazor.SpeechSynthesis](https://github.com/jsakamoto/Toolbelt.Blazor.SpeechSynthesis) - A library to provide Speech Synthesis API access for Blazor.
* [Blazor.Validation.DataAnnotation](https://github.com/RemiBou/Blazor.Validation.DataAnnotation) - Library for validating form on a Blazor application using Data Annotation.
* [Blazor.Xamarin](https://github.com/Daddoon/Blazor.Xamarin) - A Xamarin template for launch and interop a Blazor app on mobile.
* [BlazorBits](https://github.com/BlazorBits/BlazorBits) - Components including [Monaco editor](https://github.com/Microsoft/monaco-editor).
* [BlazorComponents](https://github.com/muqeet-khan/BlazorComponents) - Reusable components for Blazor. Starting with ChartJS interop.
* [BlazorConfirm](https://github.com/ctrl-alt-d/BlazorConfirm) - A Blazor Wrapper for JS's `Window.confirm()` and `onbeforeunload` as .Net Blazor Component ([Demo](https://ctrl-alt-d.github.io/BlazorConfirm/))
* [BlazorContextMenu](https://github.com/stavroskasidis/BlazorContextMenu) - A context menu component for Blazor ([Demo](https://blazor-context-menu-demo.azurewebsites.net/)).
* [BlazorDB](https://github.com/chanan/BlazorDB) - In-memory, persisted to local storage, database for Blazor.
* [BlazorEmbedLibrary](https://github.com/SQL-MisterMagoo/BlazorEmbedLibrary) - Provides Blazor-style embedded static content files for Razor Components projects.
* [BlazorFileSaver](https://github.com/IvanJosipovic/BlazorFileSaver) - Blazor Component wrapper for FileSaver.js.
* [BlazorGrid](https://github.com/AnkitSharma-007/BlazorGrid) - This is a reusable grid component for Blazor which also supports client side pagination.
* [BlazorMaterial](https://github.com/BlazorExtensions/BlazorMaterial) - Blazor components implementing Google's Material components for web.
* [BlazorNodaTimeDateTimePicker](https://github.com/nheath99/BlazorNodaTimeDateTimePicker) - A Date/Time picker component library for Blazor using NodaTime.
* [BlazorOfficeUIFabric](https://github.com/BlazorExtensions/BlazorOfficeUIFabric) - Microsoft Office Fabric UI port for Blazor.
* [BlazorRealm](https://dworthen.github.io/BlazorRealm/docs/quickstart.html) - Redux state management for Blazor.
* [BlazorScrollbar](https://github.com/Lupusa87/BlazorScrollbar) - Reusable, fully configurable component with vertical and horizontal scrollbars ([Demo](https://lupblazorscrollbar.z20.web.core.windows.net/)).
* [BlazorSignalR](https://github.com/csnewman/BlazorSignalR) - SignalR Core .NET client library for Blazor. It uses the C# client.
* [BlazorSplit](https://github.com/BlazorComponents/BlazorSplit) - Resizeable split views ([Demo](https://blazorcomponents.github.io/BlazorSplit/)).
* [BlazorSplitter](https://github.com/Lupusa87/BlazorSplitter) - Reusable, fully configurable component with vertical and horizontal splitters and diagonal resizer ([Demo](https://lupblazorsplitter.z20.web.core.windows.net/)).
* [BlazorStorage](https://github.com/cloudcrate/BlazorStorage) - Local and session storage support for Blazor.
* [BlazorStrap](https://github.com/chanan/BlazorStrap) - Bootstrap 4 components for Blazor ([Demo](https://chanan.github.io/BlazorStrap/)).
* [BlazorVirtualGrid](https://github.com/Lupusa87/BlazorVirtualGrid) - Reusable, fully configurable component with rows and columns fast virtualization ([Demo](https://lupblazorvirtualgrid.z13.web.core.windows.net/)).
* [BlazorVirtualScrolling](https://github.com/SamProf/BlazorVirtualScrolling) - Virtual Scrolling Component for Blazor
 ([Demo](https://samprof.github.io/BlazorVirtualScrolling/)).
* [Blazored.LocalStorage](https://github.com/chrissainty/BlazoredLocalStorage) - Local storage for Blazor applications.
* [Blazored.Localisation](https://github.com/Blazored/Localisation) - A library to provide localisation in client-side Blazor applications.
* [Blazored.Menu](https://github.com/Blazored/Menu) - A JavaScript free menu library for Blazor and Razor Components applications.
* [Blazored.Modal](https://github.com/Blazored/Modal) - A JavaScript free modal library for Blazor and Razor Components applications.
* [Blazored.Toast](https://github.com/Blazored/Toast) - A JavaScript free toast library for Blazor and Razor Component applications.
* [Blazorise](https://github.com/stsrki/Blazorise) - Components for Blazor with support for Bootstrap, Bulma and Material CSS. ([Demo](https://bootstrapdemo.blazorise.com/))
* [Blazorous](https://github.com/chanan/Blazorous) - Maintainable CSS with Blazor ([Demo](https://chanan.github.io/Blazorous)).
* [Bolero](https://github.com/fsbolero/Bolero) - Blazor for F# with hot reloaded templates, type-safe endpoints and routing, remoting, and much more.
* [Canvas](https://github.com/BlazorExtensions/Canvas) - HTML5 Canvas API implementation for Microsoft Blazor.
* [ChartJs.Blazor](https://github.com/mariusmuntean/ChartJs.Blazor) - Blazor Component that wraps ChartJS.
* [DevExpress Blazor UI Components](https://github.com/DevExpress/RazorComponents) - UI components including Data Grid, Pivot Grid, and several data editors.
* [Elmah.Io.Blazor](https://github.com/elmahio/Elmah.Io.Blazor) - Logs from Blazor to elmah.io using Microsoft.Extensions.Logging.
* [EmbeddedBlazorContent](https://github.com/SamProf/EmbeddedBlazorContent) - Library to load embedded content files (js and css) from Blazor libraries in server-side Blazor mode.
* [Grid.Blazor](https://github.com/gustavnavar/Grid.Blazor) - Grid component for Blazor and Mvc, supporting filtering, sorting and paging.
* [Logging](https://github.com/BlazorExtensions/Logging) - Microsoft Extension Logging implementation for Blazor.
* [MatBlazor](https://github.com/SamProf/MatBlazor) - Material Design components for Blazor. ([Demo](https://www.matblazor.com/)).
* [NObservable](https://github.com/kekekeks/NObservable) - MobX-like observables and component instrumentation.
* [Notifications](https://github.com/BlazorExtensions/Notifications) - HTML5 Notifications API implementation for Microsoft Blazor.
* [SignalR](https://github.com/BlazorExtensions/SignalR) - SignalR Core implementation for Blazor. It uses the JavaScript client.
* [Sotsera.Blazor.Toaster](https://github.com/sotsera/sotsera.blazor.toaster) - A Blazor port of Toastr.js.
* [Storage](https://github.com/BlazorExtensions/Storage) - HTML5 Storage API implementation for Microsoft Blazor.
* [Syncfusion Blazor UI Components](https://github.com/syncfusion/ej2-aspnet-core-blazor-samples) - Robust UI components including [Data Grid](https://ej2.syncfusion.com/aspnet-core-razor-components/Grid/DefaultFunctionalities), [Charts](https://ej2.syncfusion.com/aspnet-core-razor-components/Charts/polar), [Scheduler](https://ej2.syncfusion.com/aspnet-core-razor-components/Schedule/TimelineResourceGroup), [Inputs](https://ej2.syncfusion.com/aspnet-core-razor-components/TextBox/DefaultFunctionalities) and several [Editor](https://ej2.syncfusion.com/aspnet-core-razor-components/RichTextEditor/DefaultFunctionalities) components.
* [Telerik UI for Blazor](https://www.telerik.com/blazor-ui) - A native set of UI components for Blazor, including grid, charting, and calendar components.
* [Toastr](https://github.com/BlazorExtensions/Toastr) - A Blazor port of Toastr.js.
* [Trail](https://nuget.org/packages/Trail) - DSL for writing Blazor markup in F# (with an [adapter](https://nuget.org/packages/Trail.BlazorRedux) for working with BlazorRedux).
* [TwitterShareButton](https://github.com/jsakamoto/Toolbelt.Blazor.TwitterShareButton) - A Tweet Button component for Blazor.
* [WebSocketHelper](https://github.com/Lupusa87/BlazorWebSocketHelper) - Helper for Web Socket in Blazor.

## Videos
* [SPA revolution with WebAssembly and ASP.NET Blazor](https://www.youtube.com/watch?v=_gYgkZ1UBQ4) - April 23, 2019 - DevOneConf 2019 - Rainer Stropek - SPA revolution with WebAssembly and ASP.NET Blazor.
* [ASP.NET Community Standup](https://www.youtube.com/watch?v=ap60h3eQE5Y) - April 16, 2019 - ASP.NET Community Standup - Blazor Updates with Dan Roth and Steve Sanderson.
* [Continuation of the Tulsa .NET User Group website](https://www.twitch.tv/videos/409976640) - April 12, 2019 - Continuation of the Tulsa .NET User Group website. [Source code](https://github.com/devsgarage/tulsa-dnug-website) here.
* [Continuation of the Tulsa .NET User Group website](https://www.twitch.tv/videos/409075153) - April 10, 2019 - Continuation of the Tulsa .NET User Group website. [Source code](https://github.com/devsgarage/tulsa-dnug-website) here.
* [Blazor StateHasChanged: Blazor radio buttons and NuGet packages](https://www.youtube.com/watch?v=GBUGjmZlr7o) - April 9, 2019 - Blazor radio buttons and NuGet packages.
* [What’s Coming with .NET Core 3.0](https://channel9.msdn.com/Events/Visual-Studio/Visual-Studio-2019-Launch-Event/Whats-Coming-with-NET-Core-30) - April 2, 2019 - What’s Coming with .NET Core 3.0.
* [Blazor StateHasChanged: Blazor Shell apps](https://www.youtube.com/watch?v=dNQ7MgPZby4) - March 30, 2019 - Blazor Shell apps.
* [Build amazing web apps with .NET Core](https://channel9.msdn.com/Events/Visual-Studio/Visual-Studio-2019-Launch-Event/VSL107) - March 26, 2019 - Build amazing web apps with .NET Core.
* [ASP.NET Community Standup](https://www.youtube.com/watch?v=WmDXgO0f-MQ) - February 5, 2019 - ASP.NET Community Standup.
* [A New Framework for Browser-based .NET Apps (DevReach 2018)](https://www.youtube.com/watch?v=BnH2h_RJ-d8) - January 14, 2019 - A New Framework for Browser-based .NET Apps (DevReach 2018).
* [Blazor StateHasChanged](https://www.youtube.com/watch?v=sQJfLfA1TQs) - January 7, 2019 - Blazor StateHasChanged using Fluent Validation.
* [What's up with Server Side Blazor?](https://www.youtube.com/watch?v=9QRKjUoA9iY) - December 14, 2018 - ASP.NET Monsters #121: What's up with Server Side Blazor?
* [Razor Components deep dive 1](https://www.youtube.com/watch?v=UzEW0X8a010) - December 5, 2018 - Razor Components deep dive 1, from Edward Charbeneau.
* [Blazor, a New .NET Single Page Application Framework](https://www.youtube.com/watch?v=qrf3OrLHeFI) - November 28, 2018 - Steve Sanderson - Blazor, a New .NET Single Page Application Framework | Øredev 2018.
* [Cascading Parameters in Blazor 0.7.0](https://www.youtube.com/watch?v=J_QZKgBSJBw) - November 24, 2018 - Cascading Parameters in Blazor 0.7.0, by Edward Charbeneau.
* [Blazor File Inputs](https://www.youtube.com/watch?v=-IuZQeZ10Uw) - November 19, 2018 - Blazor File Inputs, by Edward Charbeneau.
* [Visual Studio Toolbox: Blazor Part 2](https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/Blazor-Part-2) - November 8, 2018 - Visual Studio Toolbox: Blazor Part 2.
* [Visual Studio Toolbox: Blazor Part 1](https://blogs.msdn.microsoft.com/robertgreen/2018/11/06/visual-studio-toolbox-blazor-part-1/) - November 6, 2018 - Visual Studio Toolbox: Blazor Part 1.
* [The Blazor Show](https://www.youtube.com/watch?v=wwi55L6Qb18&list=PL1rZQsJPBU2StolNg0aqvQswETPcYnNKL&index=0) - October 9, 2018 - ASP.NET Community Standup - The Blazor Show!
* [Developing amazing web apps with ASP.NET Core](https://myignite.techcommunity.microsoft.com/sessions/65901) - September 28, 2018 - Microsoft Ignite 2018: Developing amazing web apps with ASP.NET Core, by Daniel Roth.
* [Blazor StateHasChanged](https://www.twitch.tv/videos/315855936) - September 28, 2018 - Blazor-Fluxor, Bionic and some live demos of building Blazor Component Templates with Blazor 0.6.0.
* [Blazor StateHasChanged](https://www.twitch.tv/videos/313447722) - September 22, 2018 - Blazor 0.6.0 Templates, Razor Components, Hosting with Azure Static Websites, and some live demos using Blazor Interop and Geolocation services.
* [A fistful of Blazor; Its .NET in the browser](https://www.youtube.com/watch?v=5ztMNdCZrRY) - September 21, 2018 - A fistful of Blazor; Its .NET in the browser by William Tulloch at the NDC Sydney.
* [Blazor: Modern Web development with .NET and WebAssembly](https://channel9.msdn.com/Events/dotnetConf/2018/S207) - September 13, 2018 - Blazor: Modern Web development with .NET and WebAssembly during the .NET Conf 2018.
* [What's New in ASP.NET Core?](https://channel9.msdn.com/Events/dotnetConf/2018/S104) - August 11, 2018 - What's New in ASP.NET Core? (31:30).
* [ASP.NET Community Standup - Aug 7, 2018 - Meet the MVC Team!](https://youtu.be/7Eh_l7jEcCo?t=47m35s) - August 7, 2018 - ASP.NET Community Standup - Aug 7, 2018 - Meet the MVC Team!
* [Bionic - Ionic CLI clone for Blazor](https://www.youtube.com/watch?v=_YRR6L2Pzks) - July 8, 2018 - Bionic - Ionic CLI clone for Blazor ([NuGet package](https://www.nuget.org/packages/Bionic)).
* [ASP.NET Community Standup - Meet the Blazor team!](https://www.youtube.com/watch?v=CWuIz9khK-o) - June 12, 2018 - ASP.NET Community Standup - June 12, 2018 - Meet the Blazor team.
* [Blazor, a new .NET SPA framework](https://www.youtube.com/watch?v=JU-6pAxqAa4) - May 7, 2018 - Presentation of Blazor by Steve Sanderson at the NDC Minnesota.
* [.NET Overview & Roadmap](https://channel9.msdn.com/Events/Build/2018/BRK2100) - May 7, 2018 - .NET Overview & Roadmap (at 1:14:00).
* [What's new in Web Development with ASP.NET Core 2.1](https://channel9.msdn.com/Events/Build/2018/BRK2151) - May 6, 2018 - What's new in Web Development with ASP.NET Core 2.1 (Blazor part starts at 1:08:57).
* [Develop ASP.NET Blazor Apps in a Docker Container](https://www.youtube.com/watch?v=jGyFKH5y6LA) - April 26, 2018 - Develop ASP.NET Blazor Apps in a Docker Container, from Coding Blocks.
* [ASP.NET Community Standup - Blazor Update with Dan Roth and Steve Sanderson](https://www.youtube.com/watch?v=_b_fUq5DU0U) - April 3, 2018 - ASP.NET Community Standup - Blazor Update with Dan Roth and Steve Sanderson.
* [WebAssembly and Blazor - .NET Concept of the Week - Episode 9](https://www.youtube.com/watch?v=5HSKDGHijdI) - March 4, 2018 - WebAssembly and Blazor - .NET Concept of the Week - Episode 9.
* [Exploring ASP.NET Blazor](https://www.youtube.com/watch?v=VGotz89_iTY) - Feb 10, 2018 - Exploring ASP.NET Blazor! with Jeffrey T. Fritz.
* [ASP.NET Community Standup](https://www.youtube.com/watch?v=Ta_qXpXQqGQ) - Feb 6, 2018 - ASP.NET Community Standup - Blazor Update.
* [Web Apps can’t really do that, can they? - Steve Sanderson](https://www.youtube.com/watch?v=MiLAE6HMr10&feature=youtu.be&t=31m45s) - July 10, 2017 - Web Apps can’t really do that, can they? - Steve Sanderson.

## Articles
* [Get Some Sass Into Your Blazor App](https://chrissainty.com/get-some-sass-into-your-blazor-app/) - May 1, 2019 - Get Some Sass Into Your Blazor App.
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
* [From Angular to Blazor: The Health App](https://blog.jeremylikness.com/from-angular-to-blazor-the-health-app-2e36077d641c) - January 3, 2019 - From Angular to Blazor: The Health App.
* [An Introduction to Templated Components in Blazor](https://visualstudiomagazine.com/articles/2018/12/01/blazor-templated-components.aspx) - January 3, 2019 - An Introduction to Templated Components in Blazor.
* [Blazor StateHasChanged()](https://edcharbeneau.com/blazor-statehaschanged-113018) - December 14, 2018 - Blazor StateHasChanged().
* [Create Blazor Nuget Package With Azure Devops](https://remibou.github.io/Create-Blazor-Nuget-package-with-Azure-DevOps/) - December 14, 2018 - Create Blazor Nuget Package With Azure Devops.
* [How To Publish A Blazor Component To Nuget Gallery](https://medium.com/swlh/how-to-publish-a-blazor-component-to-nuget-gallery-850d6d1dd37d?WT.mc_id=link-twitter-jeliknes) - December 10, 2018 - How To Publish A Blazor Component To Nuget Gallery.
* [An Ad Hoc Approach to Passing Elements from Blazor to JavaScript](https://visualstudiomagazine.com/blogs/tool-tracker/2018/11/an-ad-hoc-approach.aspx?ajs_uid=5801H8419578J3Z) - December 6, 2018 - An Ad Hoc Approach to Passing Elements from Blazor to JavaScript.
* [Architecting Blazor (and Integrating JavaScript)](https://visualstudiomagazine.com/articles/2018/11/01/architecting-blazor.aspx) - December 4, 2018 - Architecting Blazor (and Integrating JavaScript), from the Visual Studio Magazine.
* [Simple localisation in Blazor](https://chrissainty.com/simple-localisation-in-blazor) - December 3, 2018 - Simple localisation in Blazor.
* [BlazorGrid – A Reusable Grid Component For Blazor](https://ankitsharmablogs.com/blazorgrid-reusable-grid-component-for-blazor/) - December 2, 2018 - BlazorGrid – A Reusable Grid Component For Blazor
* [Visual Studio Code gears up for Blazor](https://visualstudiomagazine.com/articles/2018/11/30/vs-code-blazor.aspx) - November 30, 2018 - Visual Studio Code gears up for Blazor.
* [Validate Request With Recaptcha On A Blazor App And Mediatr](https://remibou.github.io/Validate-request-with-reCaptcha-on-a-Blazor-app-and-MediatR/) - November 24, 2018 - Validate Request With Recaptcha On A Blazor App And Mediatr.
* [Validation Controls using Blazor - Basic Validation Controls](http://www.hishambinateya.com/part1-validation-controls-using-blazor-basic-validation-controls) - November 20, 2018 - Part I: Validation Controls using Blazor - Basic Validation Controls.
* [Blazor StateHasChanged()](https://edcharbeneau.com/blazor-statehaschanged-111618) - November 16, 2018 - Blazor StateHasChanged().
* [Share Blazor Components with Shared Class Libraries](https://daveabrock.com/2018/11/11/using-blazor-shared-libraries/) - November 11, 2018 - Share Blazor Components with Shared Class Libraries.
* [Adding Blazor to existing HTML+JavaScript pages](https://visualstudiomagazine.com/articles/2018/10/01/adding-blazor.aspx) - November 2, 2018 - Adding Blazor to existing HTML+JavaScript pages.
* [Blazor: Working with Events](https://visualstudiomagazine.com/articles/2018/10/01/blazor-event-handling.aspx) - October 31, 2018 - Blazor: Working with Events, by Visual Studio Magazine.
* [Implementing server side CosmosDB pagination in a Blazor Web App](https://chapsas.com/implementing-skiptake-server-side-cosmosdb-pagination-in-a-blazor-web-app/) - October 31, 2018 - Implementing server side CosmosDB pagination in a Blazor Web App (Part 1: Page Number and Page Size).
* [Blazor Q&A with Microsoft's Daniel Roth](https://www.telerik.com/blogs/blazor-qa-with-microsofts-daniel-roth) - October 25, 2018 - Blazor Q&A with Microsoft's Daniel Roth.
* [Building offline Blazor application](https://gunnarpeipman.com/aspnet/offline-blazor-application) - October 24, 2018 - Building offline Blazor application.
* [Service lifetimes in Blazor](https://chrissainty.com/service-lifetimes-in-blazor/) - October 22, 2018 - Service lifetimes in Blazor.
* [Pages in ASP .NET Core: Razor, Blazor and MVC Views](https://wakeupandcode.com/pages-in-asp-net-core-razor-blazor-and-mvc-views/) - October 21, 2018 - Pages in ASP .NET Core: Razor, Blazor and MVC Views.
* [Server-side Blazor applications](https://gunnarpeipman.com/aspnet/server-side-blazor/) - October 19, 2018 - Server-side Blazor applications.
* [Building a blogging app with Blazor: adding authentication](https://chrissainty.com/building-a-blogging-app-with-blazor-adding-authentication/) - October 15, 2018 - Building a blogging app with Blazor: adding authentication.
* [Get Started with Blazor and WebAssembly](https://developer.okta.com/blog/2018/10/15/blazor-and-web-assembly) - October 15, 2018 - Get Started with Blazor and WebAssembly.
* [A nicer looking Blazor loading page](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/4315/A-Nicer-Looking-Blazor-Loading-Page.aspx) - October 14, 2018 - A nicer looking Blazor loading page.
* [Deploying a Blazor Application on Azure](https://dzone.com/articles/deploying-a-blazor-application-on-azure) - October 12, 2018 - Deploying a Blazor Application on Azure.
* [A Blazor Tip You Should Almost Certainly Ignore](https://visualstudiomagazine.com/blogs/tool-tracker/2018/10/blazor-tip.aspx) - October 10, 2018 - A Blazor Tip You Should Almost Certainly Ignore.
* [Building Blazor apps with SignalR Core](https://dotnetthoughts.net/building-blazor-apps-with-signalr/) - October 3, 2018 - Building Blazor apps with SignalR Core.
* [Server-Side Blazor to ship in .NET Core 3.0](https://visualstudiomagazine.com/articles/2018/10/03/blazor-update.aspx) - October 3, 2018 - Server-Side Blazor to ship in .NET Core 3.0.
* [Blazor 0.6.0 experimental release now available](https://blogs.msdn.microsoft.com/webdev/2018/10/02/blazor-0-6-0-experimental-release-now-available/) - October 2, 2018 - Blazor 0.6.0 experimental release now available.
* [Integrating JavaScript and C# in the Browser: Beyond the Basics with Blazor](https://visualstudiomagazine.com/articles/2018/09/01/integrating-javascript-csharp.aspx) - October 1, 2018 - Integrating JavaScript and C# in the Browser: Beyond the Basics with Blazor.
* [Cutting Edge - Blazor at Work: Events, Binding and Composition](https://msdn.microsoft.com/magazine/mt830361) - October 1, 2018 - Cutting Edge - Blazor at Work: Events, Binding and Composition.
* [Work with Cassandra API in Cosmos DB](https://www.c-sharpcorner.com/article/blazor-work-with-cassandra-api-in-cosmos-db/) - October 1, 2018 - Work with Cassandra API in Cosmos DB.
* [Blazor - .NET in the browser](https://www.dotnetcurry.com/dotnet/1460/blazor-getting-started) - September 27, 2018 - Blazor - .NET in the browser.
* [Building a blogging app with Blazor: Editing & Deleting Posts](https://chrissainty.com/building-a-blogging-app-with-blazor-editing-deleting-posts/) - September 24, 2018 - Building a blogging app with Blazor: Editing & Deleting Posts.
* [Data Driven Layout in Server-side Blazor](https://hutchcodes.net/2018/09/data-driven-layout-in-razor-components/) - September 24, 2018 - Data Driven Layout in Server-side Blazor.
* [Building a blogging app with Blazor: add post](https://chrissainty.com/building-a-blogging-app-with-blazor-add-post/) - September 18, 2018 - Building a blogging app with Blazor: add post.
* [Dependency Injection Lifetimes in Blazor](https://hutchcodes.net/2018/09/dependency-injection-lifetimes-in-razor-components/) - September 17, 2018 - Dependency Injection Lifetimes in Blazor.
* [How to Consume Web APIs in Blazor](https://visualstudiomagazine.com/articles/2018/09/07/blazor-apis.aspx) - September 13, 2018 - How to Consume Web APIs in Blazor.
* [Integrating Stripe Payment In With Blazor And Aspnet Core](https://remibou.github.io/Integrating-Stripe-payment-in-with-Blazor-and-ASPNET-Core/) - September 11, 2018 - Integrating Stripe Payment In With Blazor And Aspnet Core.
* [Working with the Blazor JavaScript Interop](https://blog.logrocket.com/working-with-the-blazor-javascript-interop-3c2a8d0eb56c) - September 5, 2018 - Working with the Blazor JavaScript Interop.
* [Cutting Edge - Never Mind JavaScript, Here’s Blazor](https://msdn.microsoft.com/magazine/mt829756) - September 4, 2018 - Cutting Edge - Never Mind JavaScript, Here’s Blazor, published on Microsoft Magazine.
* [Web Development - C# in the Browser with Blazor](https://msdn.microsoft.com/fr-fr/magazine/mt829752) - September 4, 2018 - Web Development - C# in the Browser with Blazor, published on Microsoft Magazine.
* [Building a blogging app with Blazor: Listing Posts](https://chrissainty.com/building-a-blogging-app-with-blazor-listing-posts/) - September 3, 2018 - Building a blogging app with Blazor: Listing Posts.
* [Blazor: .NET in the browser](https://dncmagazine.blob.core.windows.net/edition38/DNCMag-Issue38.pdf) - September 1, 2018 - Blazor: .NET in the browser, from DNC Magazine.
* [Integrating Blazor and JavaScript Code](https://visualstudiomagazine.com/articles/2018/08/01/integrating-blazor-javascript.aspx) - August 27, 2018 - Integrating Blazor and JavaScript Code.
* [Building a blogging app with Blazor: Getting Setup](https://chrissainty.com/building-a-blogging-app-with-blazor-getting-setup/) - August 27, 2018 - Building a blogging app with Blazor: Getting Setup.
* [Client side validation with Blazor and System.DataAnnotation](https://remibou.github.io/Client-side-validation-with-Blazor-and-Data-Annotations/) - August 23, 2018 - Client side validation with Blazor and System.DataAnnotation.
* [Writing a Blazor app](https://davidpine.net/blog/blazing-chuck/) - August 20, 2018 - Writing a Blazor app.
* [Localizing DateTime (and numbers) in Blazor](https://remibou.github.io/Localizing-DateTime-in-Blazor/) - August 17, 2018 - Localizing DateTime (and numbers) in Blazor.
* [Introduction to Server-side Blazor aka Razor Components](https://chrissainty.com/introduction-to-server-side-blazor-aka-razor-components/) - August 11, 2018 - Introduction to Server-side Blazor aka Razor Components.
* [I18n With Blazor And Aspnet Core](https://remibou.github.io/I18n-with-Blazor-and-ASPNET-Core/) - August 11, 2018 - Internationalizing a Blazor App with ASPNET Core as backend service.
* [WebAssembly](https://davidpine.net/blog/webassembly-interview/) - August 5, 2018 - Interview with Steve Sanderson (Talking Blazor).
* [Web Assembly and Blazor: Re-assembling the Web](https://weblog.west-wind.com/posts/2018/Jul/31/Web-Assembly-and-Blazor-Reassembling-the-Web) - July 31, 2018 - Web Assembly and Blazor: Re-assembling the Web.
* [Understanding Server-Side Blazor](https://www.c-sharpcorner.com/article/understanding-server-side-blazor/) - July 29, 2018 - Understanding Server-Side Blazor.
* [Blazor 0.5.0 experimental release now available](https://blogs.msdn.microsoft.com/webdev/2018/07/25/blazor-0-5-0-experimental-release-now-available/) - July 25, 2018 - Blazor 0.5.0 experimental release now available.
* [CSRF protection with ASPNET Core and Blazor](https://remibou.github.io/CSRF-protection-with-ASPNET-Core-and-Blazor-Week-29/) - July 22, 2018 - CSRF protection with ASPNET Core and Blazor.
* [Blazor for Knockout.js Developers](https://blog.usejournal.com/blazor-for-knockout-js-developers-bfeefaacffc3) - July 20, 2018 - A brief comparison between two of Steve Sanderson’s Creations.
* [Uploading a file in a Blazor app](https://remibou.github.io/Upload-file-with-Blazor/) - July 12, 2018 - Uploading a file in a Blazor app.
* [Adding search to Blazor applications](https://gunnarpeipman.com/search2/blazor-search/) - July 11, 2018 - Adding search to Blazor applications.
* [SPA framework on .Net via WebAssembly](https://koukia.ca/blazor-spa-framework-on-net-via-webassembly-b7a0046e7f21) - July 10, 2018 - SPA framework on .Net via WebAssembly.
* [ASP.NET Core Blazor CRUD](https://code.msdn.microsoft.com/vstudio/ASPNET-Core-Blazor-122b108a) - July 9, 2018 - ASP.NET Core Blazor Master/Detail CRUD with Filtering and Sorting using EF.
* [Improved Cascading Dropdowns With Blazor](https://www.mikesdotnetting.com/article/320/improved-cascading-dropdowns-with-blazor) - July 5, 2018 - Improved Cascading Dropdowns With Blazor.
* [Hosting a Blazor App in Azure Storage Static Websites](https://anthonychu.ca/post/blazor-azure-storage-static-websites/) - June 28, 2018 - Hosting a Blazor App in Azure Storage Static Websites.
* [Implementing Google OAuth with Blazor](https://remibou.github.io/Google-OAuth-with-Blazor-ASPNET-Core-Week-26/) - June 28, 2018 - Implementing Google OAuth with Blazor (0.4) and ASPNET Core 2.1.1.
* [Web Assembly, Blazor and the future of Web Development](https://medium.com/@ZombieCodeKill/web-assembly-blazor-and-the-future-of-web-development-c240fbe5e5be) - June 25, 208 - Web Assembly, Blazor and the future of Web Development.
* [Hosting Blazor on Netlify](https://mattferderer.com/host-blazor-on-netlify) - Hosting Blazor on Netlify.
* [Who is Blazor for Exactly?](https://wildermuth.com/2018/06/13/Who-is-Blazor-for-Exactly) - June 13, 208 - Who is Blazor for Exactly?
* [Blazor 0.4.0 experimental release now available](https://blogs.msdn.microsoft.com/webdev/2018/06/07/blazor-0-4-0-experimental-release-now-available/) - June 7, 2018 - Blazor 0.4.0 experimental release now available.
* [Blazor Update Boosts .NET/JavaScript Interoperability](https://visualstudiomagazine.com/articles/2018/06/08/blazor-0-4-0.aspx) - June 8, 2018 - Blazor Update Boosts .NET/JavaScript Interoperability.
* [An Introduction to Blazor](https://remibou.github.io/An-Introduction-to-Blazor-Week-22/) - June 5, 2018 - An Introduction to Blazor.
* [Creating an SPA Using Razor Pages With Blazor](https://medium.freecodecamp.org/how-to-create-a-single-page-application-using-razor-pages-with-blazor-9d010fd6be45) - June 4, 2018 - Creating an SPA Using Razor Pages With Blazor ([Article on FreeCodeCamp](https://medium.freecodecamp.org/how-to-create-a-single-page-application-using-razor-pages-with-blazor-9d010fd6be45) - [Article on DZone](https://dzone.com/articles/creating-an-spa-using-razor-pages-with-blazor)).
* [Cascading DropDownList in Blazor Using EF Core](http://ankitsharmablogs.com/cascading-dropdownlist-in-blazor-using-ef-core/) - May 14, 2018 - Creating a cascading dropdown list in Blazor using Entity Framework Core database first approach.
* [Deploying a Blazor Application on IIS](http://ankitsharmablogs.com/deploying-a-blazor-application-on-iis/) - May 14, 2018 - Deploying an ASP.NET Core hosted Blazor application with the help of IIS 10 on a Windows 10 machine.
* [Blazor Steals the Show in VSLive!](https://visualstudiomagazine.com/articles/2018/05/03/vslive-austin.aspx) - May 3, 2018 - Blazor Steals the Show in VSLive! .NET Keynote.
* [Blazor 0.3.0 experimental release now available](https://blogs.msdn.microsoft.com/webdev/2018/05/02/blazor-0-3-0-experimental-release-now-available/) - May 2, 2018 - Blazor 0.3.0 experimental release now available.
* [Blazor, Razor, WebAssembly, and Mono](https://daveaglick.com/posts/blazor-razor-webassembly-and-mono) - April 24, 2018 - Blazor, Razor, WebAssembly, and Mono, How the pieces fit together.
* [BlazeDown with Blazor](http://edcharbeneau.com/blazedown-with-blazor) - April 20, 2018 - BlazeDown with Blazor (Blazor + Markdown = BlazeDown!).
* [Blazor 0.2.0 release now available](https://blogs.msdn.microsoft.com/webdev/2018/04/17/blazor-0-2-0-release-now-available/) - April 18, 2018 - Blazor 0.2.0 release now available.
* [ASP.NET Core – CRUD Using Blazor And Entity Framework Core](http://ankitsharmablogs.com/asp-net-core-crud-using-blazor-and-entity-framework-core/) - April 9, 2018 - Creating a web application using Blazor with the help of Entity Framework Core.
* [Using C# await against JS Promises in Blazor](https://joonasw.net/view/csharp-await-and-js-promises-in-blazor) - April 7, 2018 - Using C# await against JS Promises in Blazor.
* [Create a CRUD App using Blazor and ASP.NET Core](http://www.talkingdotnet.com/create-a-crud-app-using-blazor-and-asp-net-core/) - April 5, 2018 - Create a CRUD App using Blazor and ASP.NET Core.
* [Blazor – You Want To Run .NET Where?!](https://dotnetcore.gaprogman.com/2018/04/05/blazor-you-want-to-run-net-where/) - April 5, 2018 - Blazor – You Want To Run .NET Where?!
* [What is Blazor and why is it so exciting?](https://chrissainty.com/what-is-blazor-and-why-is-it-so-exciting/) - March 24, 2018 - What is Blazor and why is it so exciting?
* ['Death to JavaScript!' Blazor, for .NET Web Apps Using WebAssembly, Goes Alpha](https://visualstudiomagazine.com/articles/2018/03/23/blazor-alpha.aspx) - March 23, 2018 - 'Death to JavaScript!' Blazor, for .NET Web Apps Using WebAssembly, Goes Alpha.
* [Get started building .NET web apps that run in the browser with Blazor](https://blogs.msdn.microsoft.com/webdev/2018/03/22/get-started-building-net-web-apps-in-the-browser-with-blazor/) - March 22, 2018 - Get started building .NET web apps that run in the browser with Blazor.
* [Blazor and .NET Core hosting – the future’s bright](http://blog.tdwright.co.uk/2018/03/05/blazor-and-net-core-hosting-the-futures-bright) - March 5, 2018 - Blazor and .NET Core hosting – the future’s bright.
* [Blazor: a web UI framework running C# and .NET in the browser](https://www.oxfordcc.co.uk/blog/blazor-a-web-ui-framework-running-csharp-and-dotnet-in-the-browser) - February 8, 2018 - Blazor: a web UI framework running C# and .NET in the browser.
* [A new experiment: Browser-based web apps with .NET and Blazor](https://blogs.msdn.microsoft.com/webdev/2018/02/06/blazor-experimental-project/) - February 6, 2018 - A new experiment: Browser-based web apps with .NET and Blazor.
* [Blazor: a technical introduction](http://blog.stevensanderson.com/2018/02/06/blazor-intro/) - February 6, 2018 - Blazor: a technical introduction.
* [Running Blazor on Mono in the browser](http://blog.stevensanderson.com/2017/11/05/blazor-on-mono/) - November 5, 2017 - Running Blazor on Mono in the browser.
* [.NET and WebAssembly - Is this the future of the front-end?](https://www.hanselman.com/blog/NETAndWebAssemblyIsThisTheFutureOfTheFrontend.aspx) - August 12, 2017 - .NET and WebAssembly - Is this the future of the front-end?
  
## Podcasts
* [The Cynical Developer - Blazor](https://cynicaldeveloper.com/podcast/108) - February 18, 2019 - Episode 108 of The Cynical Developer - Blazor.
* [Blazor in 2019 with Steve Sanderson and Dan Roth](https://player.fm/series/net-rocks-2353294/blazor-in-2019-with-steve-sanderson-and-dan-roth) - February 14, 2019 - .NET Rocks, Blazor in 2019 with Steve Sanderson and Dan Roth.
* [SDN Cast #118 - With Rainer Stropek and Serverside Blazor!](https://www.youtube.com/watch?v=S66mK_30gPE) - November 8, 2018 - Weekly SDN Cast with special gues Rainer Stropek talking about and showing off Blazor!
* [Ed Charbeneau on Blazor](https://crosscuttingconcerns.com/Podcast-099-Ed-Charbeneau-Blazor) - September 17, 2018 - Ed Charbeneau on Blazor.
* [Blazor brings .NET to Web Assembly with Steve Sanderson](https://hanselminutes.com/642/blazor-brings-net-to-web-assembly-with-steve-sanderson) - July 26, 2018 - Blazor brings .NET to Web Assembly with Steve Sanderson.
* [Episode 037 – Blazor with Daniel Roth](https://6figuredev.com/podcast/episode-037-blazor-with-daniel-roth/) - April 30, 2018 - Episode 037 – Blazor with Daniel Roth.
* [MS Dev Show : Blazor](https://www.youtube.com/watch?v=xJtpYsVRggE) - March 19, 2018 - MS Dev Show Episode 184: Blazor (.NET in WebAssembly) with Dan Roth & Steve Sanderson.
* [.NET Rocks, WebAssembly and Blazor with Steve Sanderson](https://www.dotnetrocks.com/?show=1455) - July 4, 2017 - .NET Rocks 1455, WebAssembly and Blazor with Steve Sanderson.
* [Inside WebAssembly with Mozilla Fellow David Bryant](https://hanselminutes.com/581/inside-webassembly-with-mozilla-fellow-david-bryant) - May 25, 2017 - Inside WebAssembly with Mozilla Fellow David Bryant.

## Tooling
* [ASP.NET Core Blazor Language Services](https://marketplace.visualstudio.com/items?itemName=aspnet.blazor) - Provides Visual Studio support for ASP.NET Core Blazor.
* [BlazorFiddle](https://blazorfiddle.com) - Blazor .Net Developer Playground and Code Editor in the Browser.
* [Blazor Minimum Project Templates](https://github.com/jsakamoto/BlazorMinimumTemplates) - A project templates package of Blazor apps without JavaScript and CSS libraries.
* [Blazor Snippets Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=ScottSauber.blazorsnippets) - A Visual Studio Code extension that offers Blazor and Razor snippets.
* [BlazorSourceMangler](https://github.com/Lupusa87/BlazorSourceMangler) - A console app to mangle blazor dlls. Check this [YouTube video](https://www.youtube.com/watch?v=nlXax81b1UE) for more details. You can also check this [Blazor TODO app](https://lupblazortodo.z20.web.core.windows.net/) to see result of this app (downloaded blazortodos.dll is mangled and decompilation shows uglyfied code).
* [.NET Core](https://www.microsoft.com/net/download/dotnet-core) - .NET Core.
* [Razor+ Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=austincummings.razor-plus) - A Visual Studio Code extension that offers improved Razor support.
* [Visual Studio](https://www.visualstudio.com/vs/preview) - Latest preview of Visual Studio.
* [Visual Studio Code](https://code.visualstudio.com/) - Visual Studio Code, free, open source and cross-platform code editor.

## Books
* [Blazor Revealed](https://www.apress.com/gp/book/9781484243428) - Blazor Revealed, Building Web Applications in .NET(Published February, 2019).
* [Blazor Quick Start Guide: Build web applications using Blazor, EF Core, and SQL Server](https://www.amazon.in/gp/product/178934414X/ref=awesome_blazor) - Blazor Quick Start Guide: Build web applications using Blazor, EF Core, and SQL Server (Published October 31, 2018).

## E-Books
* [Dockerizing ASP.NET Core and Blazor Applications on Mac](https://www.c-sharpcorner.com/ebooks/dockerizing-asp-net-core-and-blazor-applications-on-mac) - Dockerizing ASP.NET Core and Blazor Applications on Mac (Published October 30, 2018).

## Courses
* [Blazor First Look on LinkedIn Learning](https://www.linkedin.com/learning/blazor-first-look) - Blazor First Look on LinkedIn Learning. [Source code](https://github.com/Dedac/Beam).
* [Free Blazor Training Course](https://www.devexpress.com/support/training/blazor/) - DevExpress Blazor free training course [Source code](https://github.com/DevExpress/blazor-training-samples).
  
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

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Adrien Torris has waived all copyright and related or neighboring rights to this work.
