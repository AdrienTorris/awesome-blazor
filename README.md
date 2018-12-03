# Awesome Blazor [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A collection of awesome Blazor resources.

Inspired by [awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet) and [awesome-dotnet-core](https://github.com/thangchung/awesome-dotnet-core).

Contributions are always welcome! 

## Contents
* [Introduction](#introduction)
* [General](#general)
* [Demos](#demos)
* [Sample Projects](#sample-projects)
* [Extensions](#extensions)
* [Libraries](#libraries)
* [Videos](#videos)
* [Articles](#articles)
* [Podcasts](#podcasts)
* [Tooling](#tooling)
* [Books](#books)
* [Courses](#courses)
* [Community](#community)
* [Contributing](#contributing)

## Introduction
### What is Blazor?
Blazor is an experimental .NET web framework using C#/Razor and HTML that runs in the browser with WebAssembly.

### Warning
Blazor is a really early-stage project, it's not a mature technology and it's absolutely not production-ready.

### Requirements
Please note that if you want to open Blazor projects in Visual Studio, you must have [Visual Studio 15.7 Preview 1](https://www.visualstudio.com/vs/preview/) or later and the [.NET Core 2.1 Preview 1 SDK](https://www.microsoft.com/net/download/dotnet-core/sdk-2.1.300-preview1).

## General
* [ASP.NET Blog](https://blogs.msdn.microsoft.com/webdev/category/blazor/) Blazor topic on the ASP.NET blog.
* [Blazor.net](http://blazor.net/) Blazor.net, official documentation website.
* [Blazor bites](https://codedaze.io/tag/blazor-bites/) Blazor bites serie on codedaze.io.
* [Blazor-Dev gallery on .NET Foundation](https://dotnet.myget.org/gallery/blazor-dev) Daily builds of the 'dev' branch of Blazor.
* [Blazor Extensions](https://github.com/BlazorExtensions) Curated extensions for Microsoft ASP.Net Core Blazor.
* [FAQ](https://github.com/aspnet/Blazor/wiki/FAQ) FAQ.
* [GitHub repository](https://github.com/aspnet/Blazor) The official Blazor repository.
* ['Hello World' sample](https://github.com/dodyg/practical-aspnetcore/tree/master/projects/blazor) 'Hello World' sample.
* [Introduction to ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/) Introduction to ASP.NET Core.
* [Learn Blazor](https://learn-blazor.com) An unofficial documentation website ([source code here](https://github.com/software-architects/learn-blazor)).

## Demos
* [BlazorCalculator](https://lupblazordemos.z13.web.core.windows.net/CalculatorPage) Simple calculator with history and ability to use previous results in new calculations.
* [BlazorChess](https://lupblazordemos.z13.web.core.windows.net/ChessPage) Chess engine implemented with Blazor.
* [BlazorClockCanvas](https://lupblazordemos.z13.web.core.windows.net/ClockCanvas) Password pattern based on SVG.
* [BlazorClockSVG](https://lupblazordemos.z13.web.core.windows.net/) Complex clock based on SVG.
* [BlazeDown](http://edcharbeneau.com/BlazeDown) BlazeDown, online Markdown editor.
* [BlazorGameSnake](https://lupblazordemos.z13.web.core.windows.net/GameSnakePage) 2D game snake with customizations, path finding algorithm, and sound effects using SVG.
* [BlazorPasswordPattern](https://lupblazordemos.z13.web.core.windows.net/PasswordPatternPage) Password pattern based on SVG.
* [BlazorRawHtmlRenderer](https://lupblazordemos.z13.web.core.windows.net/RawHTML) Raw HTML rendering with Blazor.
* [Blazorships](http://blazorships.azurewebsites.net) Blazorships, a Blazor implementation of Battleship using SignalR.
* [Demo](https://blazor-demo.github.io/) Official demo website.
* [Flight Finder](http://blazor-flight-finder.azurewebsites.net/) Flight Finder.
* [Money](http://money.neptuo.com) Money.
* [RealWorld demo](https://blazor-realworld.azurewebsites.net/) RealWorld demo website.
* [VocaDB lyrics display](https://lyrics-proto.vocadb.net/) VocaDB lyrics display.

## Sample Projects
* [ASP.NET Core Blazor CRUD](https://code.msdn.microsoft.com/vstudio/ASPNET-Core-Blazor-122b108a) ASP.NET Core Blazor Master/Detail CRUD with Filtering and Sorting using EF.
* [AsteroidsWasm](https://github.com/aesalazar/AsteroidsWasm) A mixed bag of C# projects to see if a single .NET Standard base can run across all common platforms include WebAssembly.
* [Beam](https://github.com/Dedac/Beam) A social network demo application. This is the source code of the LinkedIn course "Blazor First Look".
* [Blangular](https://github.com/danroth27/Blangular) Blazor + Angular, by Daniel Roth.
* [BlazorAzureSignalRService](https://github.com/danroth27/BlazorAzureSignalRService) Blazor + Azure SignalR Service.
* [BlazeDown](https://github.com/EdCharbeneau/BlazeDown) BlazeDown, online Markdown editor.
* [BlazorBinding](https://github.com/SQL-MisterMagoo/BlazorBinding) Sample Blazor App demonstrating various data binding scenarios.
* [BlazorBricks](https://www.codeproject.com/Articles/1241210/WebAssembly-with-Blazor) BlazorBricks, a Blazor implementation of the game Tetris.
* [BlazorCalculator](https://github.com/Lupusa87/BlazorCalculator) Simple calculator with history and ability to use previous results in new calculations.
* [BlazorChat](https://github.com/danroth27/BlazorChat) Real-time chat app using ASP.NET Core and Blazor, from Daniel Roth.
* [BlazorChatSample](https://github.com/conficient/blazorchatsample) Blazor chat demo using SignalR JS client with interop.
* [BlazorChess](https://github.com/Lupusa87/BlazorChess) Chess engine implemented with Blazor.
* [BlazorClockCanvas](https://github.com/Lupusa87/BlazorClockCanvas) Complex clock based on Canvas.
* [BlazorClockSVG](https://github.com/Lupusa87/BlazorClockSVG) Complex clock based on SVG.
* [Blazor.DataDrivenLayout](https://github.com/hutchcodes/Blazor.DataDrivenLayout) Two example of how to do data driven layouts in Server-side Blazor.
* [BlazorElectronExperiment](https://github.com/SteveSandersonMS/BlazorElectronExperiment.Sample) Exploring how a Blazor could be used to build a cross-platform desktop application using [Electron](https://electronjs.org/).
* [BlazorFileReader](https://github.com/Tewr/BlazorFileReader) Read-only File streams in Blazor. [Demo](https://tewr.github.io/BlazorFileReader/).
* [BlazorGameSnake](https://github.com/Lupusa87/BlazorGameSnake) 2D game snake with customizations, path finding algorithm, and sound effects using SVG.
* [BlazorGeolocation](https://github.com/EdCharbeneau/BlazorGeolocation) An example of using Geolocation with Blazor.
* [BlazorGraphExample](https://github.com/jburman/BlazorGraphExample) Example application for connecting to Graph API from Blazor.
* [BlazorNasaImages](https://github.com/ncarandini/BlazorNasaImages) A sample Blazor app that fetches the Nasa Astronomy Picture of the Day.
* [BlazorPasswordPattern](https://github.com/Lupusa87/BlazorPasswordPattern) Password pattern based on SVG.
* [BlazorPong](https://github.com/ctrl-alt-d/blazorpong) 8 bits pong with blazor and signalR. Warning: Blazor Pong is not finished and is stopped with a knowed SignalR issue with Blazor, more info [here](https://github.com/AdrienTorris/awesome-blazor/pull/19).
* [BlazorQuiz](https://github.com/Amine-Smahi/BlazorQuiz) Simple quiz using Blazor.NET and Webassembly.
* [BlazorRawHtmlRenderer](https://github.com/Lupusa87/BlazorRawHtmlRenderer) Raw HTML rendering with Blazor.
* [BlazorServerTree](https://github.com/ctrl-alt-d/BlazorServerTree) A simple Server-Side Blazor sample app to deal with hierarchical data.
* [Blazorships](https://github.com/bjorndaniel/Blazorships) Blazorships, a Blazor implementation of Battleship using SignalR.
* [BlazorSignalRTest](https://github.com/danroth27/BlazorSignalRTest) Test with Blazor and SignalR.
* [Blazor Summernote](https://github.com/shawty/blazor.summernote) Wrapper for the new MS Blazor framework, allowing the use of the Summernote Wysiwyg editor in a form.
* [Blazor Survey](https://github.com/nutshellit/Blazor-Survey) A hybrid F#/C# blazor sample app to kick the tyres of blazor.
* [BlazorTasks](https://github.com/BorowskiKamil/blazor-tasks) To-Do App.
* [Blazor.Toaster](https://github.com/sotsera/sotsera.blazor.toaster) A Blazor port of Toastr.js.
* [Blazor Tree CRUD](https://github.com/ctrl-alt-d/TreeCrud) CRUD operations with hierarchical data. Blazor Server + GraphQL + EF.
* [Blazor.Universal](https://github.com/pushqrdx/Blazor.Universal) Example of using Blazor to build Xamarin based UWP application without WebAssembly.
* [Blazor.Xamarin](https://github.com/Appizeo/Blazor.Xamarin) A Xamarin template for launch and interop a Blazor app on mobile.
* [Blazume](https://github.com/Amine-Smahi/Blazume) A simple portfolio/Resume template using Blazor.
* [CRUD sample with EF](https://code.msdn.microsoft.com/vstudio/ASPNET-Core-Blazor-122b108a) ASP.NET Core Blazor Master/Detail CRUD with Filtering and Sorting using EF.
* [Demo](https://github.com/blazor-demo/blazor-demo.github.io) Code of the official demo website.
* [Do](https://github.com/jamie-lord/do) To Do app.
* [Flight Finder](https://github.com/aspnet/samples/tree/master/samples/aspnetcore/blazor) Flight Finder.
* [Hacker News Clone](https://github.com/lohithgn/blazor-hackernews-clone) Hacker News Clone.
* [KendoBlazorPoc](https://github.com/ivanchev/KendoBlazorPoc) Kendo UI wrapped inside Blazor components.
* [Money](https://github.com/maraf/Money) Money.
* [Randify](https://github.com/tinyioda/Randify) Spotify Playlist randomizer.
* [Realworld](https://github.com/torhovland/blazor-realworld-example-app) Blazor realworld example app.
* [RxBlazor](https://github.com/bmsantos/RxBlazor) Rx.NET based MessageService demo for Blazor Framework.
* [SitecoreBlazor](https://github.com/GoranHalvarsson/SitecoreBlazor) Sitecore + Blazor.
* [Tour of Heroes](https://github.com/lohithgn/blazor-tour-of-heroes) Blazor implementation of Angular Tour of Heroes.
* [Toss.Blazor](https://github.com/RemiBou/Toss.Blazor) Twitter-like web application using Blazor.
* [TrendTv](https://github.com/MattMarked/TrendTv) Fetch video list from youtube and "zap" in real time between trending videos, filtered by country or category.
* [VocaDB lyrics](https://github.com/riipah/vocadb-lyrics-blazor-proto) VocaDB lyrics display Blazor proto.
* [WordDaze](https://github.com/chrissainty/worddaze) Blogging application written using Blazor with a WebAPI backend.

## Extensions
* [BlazorConfirm](https://github.com/ctrl-alt-d/BlazorConfirm) A Blazor Wrapper for JS's `Window.confirm()` and `onbeforeunload` as .Net Blazor Component ([Demo](https://ctrl-alt-d.github.io/BlazorConfirm/))
* [BlazorGrid](https://github.com/AnkitSharma-007/BlazorGrid) This is a reusable grid component for Blazor which also supports client side pagination.
* [BlazorMaterial](https://github.com/BlazorExtensions/BlazorMaterial) Blazor components implementing Google's Material components for web.
* [BlazorOfficeUIFabric](https://github.com/BlazorExtensions/BlazorOfficeUIFabric) Microsoft Office Fabric UI port for Blazor.
* [BlazorSignalR](https://github.com/csnewman/BlazorSignalR) SignalR Core .NET client library for Blazor. It uses the C# client.
* [Canvas](https://github.com/BlazorExtensions/Canvas) HTML5 Canvas API implementation for Microsoft Blazor.
* [Logging](https://github.com/BlazorExtensions/Logging) Microsoft Extension Logging implementation for Blazor.
* [Notifications](https://github.com/BlazorExtensions/Notifications) HTML5 Notifications API implementation for Microsoft Blazor.
* [SignalR](https://github.com/BlazorExtensions/SignalR) SignalR Core implementation for Blazor. It uses the JavaScript client.
* [Storage](https://github.com/BlazorExtensions/Storage) HTML5 Storage API implementation for Microsoft Blazor.
* [Toastr](https://github.com/BlazorExtensions/Toastr) A Blazor port of Toastr.js.

## Libraries
* [BlazorBits](https://github.com/BlazorBits/BlazorBits) Components including Monaco editor.
* [Blazor-Charts](https://github.com/Misfits-Rebels-Outcasts/Blazor-Charts) SVG charts for Blazor.
* [BlazorComponents](https://github.com/muqeet-khan/BlazorComponents) Reusable components for Blazor. Starting with ChartJS interop.
* [BlazorContextMenu](https://github.com/stavroskasidis/BlazorContextMenu) A context menu component for Blazor ([Demo](https://blazor-context-menu-demo.azurewebsites.net/)).
* [Blazor-Dashboard](https://github.com/Misfits-Rebels-Outcasts/Blazor-Dashboard) Admin Dashboard Template Theme for Blazor.
* [BlazorDB](https://github.com/chanan/BlazorDB) In-memory, persisted to local storage, database for Blazor.
* [Blazor.FlexGrid](https://github.com/Mewriick/Blazor.FlexGrid) GridView component for Blazor.
* [Blazor-Fluxor](https://github.com/mrpmorris/blazor-fluxor) A low-boilerplate Flux/Redux state library for Blazor.
* [Blazor Gamepad](https://github.com/jsakamoto/Toolbelt.Blazor.Gamepad) Provides gamepad API access for Blazor.
* [Blazor.Geolocation](https://github.com/AspNetMonsters/Blazor.Geolocation) Blazor interop for browers Geolocation apis.
* [Blazor Hotkeys](https://github.com/jsakamoto/Toolbelt.Blazor.Hotkeys) A library to provide configuration-centric keyboard shortcuts for Blazor.
* [Blazor LoadingBar](https://github.com/jsakamoto/Toolbelt.Blazor.LoadingBar) Loading bar UI for Client-Side Blazor application.
* [Blazor.LocalFiles](https://github.com/jburman/W8lessLabs.Blazor.LocalFiles) Open files in your browser and load into Blazor.
* [BlazoredLocalStorage](https://github.com/chrissainty/BlazoredLocalStorage) Local storage for Blazor applications.
* [Blazor.Notifications](https://github.com/vertonghenb/Blazor.Notifications) Implementation of the Notification API in C# for Blazor via Interop.
* [Blazorous](https://github.com/chanan/Blazorous) Maintainable CSS with Blazor ([Demo](https://chanan.github.io/Blazorous)).
* [Blazor.Payments](https://github.com/philipblaquiere/Blazor.Payments) Blazor Web Agent port of the Web Payment API standard developed by W3C .
* [Blazor.Polyfill](https://github.com/Daddoon/Blazor.Polyfill) Polyfills for Blazor (for Internet Explorer 11 support and some other browsers).
* [BlazorRealm](https://dworthen.github.io/BlazorRealm/docs/quickstart.html) Redux state management for Blazor.
* [Blazor-Redux](https://github.com/torhovland/blazor-redux) Connecting a Redux state store with Blazor.
* [Blazor.Sensors](https://github.com/AspNetMonsters/Blazor.Sensors) Blazor interop for browers sensor apis.
* [BlazorSplit](https://github.com/BlazorComponents/BlazorSplit) Resizeable split views ([Demo](https://blazorcomponents.github.io/BlazorSplit/)).
* [Blazor-State](https://github.com/TimeWarpEngineering/blazor-state) Manage client side state in Blazor using MediatR pipeline.
* [BlazorStorage](https://github.com/cloudcrate/BlazorStorage) Local and session storage support for Blazor.
* [BlazorStrap](https://github.com/chanan/BlazorStrap) Bootstrap 4 components for Blazor ([Demo](https://chanan.github.io/BlazorStrap/)).
* [Blazor Svg Helper](https://github.com/Lupusa87/BlazorSvgHelper) SVG classes for using in Blazor.
* [Blazor Time Zone Kit](https://github.com/jsakamoto/Toolbelt.Blazor.TimeZoneKit) A system time zones set, and local time zone initialization for Blazor.
* [Blazor.Xamarin](https://github.com/Daddoon/Blazor.Xamarin) A Xamarin template for launch and interop a Blazor app on mobile.
* [ChartJs.Blazor](https://github.com/mariusmuntean/ChartJs.Blazor) Blazor Component that wraps ChartJS.
* [Elmah.Io.Blazor](https://github.com/elmahio/Elmah.Io.Blazor) Logs from Blazor to elmah.io using Microsoft.Extensions.Logging.
* [MatBlazor](https://github.com/BlazorComponents/MatBlazor) Material Design components for Blazor. ([Demo](https://blazorcomponents.github.io/MatBlazor/)).
* [Sotsera.Blazor.Toaster](https://github.com/sotsera/sotsera.blazor.toaster) A Blazor port of Toastr.js.
* [Trail](https://nuget.org/packages/Trail) DSL for writing Blazor markup in F# (with an [adapter](https://nuget.org/packages/Trail.BlazorRedux) for working with BlazorRedux).

## Videos
* [Visual Studio Toolbox: Blazor Part 2](https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/Blazor-Part-2) November 8, 2018 - Visual Studio Toolbox: Blazor Part 2.
* [Visual Studio Toolbox: Blazor Part 1](https://blogs.msdn.microsoft.com/robertgreen/2018/11/06/visual-studio-toolbox-blazor-part-1/) November 6, 2018 - Visual Studio Toolbox: Blazor Part 1.
* [The Blazor Show](https://www.youtube.com/watch?v=wwi55L6Qb18&list=PL1rZQsJPBU2StolNg0aqvQswETPcYnNKL&index=0) October 9, 2018 - ASP.NET Community Standup - The Blazor Show!
* [Developing amazing web apps with ASP.NET Core](https://myignite.techcommunity.microsoft.com/sessions/65901) September 28, 2018 - Microsoft Ignite 2018: Developing amazing web apps with ASP.NET Core, by Daniel Roth.
* [Blazor StateHasChanged](https://www.twitch.tv/videos/315855936) September 28, 2018 - Blazor-Fluxor, Bionic and some live demos of building Blazor Component Templates with Blazor 0.6.0.
* [Blazor StateHasChanged](https://www.twitch.tv/videos/313447722) September 22, 2018 - Blazor 0.6.0 Templates, Razor Components, Hosting with Azure Static Websites, and some live demos using Blazor Interop and Geolocation services.
* [A fistful of Blazor; Its .NET in the browser](https://www.youtube.com/watch?v=5ztMNdCZrRY) September 21, 2018 - A fistful of Blazor; Its .NET in the browser by William Tulloch at the NDC Sydney.
* [Blazor: Modern Web development with .NET and WebAssembly](https://channel9.msdn.com/Events/dotnetConf/2018/S207) September 13, 2018 - Blazor: Modern Web development with .NET and WebAssembly during the .NET Conf 2018.
* [What's New in ASP.NET Core?](https://channel9.msdn.com/Events/dotnetConf/2018/S104) August 11, 2018 - What's New in ASP.NET Core? (31:30).
* [ASP.NET Community Standup - Aug 7, 2018 - Meet the MVC Team!](https://youtu.be/7Eh_l7jEcCo?t=47m35s) August 7, 2018 - ASP.NET Community Standup - Aug 7, 2018 - Meet the MVC Team!
* [Bionic - Ionic CLI clone for Blazor](https://www.youtube.com/watch?v=_YRR6L2Pzks) July 8, 2018 - Bionic - Ionic CLI clone for Blazor ([NuGet package](https://www.nuget.org/packages/Bionic)).
* [ASP.NET Community Standup - Meet the Blazor team!](https://www.youtube.com/watch?v=CWuIz9khK-o) June 12, 2018 - ASP.NET Community Standup - June 12, 2018 - Meet the Blazor team.
* [Blazor, a new .NET SPA framework](https://www.youtube.com/watch?v=JU-6pAxqAa4) May 7, 2018 - Presentation of Blazor by Steve Sanderson at the NDC Minnesota.
* [.NET Overview & Roadmap](https://channel9.msdn.com/Events/Build/2018/BRK2100) May 7, 2018 - .NET Overview & Roadmap (at 1:14:00).
* [What's new in Web Development with ASP.NET Core 2.1](https://channel9.msdn.com/Events/Build/2018/BRK2151) May 6, 2018 - What's new in Web Development with ASP.NET Core 2.1 (Blazor part starts at 1:08:57).
* [Develop ASP.NET Blazor Apps in a Docker Container](https://www.youtube.com/watch?v=jGyFKH5y6LA) April 26, 2018 - Develop ASP.NET Blazor Apps in a Docker Container, from Coding Blocks.
* [ASP.NET Community Standup - Blazor Update with Dan Roth and Steve Sanderson](https://www.youtube.com/watch?v=_b_fUq5DU0U) - April 3, 2018 - ASP.NET Community Standup - Blazor Update with Dan Roth and Steve Sanderson.
* [WebAssembly and Blazor - .NET Concept of the Week - Episode 9](https://www.youtube.com/watch?v=5HSKDGHijdI) - March 4, 2018 - WebAssembly and Blazor - .NET Concept of the Week - Episode 9.
* [Exploring ASP.NET Blazor](https://www.youtube.com/watch?v=VGotz89_iTY) - Feb 10, 2018 - Exploring ASP.NET Blazor! with Jeffrey T. Fritz.
* [ASP.NET Community Standup](https://www.youtube.com/watch?v=Ta_qXpXQqGQ) - Feb 6, 2018 - ASP.NET Community Standup - Blazor Update.
* [Web Apps can’t really do that, can they? - Steve Sanderson](https://www.youtube.com/watch?v=MiLAE6HMr10&feature=youtu.be&t=31m45s) - July 10, 2017 - Web Apps can’t really do that, can they? - Steve Sanderson.

## Articles
* [Validate Request With Recaptcha On A Blazor App And Mediatr](https://remibou.github.io/Validate-request-with-reCaptcha-on-a-Blazor-app-and-MediatR/) November 24, 2018 - Validate Request With Recaptcha On A Blazor App And Mediatr.
* [Validation Controls using Blazor - Basic Validation Controls](http://www.hishambinateya.com/part1-validation-controls-using-blazor-basic-validation-controls) November 20, 2018 - Part I: Validation Controls using Blazor - Basic Validation Controls.
* [Share Blazor Components with Shared Class Libraries](https://daveabrock.com/2018/11/11/using-blazor-shared-libraries/) November 11, 2018 - Share Blazor Components with Shared Class Libraries.
* [Adding Blazor to existing HTML+JavaScript pages](https://visualstudiomagazine.com/articles/2018/10/01/adding-blazor.aspx) November 2, 2018 - Adding Blazor to existing HTML+JavaScript pages.
* [Blazor: Working with Events](https://visualstudiomagazine.com/articles/2018/10/01/blazor-event-handling.aspx) October 31, 2018 - Blazor: Working with Events, by Visual Studio Magazine.
* [Implementing server side CosmosDB pagination in a Blazor Web App](https://chapsas.com/implementing-skiptake-server-side-cosmosdb-pagination-in-a-blazor-web-app/) October 31, 2018 - Implementing server side CosmosDB pagination in a Blazor Web App (Part 1: Page Number and Page Size).
* [Blazor Q&A with Microsoft's Daniel Roth](https://www.telerik.com/blogs/blazor-qa-with-microsofts-daniel-roth) October 25, 2018 - Blazor Q&A with Microsoft's Daniel Roth.
* [Building offline Blazor application](https://gunnarpeipman.com/aspnet/offline-blazor-application) October 24, 2018 - Building offline Blazor application.
* [Service lifetimes in Blazor](https://codedaze.io/service-lifetimes-in-blazor/) October 22, 2018 - Service lifetimes in Blazor.
* [Pages in ASP .NET Core: Razor, Blazor and MVC Views](https://wakeupandcode.com/pages-in-asp-net-core-razor-blazor-and-mvc-views/) October 21, 2018 - Pages in ASP .NET Core: Razor, Blazor and MVC Views.
* [Server-side Blazor applications](https://gunnarpeipman.com/aspnet/server-side-blazor/) October 19, 2018 - Server-side Blazor applications.
* [Building a blogging app with Blazor: adding authentication](https://codedaze.io/building-a-blogging-app-with-blazor-adding-authentication/) October 15, 2018 - Building a blogging app with Blazor: adding authentication.
* [Get Started with Blazor and WebAssembly](https://developer.okta.com/blog/2018/10/15/blazor-and-web-assembly) October 15, 2018 - Get Started with Blazor and WebAssembly.
* [A nicer looking Blazor loading page](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/4315/A-Nicer-Looking-Blazor-Loading-Page.aspx) October 14, 2018 - A nicer looking Blazor loading page.
* [Deploying a Blazor Application on Azure](https://dzone.com/articles/deploying-a-blazor-application-on-azure) October 12, 2018 - Deploying a Blazor Application on Azure.
* [A Blazor Tip You Should Almost Certainly Ignore](https://visualstudiomagazine.com/blogs/tool-tracker/2018/10/blazor-tip.aspx) October 10, 2018 - A Blazor Tip You Should Almost Certainly Ignore.
* [Building Blazor apps with SignalR Core](https://dotnetthoughts.net/building-blazor-apps-with-signalr/) October 3, 2018 - Building Blazor apps with SignalR Core.
* [Server-Side Blazor to ship in .NET Core 3.0](https://visualstudiomagazine.com/articles/2018/10/03/blazor-update.aspx) October 3, 2018 - Server-Side Blazor to ship in .NET Core 3.0.
* [Blazor 0.6.0 experimental release now available](https://blogs.msdn.microsoft.com/webdev/2018/10/02/blazor-0-6-0-experimental-release-now-available/) October 2, 2018 - Blazor 0.6.0 experimental release now available.
* [Integrating JavaScript and C# in the Browser: Beyond the Basics with Blazor](https://visualstudiomagazine.com/articles/2018/09/01/integrating-javascript-csharp.aspx) October 1, 2018 - Integrating JavaScript and C# in the Browser: Beyond the Basics with Blazor.
* [Cutting Edge - Blazor at Work: Events, Binding and Composition](https://msdn.microsoft.com/magazine/mt830361) October 1, 2018 - Cutting Edge - Blazor at Work: Events, Binding and Composition.
* [Work with Cassandra API in Cosmos DB](https://www.c-sharpcorner.com/article/blazor-work-with-cassandra-api-in-cosmos-db/) October 1, 2018 - Work with Cassandra API in Cosmos DB.
* [Building a blogging app with Blazor: Editing & Deleting Posts](https://codedaze.io/building-a-blogging-app-with-blazor-editing-deleting-posts/) September 24, 2018 - Building a blogging app with Blazor: Editing & Deleting Posts.
* [Data Driven Layout in Server-side Blazor](https://hutchcodes.net/2018/09/data-driven-layout-in-razor-components/) September 24, 2018 - Data Driven Layout in Server-side Blazor.
* [Building a blogging app with Blazor: add post](https://codedaze.io/building-a-blogging-app-with-blazor-add-post/) September 18, 2018 - Building a blogging app with Blazor: add post.
* [Dependency Injection Lifetimes in Blazor](https://hutchcodes.net/2018/09/dependency-injection-lifetimes-in-razor-components/) September 17, 2018 - Dependency Injection Lifetimes in Blazor.
* [How to Consume Web APIs in Blazor](https://visualstudiomagazine.com/articles/2018/09/07/blazor-apis.aspx) September 13, 2018 - How to Consume Web APIs in Blazor.
* [Integrating Stripe Payment In With Blazor And Aspnet Core](https://remibou.github.io/Integrating-Stripe-payment-in-with-Blazor-and-ASPNET-Core/) September 11, 2018 - Integrating Stripe Payment In With Blazor And Aspnet Core.
* [Working with the Blazor JavaScript Interop](https://blog.logrocket.com/working-with-the-blazor-javascript-interop-3c2a8d0eb56c) September 5, 2018 - Working with the Blazor JavaScript Interop.
* [Cutting Edge - Never Mind JavaScript, Here’s Blazor](https://msdn.microsoft.com/magazine/mt829756) September 4, 2018 - Cutting Edge - Never Mind JavaScript, Here’s Blazor, published on Microsoft Magazine.
* [Web Development - C# in the Browser with Blazor](https://msdn.microsoft.com/fr-fr/magazine/mt829752) September 4, 2018 - Web Development - C# in the Browser with Blazor, published on Microsoft Magazine.
* [Building a blogging app with Blazor: Listing Posts](https://codedaze.io/building-a-blogging-app-with-blazor-listing-posts/) September 3, 2018 - Building a blogging app with Blazor: Listing Posts.
* [Blazor: .NET in the browser](https://dncmagazine.blob.core.windows.net/edition38/DNCMag-Issue38.pdf) September 1, 2018 - Blazor: .NET in the browser, from DNC Magazine.
* [Integrating Blazor and JavaScript Code](https://visualstudiomagazine.com/articles/2018/08/01/integrating-blazor-javascript.aspx) August 27, 2018 - Integrating Blazor and JavaScript Code.
* [Building a blogging app with Blazor: Getting Setup](https://codedaze.io/building-a-blogging-app-with-blazor-getting-setup/) August 27, 2018 - Building a blogging app with Blazor: Getting Setup.
* [Client side validation with Blazor and System.DataAnnotation](https://remibou.github.io/Client-side-validation-with-Blazor-and-Data-Annotations/) August 23, 2018 - Client side validation with Blazor and System.DataAnnotation.
* [Writing a Blazor app](https://davidpine.net/blog/blazing-chuck/) August 20, 2018 - Writing a Blazor app.
* [Localizing DateTime (and numbers) in Blazor](https://remibou.github.io/Localizing-DateTime-in-Blazor/) August 17, 2018 - Localizing DateTime (and numbers) in Blazor.
* [Introduction to Server-side Blazor aka Razor Components](https://codedaze.io/introduction-to-server-side-blazor-aka-razor-components/) August 11, 2018 - Introduction to Server-side Blazor aka Razor Components.
* [I18n With Blazor And Aspnet Core](https://remibou.github.io/I18n-with-Blazor-and-ASPNET-Core/) August 11, 2018 - Internationalizing a Blazor App with ASPNET Core as backend service.
* [WebAssembly](https://davidpine.net/blog/webassembly-interview/) August 5, 2018 - Interview with Steve Sanderson (Talking Blazor).
* [Web Assembly and Blazor: Re-assembling the Web](https://weblog.west-wind.com/posts/2018/Jul/31/Web-Assembly-and-Blazor-Reassembling-the-Web) July 31, 2018 - Web Assembly and Blazor: Re-assembling the Web.
* [Understanding Server-Side Blazor](https://www.c-sharpcorner.com/article/understanding-server-side-blazor/) July 29, 2018 - Understanding Server-Side Blazor.
* [Blazor 0.5.0 experimental release now available](https://blogs.msdn.microsoft.com/webdev/2018/07/25/blazor-0-5-0-experimental-release-now-available/) July 25, 2018 - Blazor 0.5.0 experimental release now available.
* [CSRF protection with ASPNET Core and Blazor](https://remibou.github.io/CSRF-protection-with-ASPNET-Core-and-Blazor-Week-29/) July 22, 2018 - CSRF protection with ASPNET Core and Blazor.
* [Blazor for Knockout.js Developers](https://blog.usejournal.com/blazor-for-knockout-js-developers-bfeefaacffc3) July 20, 2018 - A brief comparison between two of Steve Sanderson’s Creations.
* [Uploading a file in a Blazor app](https://remibou.github.io/Upload-file-with-Blazor/) July 12, 2018 - Uploading a file in a Blazor app.
* [Adding search to Blazor applications](https://gunnarpeipman.com/search2/blazor-search/) July 11, 2018 - Adding search to Blazor applications.
* [SPA framework on .Net via WebAssembly](https://koukia.ca/blazor-spa-framework-on-net-via-webassembly-b7a0046e7f21) July 10, 2018 - SPA framework on .Net via WebAssembly.
* [ASP.NET Core Blazor CRUD](https://code.msdn.microsoft.com/vstudio/ASPNET-Core-Blazor-122b108a) July 9, 2018 - ASP.NET Core Blazor Master/Detail CRUD with Filtering and Sorting using EF.
* [Improved Cascading Dropdowns With Blazor](https://www.mikesdotnetting.com/article/320/improved-cascading-dropdowns-with-blazor) July 5, 2018 - Improved Cascading Dropdowns With Blazor.
* [Hosting a Blazor App in Azure Storage Static Websites](https://anthonychu.ca/post/blazor-azure-storage-static-websites/) June 28, 2018 - Hosting a Blazor App in Azure Storage Static Websites.
* [Implementing Google OAuth with Blazor](https://remibou.github.io/Google-OAuth-with-Blazor-ASPNET-Core-Week-26/) June 28, 2018 - Implementing Google OAuth with Blazor (0.4) and ASPNET Core 2.1.1.
* [Web Assembly, Blazor and the future of Web Development](https://medium.com/@ZombieCodeKill/web-assembly-blazor-and-the-future-of-web-development-c240fbe5e5be) June 25, 208 - Web Assembly, Blazor and the future of Web Development.
* [Hosting Blazor on Netlify](https://mattferderer.com/host-blazor-on-netlify) Hosting Blazor on Netlify.
* [Who is Blazor for Exactly?](https://wildermuth.com/2018/06/13/Who-is-Blazor-for-Exactly) June 13, 208 - Who is Blazor for Exactly?
* [Blazor 0.4.0 experimental release now available](https://blogs.msdn.microsoft.com/webdev/2018/06/07/blazor-0-4-0-experimental-release-now-available/) June 7, 2018 - Blazor 0.4.0 experimental release now available.
* [Blazor Update Boosts .NET/JavaScript Interoperability](https://visualstudiomagazine.com/articles/2018/06/08/blazor-0-4-0.aspx) June 8, 2018 - Blazor Update Boosts .NET/JavaScript Interoperability.
* [An Introduction to Blazor](https://remibou.github.io/An-Introduction-to-Blazor-Week-22/) June 5, 2018 - An Introduction to Blazor.
* [Creating an SPA Using Razor Pages With Blazor](https://medium.freecodecamp.org/how-to-create-a-single-page-application-using-razor-pages-with-blazor-9d010fd6be45) June 4, 2018 - Creating an SPA Using Razor Pages With Blazor ([Article on FreeCodeCamp](https://medium.freecodecamp.org/how-to-create-a-single-page-application-using-razor-pages-with-blazor-9d010fd6be45) - [Article on DZone](https://dzone.com/articles/creating-an-spa-using-razor-pages-with-blazor)).
* [Cascading DropDownList in Blazor Using EF Core](http://ankitsharmablogs.com/cascading-dropdownlist-in-blazor-using-ef-core/) May 14, 2018 - Creating a cascading dropdown list in Blazor using Entity Framework Core database first approach.
* [Deploying a Blazor Application on IIS](http://ankitsharmablogs.com/deploying-a-blazor-application-on-iis/) May 14, 2018 - Deploying an ASP.NET Core hosted Blazor application with the help of IIS 10 on a Windows 10 machine.
* [Blazor Steals the Show in VSLive!](https://visualstudiomagazine.com/articles/2018/05/03/vslive-austin.aspx) May 3, 2018 - Blazor Steals the Show in VSLive! .NET Keynote.
* [Blazor 0.3.0 experimental release now available](https://blogs.msdn.microsoft.com/webdev/2018/05/02/blazor-0-3-0-experimental-release-now-available/) May 2, 2018 - Blazor 0.3.0 experimental release now available.
* [Blazor, Razor, WebAssembly, and Mono](https://daveaglick.com/posts/blazor-razor-webassembly-and-mono) April 24, 2018 - Blazor, Razor, WebAssembly, and Mono, How the pieces fit together.
* [BlazeDown with Blazor](http://edcharbeneau.com/blazedown-with-blazor) April 20, 2018 - BlazeDown with Blazor (Blazor + Markdown = BlazeDown!).
* [Blazor 0.2.0 release now available](https://blogs.msdn.microsoft.com/webdev/2018/04/17/blazor-0-2-0-release-now-available/) April 18, 2018 - Blazor 0.2.0 release now available.
* [ASP.NET Core – CRUD Using Blazor And Entity Framework Core](http://ankitsharmablogs.com/asp-net-core-crud-using-blazor-and-entity-framework-core/) April 9, 2018 - Creating a web application using Blazor with the help of Entity Framework Core.
* [Using C# await against JS Promises in Blazor](https://joonasw.net/view/csharp-await-and-js-promises-in-blazor) April 7, 2018 - Using C# await against JS Promises in Blazor.
* [Create a CRUD App using Blazor and ASP.NET Core](http://www.talkingdotnet.com/create-a-crud-app-using-blazor-and-asp-net-core/) April 5, 2018 - Create a CRUD App using Blazor and ASP.NET Core.
* [Blazor – You Want To Run .NET Where?!](https://dotnetcore.gaprogman.com/2018/04/05/blazor-you-want-to-run-net-where/) April 5, 2018 - Blazor – You Want To Run .NET Where?!
* [What is Blazor and why is it so exciting?](https://codedaze.io/what-is-blazor-and-why-is-it-so-exciting/) March 24, 2018 - What is Blazor and why is it so exciting?
* ['Death to JavaScript!' Blazor, for .NET Web Apps Using WebAssembly, Goes Alpha](https://visualstudiomagazine.com/articles/2018/03/23/blazor-alpha.aspx) March 23, 2018 - 'Death to JavaScript!' Blazor, for .NET Web Apps Using WebAssembly, Goes Alpha.
* [Get started building .NET web apps that run in the browser with Blazor](https://blogs.msdn.microsoft.com/webdev/2018/03/22/get-started-building-net-web-apps-in-the-browser-with-blazor/) March 22, 2018 - Get started building .NET web apps that run in the browser with Blazor.
* [Blazor and .NET Core hosting – the future’s bright](http://blog.tdwright.co.uk/2018/03/05/blazor-and-net-core-hosting-the-futures-bright) March 5, 2018 - Blazor and .NET Core hosting – the future’s bright.
* [Blazor: a web UI framework running C# and .NET in the browser](https://www.oxfordcc.co.uk/blog/blazor-a-web-ui-framework-running-csharp-and-dotnet-in-the-browser) February 8, 2018 - Blazor: a web UI framework running C# and .NET in the browser.
* [A new experiment: Browser-based web apps with .NET and Blazor](https://blogs.msdn.microsoft.com/webdev/2018/02/06/blazor-experimental-project/) February 6, 2018 - A new experiment: Browser-based web apps with .NET and Blazor.
* [Blazor: a technical introduction](http://blog.stevensanderson.com/2018/02/06/blazor-intro/) February 6, 2018 - Blazor: a technical introduction.
* [Running Blazor on Mono in the browser](http://blog.stevensanderson.com/2017/11/05/blazor-on-mono/) - November 5, 2017 - Running Blazor on Mono in the browser.
* [.NET and WebAssembly - Is this the future of the front-end?](https://www.hanselman.com/blog/NETAndWebAssemblyIsThisTheFutureOfTheFrontend.aspx) - August 12, 2017 - .NET and WebAssembly - Is this the future of the front-end?
  
## Podcasts
* [SDN Cast #118 - With Rainer Stropek and Serverside Blazor!](https://www.youtube.com/watch?v=S66mK_30gPE) November 8, 2018 - Weekly SDN Cast with special gues Rainer Stropek talking about and showing off Blazor!
* [Ed Charbeneau on Blazor](https://crosscuttingconcerns.com/Podcast-099-Ed-Charbeneau-Blazor) September 17, 2018 - Ed Charbeneau on Blazor.
* [Blazor brings .NET to Web Assembly with Steve Sanderson](https://hanselminutes.com/642/blazor-brings-net-to-web-assembly-with-steve-sanderson) July 26, 2018 - Blazor brings .NET to Web Assembly with Steve Sanderson.
* [Episode 037 – Blazor with Daniel Roth](https://6figuredev.com/podcast/episode-037-blazor-with-daniel-roth/) April 30, 2018 - Episode 037 – Blazor with Daniel Roth.
* [MS Dev Show : Blazor](https://www.youtube.com/watch?v=xJtpYsVRggE) March 19, 2018 - MS Dev Show Episode 184: Blazor (.NET in WebAssembly) with Dan Roth & Steve Sanderson.
* [.NET Rocks, WebAssembly and Blazor with Steve Sanderson](https://www.dotnetrocks.com/?show=1455) July 4, 2017 - .NET Rocks 1455, WebAssembly and Blazor with Steve Sanderson.
* [Inside WebAssembly with Mozilla Fellow David Bryant](https://hanselminutes.com/581/inside-webassembly-with-mozilla-fellow-david-bryant) May 25, 2017 - Inside WebAssembly with Mozilla Fellow David Bryant.

## Tooling
* [ASP.NET Core Blazor Language Services](https://marketplace.visualstudio.com/items?itemName=aspnet.blazor) Provides Visual Studio support for ASP.NET Core Blazor.
* [BlazorFiddle](https://blazorfiddle.com) Blazor .Net Developer Playground and Code Editor in the Browser.
* [.NET Core](https://www.microsoft.com/net/download/dotnet-core) .NET Core.
* [Razor+](https://marketplace.visualstudio.com/items?itemName=austincummings.razor-plus) Improved Razor support for VS Code with a mind towards Blazor.
* [Visual Studio](https://www.visualstudio.com/vs/preview) Latest preview of Visual Studio.
* [Visual Studio Code](https://code.visualstudio.com/) Visual Studio Code, free, open source and cross-platform code editor.

## Books
* [Blazor Quick Start Guide: Build web applications using Blazor, EF Core, and SQL Server](https://www.amazon.in/gp/product/178934414X/ref=awesome_blazor) Blazor Quick Start Guide: Build web applications using Blazor, EF Core, and SQL Server (Published October 31, 2018)

## Courses
* [Blazor First Look on LinkedIn Learning](https://www.linkedin.com/learning/blazor-first-look) Blazor First Look on LinkedIn Learning. [Source code](https://github.com/Dedac/Beam).
  
## Community
* [Gitter](https://gitter.im/aspnet/Blazor) Blazor discussion on Gitter.
* [Stack Overflow](https://stackoverflow.com/questions/tagged/blazor) Blazor questions feed on Stack Overflow.
* [Twitter](https://twitter.com/hashtag/blazor) Hashtag on Twitter.
* [Awesome Blazor on Twitter](https://twitter.com/awesomeblazor) This repository's Twitter feed.

## Contributing
Please see [CONTRIBUTING](https://github.com/AdrienTorris/awesome-blazor/blob/master/CONTRIBUTING.md) for details.
