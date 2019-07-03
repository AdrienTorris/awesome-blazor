# Awesome Blazor [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
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
Recommanded: [Visual Studio 2019 Preview](https://visualstudio.microsoft.com/) and the [latest .NET Core Framework](https://dotnet.microsoft.com/download/dotnet-core/3.0).

## General
* [ASP.NET Blog's archives](https://devblogs.microsoft.com/aspnet/category/blazor/) - Archives of the ASP.NET blog about Blazor.
* [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/client) - Official website of Blazor, from Microsoft.
* [Blazor bites](https://chrissainty.com/blazor-bites/) - Blazor bites series by chris Sainty.
* [Blazor-Dev gallery on .NET Foundation](https://dotnet.myget.org/gallery/blazor-dev) - Daily builds of the 'dev' branch of Blazor.
* [Blazor Extensions](https://github.com/BlazorExtensions) - Curated extensions for Microsoft ASP.Net Core Blazor.
* [Blazor University](http://blazor-university.com/) - Unofficial documentation website.
* [Demo](https://blazor-demo.github.io/) - Official demo website.
* [FAQ](https://github.com/aspnet/Blazor/wiki/FAQ) - FAQ.
* [GitHub repository](https://github.com/aspnet/Blazor) - The official Blazor repository.
* ['Hello World' sample](https://github.com/dodyg/practical-aspnetcore/tree/master/projects/blazor) - 'Hello World' sample.
* [Introduction to ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/) - Introduction to ASP.NET Core.
* [Study Blazor](https://studyblazor.com) - Blazor tutorial for beginners, in simple and easy steps starting from basics to advanced concepts with more code snippets.
* [Workshop](https://github.com/dotnet-presentations/blazor-workshop/) - Blazor workshop.

## Sample Projects
### CMS
* [WordDaze](https://github.com/chrissainty/worddaze) - Blogging application written using Blazor with a WebAPI backend.
* [BlogCore](https://github.com/thangchung/blog-core) - Modern CMS on Domain-driven Design and Clean Architecture patterns.
### Games
* [AsteroidsWasm](https://github.com/aesalazar/AsteroidsWasm) - A mixed bag of C# projects to see if a single .NET Standard base can run across all common platforms include WebAssembly. [Demo](https://aesalazar.github.io/AsteroidsWasm/).
* [BlazorChess](https://github.com/Lupusa87/BlazorChess) - Chess engine implemented with Blazor. [Demo](https://lupblazorchess.z20.web.core.windows.net/).
* [BlazorGameSnake](https://github.com/Lupusa87/BlazorGameSnake) - 2D game snake with customizations, path finding algorithm, and sound effects using SVG. [Demo](https://lupblazorsnake.z20.web.core.windows.net/).
* [BlazorDestinationGame](https://github.com/SharePointSean/BlazorDestinationGame) - Quizz about places in the world. [Demo](https://blazordestinationgame.azurewebsites.net/).
* [Blagario](https://github.com/ctrl-alt-d/Blagario) - Experimental lab to test blazor server side as multiplayer game engine with no canvas (just blazor, html and css). Collaborations are welcome. Scaffolding status.
* [Blazor20Questions](https://github.com/MetalMichael/blazor-20-questions) - Client/Server game using Websockets (SignalR) & MongoDB API, with Docker (docker-compose).
* [BlazorDice](https://github.com/shahedc/BlazorDemos/tree/master/BlazorDice) - Roll the dice.
* [BlazorQuiz](https://github.com/Amine-Smahi/BlazorQuiz) - Simple quiz using Blazor.NET and Webassembly.
* [Tzaar](https://github.com/paularundel/tzaar) - Implementation of the board game Tzaar with Blazor and SignalR. [Demo](https://tzaar.azurewebsites.net/).
### ToDos
* [BlazorAdvancedTodo](https://github.com/EdCharbeneau/BlazorAdvancedTodo) - A Blazor to-do app with state and undo function.
* [BlazorTasks](https://github.com/BorowskiKamil/blazor-tasks) - To-Do App.
* [Bolero.TodoMVC](https://github.com/fsbolero/TodoMVC) - A TodoMVC clone using Bolero.
### Others
* [BlazeDown](https://github.com/EdCharbeneau/BlazeDown) - BlazeDown, online Markdown editor. [Demo](https://edcharbeneau.com/BlazeDown/).
* [Client-side RealWorld](https://github.com/burke166/blazor-client-side-realworld-example-app) - [RealWorld](https://github.com/gothinkster/realworld) implementation of Blazor Client-Side. [Demo](https://blazorclientside.computercodeblue.com).
* [Server-side RealWorld](https://github.com/burke166/blazor-server-side-realworld-example-app) - [RealWorld](https://github.com/gothinkster/realworld) implementation of Blazor Server-Side. [Demo](https://blazorserverside.computercodeblue.com).
* [BlazorClockCanvas](https://github.com/Lupusa87/BlazorClockCanvas) - Complex clock based on Canvas. [Demo](https://lupblazorclockcanvas.z20.web.core.windows.net/).
* [BlazorClockSVG](https://github.com/Lupusa87/BlazorClockSVG) - Complex clock based on SVG. [Demo](https://lupblazorclocksvg.z20.web.core.windows.net/).
* [BlazorFileReader](https://github.com/Tewr/BlazorFileReader) - Read-only File streams in Blazor. [Demo](https://tewr.github.io/BlazorFileReader/).
* [Blazor Spreadsheet](https://github.com/Lupusa87/BlazorSpreadsheet) - Spreadsheet app developed in Blazor. [Demo](https://lupblazorspreadsheet.z20.web.core.windows.net/).
* [BlazorPasswordPattern](https://github.com/Lupusa87/BlazorPasswordPattern) - Password pattern based on SVG. [Demo](https://lupblazorpasswordpattern.z20.web.core.windows.net/).
* [BlazorRawHtmlRenderer](https://github.com/Lupusa87/BlazorRawHtmlRenderer) - Raw HTML rendering with Blazor. [Demo](https://lupblazorrawhtml.z20.web.core.windows.net/).
* [BlazePort](https://github.com/EdCharbeneau/BlazePort) - A futuristic ride share app for space travel written in full stack .NET with Blazor.
* [BlazingPizza (server side)](https://github.com/ADefWebserver/BlazingPizza) - A server side Blazor version of the Blazing Pizza project from the [Blazor - app building workshop](https://github.com/dotnet-presentations/blazor-workshop/).
* [BlazorBeerCalculator](https://github.com/gpeipman/BlazorBeerCalculator) - Offline beer alc. vol. calculator built on Blazor. [Demo](https://gunnarpeipman.com/demos/blazoroffline/).
* [BlazorBinding](https://github.com/SQL-MisterMagoo/BlazorBinding) - Sample Blazor App demonstrating various data binding scenarios.
* [BlazorBoilerplate](https://github.com/enkodellc/blazorboilerplate) - Admin Dashboard / Starter Template with IdentityServer4, MatBlazer for Material Design.
* [BlazorCalculator](https://github.com/Lupusa87/BlazorCalculator) - Simple calculator with history and ability to use previous results in new calculations. [Demo](https://lupblazorcalculator.z20.web.core.windows.net/).
* [Blazor calculator with expressions](https://github.com/khaledmousa/BlazorCalculator) - A sample numerical expression evaluator in Blazor utilizing an F# library that uses FsLex and FsYacc to parse expressions. [Demo](https://khaledmousa.github.io/).
* [Blazor Charts](https://github.com/SQL-MisterMagoo/Mister-Magoo-Goes-Charting) - Chart components for Blazor.
* [Beam](https://github.com/Dedac/Beam) - A social network demo application. This is the source code of the LinkedIn course "Blazor First Look".
* [BlazorChatSample](https://github.com/conficient/blazorchatsample) - Blazor chat demo using SignalR JS client with interop.
* [Blazor Converters](https://github.com/lohithgn/blazor-converters) - Blazor Converters is simple converter app written using Blazor, influenced by Windows 10 Calculator.
* [BlazorCRUD](https://github.com/thbst16/BlazorCrud) - Sample line of business application that illustrates key features of Blazor. [Demo](https://becksblazor.azurewebsites.net/).
* [BlazorDynamicList](https://github.com/conficient/BlazorDynamicList) - Dynamic component binding for a generic list. [Demo](https://blazordynamiclist.azurewebsites.net/).
* [BlazorElectronExperiment](https://github.com/SteveSandersonMS/BlazorElectronExperiment.Sample) - Exploring how a Blazor could be used to build a cross-platform desktop application using [Electron](https://electronjs.org/).
* [BlazorFormsValidation](https://github.com/Dallas411/BlazorFormsValidation) - Blazor form validation sample.
* [BlazorGraphExample](https://github.com/jburman/BlazorGraphExample) - Example application for connecting to Graph API from Blazor.
* [Blazor.JWTTest](https://github.com/shawty/blazor.jwttest) - JWT authentication for a blazor hosted (Client/Serverside) app with API and Authentication.
* [BlazorMobile](https://github.com/Daddoon/BlazorMobile) - Launch a Blazor application as a standalone application.
* [BlazorPaint](https://github.com/Lupusa87/BlazorPaint) - A paint sample with Blazor ([demo](https://lupblazorpaint.z20.web.core.windows.net/)).
* [BlazorPages](https://github.com/fernandreu/blazor-pages) - A sample client-side Blazor app showcasing automatic deployment to GitHub Pages via Azure Pipelines.
* [BlazorServerTree](https://github.com/ctrl-alt-d/BlazorServerTree) - A simple Server-Side Blazor sample app to deal with hierarchical data.
* [BlazorServiceWorker](https://github.com/roboriaan/BlazorServiceWorker) - A client-side Blazor template with service worker caching.
* [Blazor Summernote](https://github.com/shawty/blazor.summernote) - Wrapper for the new MS Blazor framework, allowing the use of the Summernote Wysiwyg editor in a form.
* [Blazor Survey](https://github.com/nutshellit/Blazor-Survey) - A hybrid F#/C# blazor sample app to kick the tyres of blazor.
* [Blazor.Toaster](https://github.com/sotsera/sotsera.blazor.toaster) - A Blazor port of Toastr.js.
* [Blazor Tree CRUD](https://github.com/ctrl-alt-d/TreeCrud) - CRUD operations with hierarchical data. Blazor Server + GraphQL + EF.
* [Blazor.Universal](https://github.com/pushqrdx/Blazor.Universal) - Example of using Blazor to build Xamarin based UWP application without WebAssembly.
* [BlazorUnmarshalledCanvas](https://github.com/jhwcn/BlazorUnmarshalledCanvas) - Unmarshalled invoking of Canvas 2d context from Blazor.
* [BlazorValidationControls](https://github.com/hishamco/BlazorValidationControls) - Blazor validation controls.
* [BlazorWithIdentity](https://github.com/stavroskasidis/BlazorWithIdentity) - A sample project showcasing a Blazor app using EF Core with Identity authentication.
* [Blazor.Xamarin](https://github.com/Appizeo/Blazor.Xamarin) - A Xamarin template for launch and interop a Blazor app on mobile.
* [Blazor + Electron sample](https://github.com/aspnet/AspLabs/tree/master/src/ComponentsElectron) - Explore how a Blazor app can be used to build a cross-platform desktop app.
* [Blazor + Sitecore](https://github.com/GoranHalvarsson/SitecoreBlazor) - Example of dynamic pages and routes with SiteCore and [Helix](https://helix.sitecore.net/). 
* [C# Minifer](https://github.com/atifaziz/CSharpMinifierDemo) A client-side Blazor application demonstrating live minification of C# code using the [C# Minifier](https://github.com/atifaziz/CSharpMinifier) library. [Demo](https://atifaziz.github.io/CSharpMinifierDemo/)
* [CssBuilder](https://www.nuget.org/packages/BlazorComponentUtilities/) &ndash; A clean code approach to conditional CSS classes for Razor components in Blazor.
* [Data Driven Layout](https://github.com/hutchcodes/Blazor.DataDrivenLayout) - Two ways of driving the layout based on data in the page.
* [Flight Finder](https://github.com/aspnet/samples/tree/master/samples/aspnetcore/blazor) - Flight Finder.
* [Gitter](https://github.com/Blazored/Gitter) - A Blazor Gitter client.
* [Money](https://github.com/maraf/Money) - A money manager implemented using CQRS+ES. [Demo](https://app.money.neptuo.com/).
* [NethereumBlazor](https://github.com/Nethereum/NethereumBlazor) - Ethereum blockchain explorer and simple wallet.
* [Oqtane Framework](https://github.com/oqtane/oqtane.framework) - Modular Application Framework for Blazor.
* [Runny](https://github.com/Suchiman/Runny) - Prototype of running roslyn in the browser via Blazor. [Demo](https://runny.azurewebsites.net/).
* [Rudder Example](https://github.com/kjeske/rudder-example) - Sample application using Rudder state container for Blazor.
* [StarshipTraveler](https://github.com/rstropek/StarshipTraveler) - A starship traveler demo app built with Blazor for the DevOne 2019 conference.
* [TaxiFareBlazorServer](https://github.com/EdCharbeneau/TaxiFareBlazorServer) - ML.NET TaxiFare Prediction Model with Blazor Server-Side front end.
* [Tour of Heroes](https://github.com/lohithgn/blazor-tour-of-heroes) - Blazor implementation of Angular Tour of Heroes.
* [Toss.Blazor](https://github.com/RemiBou/Toss.Blazor) - Twitter-like web application using Blazor.
* [Try F# on WebAssembly](https://github.com/fsbolero/TryFSharpOnWasm) - The F# compiler running in WebAssembly with Bolero.
* [Tulsa .NET User Group website](https://github.com/devsgarage/tulsa-dnug-website) - Tulsa .NET User Group website.
* [WebSocketPage](https://github.com/Lupusa87/BlazorWebSocketHelper) - Web Socket in Blazor. [demo](https://lupblazordemos.z13.web.core.windows.net/WebSocketPage).
* [ZoraGen Blazor](https://github.com/friendlyanon/zoragen-blazor) - PWA capable Blazor UI for the [ZoraSharp](https://github.com/kabili207/zora-sharp) library.
* [Planning Poker](https://github.com/duracellko/planningpoker4azure) &ndash; An app to play Planning Poker for distributed teams. The app is implemented using Blazor and shows how to switch between client-side and server-side mode with a configuration change. [Demo](http://planningpoker.duracellko.net).
* [Gjallarhorn](https://github.com/haavamoa/Gjallarhorn) - Compare packages on different NuGet-sources. Demonstating Client-Side Blazor MVVM-style. 

## Tutorials
* [Blazor client-side app with CRUD operations against a Web API endpoint](http://blog.medhat.ca/2019/05/blazor-app-with-crud-operations-from.html) - May 31, 2019 - Blazor client-side app with CRUD operations against a Web API endpoint. [Source code](https://github.com/medhatelmasry/BlazingSchool). [Video](https://www.youtube.com/watch?v=wkSR3eo4Tek).
* [Get .NET Core 3 and Blazor running on a Raspberry PI](https://gist.github.com/shawty/a55f6d09edc2d381c8bd5bf2f639b2de) - April 24, 2019 - Instructions on how to get the latest .NET Core 3 (as of 24th April 2019) and Blazor running on a Raspberry PI.
* [Blazor TODO list](https://github.com/exceptionnotfound/BlazorToDoList) - April 22, 2019 - Blazor TODO list.
* [Blazor workshop](https://github.com/dotnet-presentations/blazor-workshop/) - Blazor app building workshop by [.NET Foundation](https://www.dotnetfoundation.org/), Blazzing Pizza.
* [Archives of 2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#tutorials)

## Libraries & Extensions
### Components
*Reusable components like buttons, inputs, grids and more.*
* [Canvas](https://github.com/BlazorExtensions/Canvas) - HTML5 Canvas API implementation for Microsoft Blazor.
* [BlazorMaterial](https://github.com/BlazorExtensions/BlazorMaterial) - Blazor components implementing Google's Material components for web.
* [BlazorStrap](https://github.com/chanan/BlazorStrap) - Bootstrap 4 components for Blazor ([Demo](https://chanan.github.io/BlazorStrap/)).
* [BlazorStyled](https://github.com/chanan/BlazorStyled) - CSS in Blazor Components ([Demo](https://chanan.github.io/BlazorStyled)).
* [BlazorContextMenu](https://github.com/stavroskasidis/BlazorContextMenu) - A context menu component for Blazor ([Demo](https://blazor-context-menu-demo.azurewebsites.net/)).
* [Blazorise](https://github.com/stsrki/Blazorise) - Components for Blazor with support for Bootstrap, Bulma and Material CSS. ([Demo](https://bootstrapdemo.blazorise.com/))
* [BlazorBits](https://github.com/BlazorBits/BlazorBits) - Components including [Monaco editor](https://github.com/Microsoft/monaco-editor).
* [BlazorVirtualGrid](https://github.com/Lupusa87/BlazorVirtualGrid) - Reusable, fully configurable component with rows and columns fast virtualization ([Demo](https://lupblazorvirtualgrid.z13.web.core.windows.net/)).
* [BlazorVirtualScrolling](https://github.com/SamProf/BlazorVirtualScrolling) - Virtual Scrolling Component for Blazor
 ([Demo](https://samprof.github.io/BlazorVirtualScrolling/)).
 * [BlazorScrollbar](https://github.com/Lupusa87/BlazorScrollbar) - Reusable, fully configurable component with vertical and horizontal scrollbars ([Demo](https://lupblazorscrollbar.z20.web.core.windows.net/)).
 * [BlazorSplitter](https://github.com/Lupusa87/BlazorSplitter) - Reusable, fully configurable component with vertical and horizontal splitters and diagonal resizer ([Demo](https://lupblazorsplitter.z20.web.core.windows.net/)).
 * [Sotsera.Blazor.Toaster](https://github.com/sotsera/sotsera.blazor.toaster) - A Blazor port of Toastr.js. [Demo](https://blazor-toaster.sotsera.com/).
 * [NodaTimePicker](https://github.com/nheath99/NodaTimePicker) - A Date/Time picker component library for Blazor using NodaTime. [Demo](https://nodatimepicker.azurewebsites.net/).
 * [BlazorConfirm](https://github.com/ctrl-alt-d/BlazorConfirm) - A Blazor Wrapper for JS's `Window.confirm()` and `onbeforeunload` as .Net Blazor Component ([Demo](https://ctrl-alt-d.github.io/BlazorConfirm/)).
* [Blazor LoadingBar](https://github.com/jsakamoto/Toolbelt.Blazor.LoadingBar) - Loading bar UI for Client-Side Blazor application.
* [Blazor-Charts](https://github.com/Misfits-Rebels-Outcasts/Blazor-Charts) - SVG charts for Blazor.
* [BlazorComponents](https://github.com/muqeet-khan/BlazorComponents) - Reusable components for Blazor. Starting with ChartJS interop.
* [ChartJs.Blazor](https://github.com/mariusmuntean/ChartJs.Blazor) - Blazor Component that wraps ChartJS.
* [Blazored.Menu](https://github.com/Blazored/Menu) - A JavaScript free menu library for Blazor and Razor Components applications.
* [Blazored.Modal](https://github.com/Blazored/Modal) - A JavaScript free modal library for Blazor and Razor Components applications.
* [Blazored.Toast](https://github.com/Blazored/Toast) - A JavaScript free toast library for Blazor and Razor Component applications.
* [Blazored.Typeahead](https://github.com/Blazored/Typeahead) - Auto-complete textbox with local and remote data source, for both Client-side and Server-Side Blazor.
* [BlazorGrid](https://github.com/AnkitSharma-007/BlazorGrid) - This is a reusable grid component for Blazor which also supports client side pagination.
* [DevExpress Blazor UI Components](https://github.com/DevExpress/RazorComponents) - UI components including Data Grid, Pivot Grid, and several data editors.
* [Blazor.FlexGrid](https://github.com/Mewriick/Blazor.FlexGrid) - GridView component for Blazor.
* [MatBlazor](https://github.com/SamProf/MatBlazor) - Material Design components for Blazor. ([Demo](https://www.matblazor.com/)).
* [Syncfusion Blazor UI Components](https://github.com/syncfusion/ej2-aspnet-core-blazor-samples) - Robust UI components including [Data Grid](https://ej2.syncfusion.com/aspnet-core-razor-components/Grid/DefaultFunctionalities), [Charts](https://ej2.syncfusion.com/aspnet-core-razor-components/Charts/polar), [Scheduler](https://ej2.syncfusion.com/aspnet-core-razor-components/Schedule/TimelineResourceGroup), [Inputs](https://ej2.syncfusion.com/aspnet-core-razor-components/TextBox/DefaultFunctionalities) and several [Editor](https://ej2.syncfusion.com/aspnet-core-razor-components/RichTextEditor/DefaultFunctionalities) components.
* [Telerik UI for Blazor](https://www.telerik.com/blazor-ui) - A native set of UI components for Blazor, including grid, charting, and calendar components.
* [TwitterShareButton](https://github.com/jsakamoto/Toolbelt.Blazor.TwitterShareButton) - A Tweet Button component for Blazor.
* [Flexor](https://github.com/DerekChasse/Flexor) - Highly configurable components which let you take full advantage of Flexbox CSS.([Demo](http://flexor.azurewebsites.net/)).
* [Grid.Blazor](https://github.com/gustavnavar/Grid.Blazor) - Grid component for Blazor and ASP.NET MVC, supporting filtering, sorting, searching, paging, subgrids and others ([Demo](http://gridblazor.azurewebsites.net)).
* [Blazor.Validation.DataAnnotation](https://github.com/RemiBou/Blazor.Validation.DataAnnotation) - Library for validating form on a Blazor application using Data Annotation.
* [Radzen.Blazor](https://github.com/akorchev/razor.radzen.com/) - Native UI components for Blazor. DataGrid, DataList, Tabs, Dialog and more. ([Demo](https://razor.radzen.com/)).
### Tools & Utilities
*Libraries and extensions for state management, cookies, local storage and other specific tools.*
* [Logging](https://github.com/BlazorExtensions/Logging) - Microsoft Extension Logging implementation for Blazor.
* [Notifications](https://github.com/BlazorExtensions/Notifications) - HTML5 Notifications API implementation for Microsoft Blazor.
* [SignalR](https://github.com/BlazorExtensions/SignalR) - SignalR Core implementation for Blazor. It uses the JavaScript client.
* [Storage](https://github.com/BlazorExtensions/Storage) - HTML5 Storage API implementation for Microsoft Blazor.
* [Blazored.LocalStorage](https://github.com/chrissainty/BlazoredLocalStorage) - Local storage for Blazor applications.
* [Blazored.Localisation](https://github.com/Blazored/Localisation) - A library to provide localisation in client-side Blazor applications.
* [BlazorPrettyCode](https://github.com/chanan/BlazorPrettyCode) - Blazor Code Component for documentation sites. [Demo](https://chanan.github.io/BlazorPrettyCode/).
* [Blazor Analytics](https://github.com/isc30/blazor-analytics) - Blazor extensions for Analytics.
* [Blazor BarCode](https://barcoderesource.com/blazorbarcode.shtml) &ndash; A barcode library for Blazor using barcode fonts.
* [Blazor Svg Helper](https://github.com/Lupusa87/BlazorSvgHelper) - Create SVG elements with children (circle, rectangle, image, text, and others) and render with RenderTreeBuilder.
* [Blazor I18n/Localization Text](https://github.com/jsakamoto/Toolbelt.Blazor.I18nText) - Localizing contents text in Blazor ([Demo](https://jsakamoto.github.io/Toolbelt.Blazor.I18nText/)).
* [BlazorDB](https://github.com/chanan/BlazorDB) - In-memory, persisted to local storage, database for Blazor.
* [Blazor Time Zone Kit](https://github.com/jsakamoto/Toolbelt.Blazor.TimeZoneKit) - A library to provide system time zones and local time zone initialization in Blazor apps.
* [BlazorStorage](https://github.com/cloudcrate/BlazorStorage) - Local and session storage support for Blazor.
* [EmbeddedBlazorContent](https://github.com/SamProf/EmbeddedBlazorContent) - Library to load embedded content files (js and css) from Blazor libraries in server-side Blazor mode.
* [Blazor.EventAggregator](https://github.com/mikoskinen/Blazor.EventAggregator) - Lightweight Event Aggregator for Blazor (Razor Components).
* [Blazor-Fluxor](https://github.com/mrpmorris/blazor-fluxor) - A low-boilerplate Flux/Redux state library for Blazor.
* [Blazor-Redux](https://github.com/torhovland/blazor-redux) - Connecting a Redux state store with Blazor.
* [Blazor-State](https://github.com/TimeWarpEngineering/blazor-state) - Manage client side state in Blazor using MediatR pipeline.
* [Blazor.Auth0](https://github.com/Pegazux/Blazor.Auth0) - Library for Blazor authentication with OIDC Authorization Code-Grant and Implicit-Grant flows, using Auth0's Universal Login and Silent Login.
* [Blazor Gamepad](https://github.com/jsakamoto/Toolbelt.Blazor.Gamepad) - Provides gamepad API access for Blazor.
* [Blazor Hotkeys](https://github.com/jsakamoto/Toolbelt.Blazor.Hotkeys) - A library to provide configuration-centric keyboard shortcuts for Blazor.
* [CssBuilder](https://github.com/EdCharbeneau/CssBuilder) - CssBuilder is a Builder pattern for CSS classes to be used with Razor Components.
* [Blazor.Geolocation](https://github.com/AspNetMonsters/Blazor.Geolocation) - Blazor interop for browers Geolocation apis.
* [BlazorRealm](https://dworthen.github.io/BlazorRealm/docs/quickstart.html) - Redux state management for Blazor.
* [Blazor.LocalFiles](https://github.com/jburman/W8lessLabs.Blazor.LocalFiles) - Open files in your browser and load into Blazor.
* [Blazor.Payments](https://github.com/philipblaquiere/Blazor.Payments) - Blazor Web Agent port of the Web Payment API standard developed by W3C .
* [Blazor.Polyfill](https://github.com/Daddoon/Blazor.Polyfill) - Polyfills for Blazor (for Internet Explorer 11 support and some other browsers).
* [Blazor.Sensors](https://github.com/AspNetMonsters/Blazor.Sensors) - Blazor interop for browers sensor apis.
* [BlazorSignalR](https://github.com/csnewman/BlazorSignalR) - SignalR Core .NET client library for Blazor. It uses the C# client.
* [Rudder](https://github.com/kjeske/rudder) - Efficient state container for Blazor with concepts similar to the ones in redux, including reducers and sagas.
* [BlazorIntersectionObserver](https://github.com/ljbc1994/BlazorIntersectionObserver) - A Blazor wrapper for the Intersection Observer API.
* [Blazor.SpeechSynthesis](https://github.com/jsakamoto/Toolbelt.Blazor.SpeechSynthesis) - A library to provide Speech Synthesis API access for Blazor.
### Others
* [Blazor Extensions Home](https://github.com/BlazorExtensions/Home) - Home for Blazor Extensions.
* [Bionic](https://bionicframework.github.io/Documentation/) - An Ionic CLI clone for Blazor projects.
* [Blazor-Dashboard](https://github.com/Misfits-Rebels-Outcasts/Blazor-Dashboard) - Admin Dashboard Template Theme for Blazor.
* [Blazor.Xamarin](https://github.com/Daddoon/Blazor.Xamarin) - A Xamarin template for launch and interop a Blazor app on mobile.
* [BlazorEmbedLibrary](https://github.com/SQL-MisterMagoo/BlazorEmbedLibrary) - Provides Blazor-style embedded static content files for Razor Components projects.
* [BlazorFabric](https://github.com/limefrogyank/BlazorFabric) - Blazor port of Microsoft UI Fabric with fluent design. ([Demo](https://blazorfabric.azurewebsites.net/)).
* [BlazorFileSaver](https://github.com/IvanJosipovic/BlazorFileSaver) - Blazor Component wrapper for FileSaver.js. 
* [BlazorOfficeUIFabric](https://github.com/BlazorExtensions/BlazorOfficeUIFabric) - Microsoft Office Fabric UI port for Blazor.
* [Bolero](https://github.com/fsbolero/Bolero) - Blazor for F# with hot reloaded templates, type-safe endpoints and routing, remoting, and much more.
* [NObservable](https://github.com/kekekeks/NObservable) - MobX-like observables and component instrumentation.
* [WebSocketHelper](https://github.com/Lupusa87/BlazorWebSocketHelper) - Helper for Web Socket in Blazor.

## Videos
* [The Freeze Team - A Blazor Console](https://www.twitch.tv/videos/447594138) - July 3, 2019 -  - The Freeze Team - A Blazor Console.
* [The Freeze Team - A Blazor CLI](https://www.twitch.tv/videos/444377657) - June 26, 2019 - The Freeze Team - A Blazor CLI.
* [Blazor StateHasChanged: BlazePort part 5](https://www.twitch.tv/videos/443598774) - June 24, 2019 - Blazor StateHasChanged: BlazePort part  5, about creating BlazePort, a futuristic ride share app for space travel written in full stack .NET with Blazor. [Source Code](https://github.com/EdCharbeneau/BlazePort).
* [Blazor StateHasChanged: BlazePort part 4](https://www.twitch.tv/videos/442689869) - June 22, 2019 - Blazor StateHasChanged: BlazePort part  4, about creating BlazePort, a futuristic ride share app for space travel written in full stack .NET with Blazor. [Source Code](https://github.com/EdCharbeneau/BlazePort).
* [Working Through the Blazor Workshop From Scratch](https://www.youtube.com/watch?v=QkVQ6XdIsE0) - June 21, 2019 - Working Through the Blazor Workshop From Scratch, by Ardalis.
* [.NET Core 3.0 with Scott Hunter](https://channel9.msdn.com/Shows/On-NET/NET-Core-30-with-Scott-Hunter) - June 20, 2019 - In this episode, Richard Lander and Scott Hunter get together to discuss some of the highlights that developers can look forward to in this new release of .NET Core.
* [Server-side Blazor in .NET Core 3.0](https://channel9.msdn.com/Shows/On-NET/Server-side-Blazor-in-NET-Core-30) - June 18, 2019 - Server-side Blazor in .NET Core 3.0.
* [ASP.NET Community Standup - .NET Core 3.0 Preview 6](https://www.youtube.com/watch?v=SKnIzX6WFfI&list=PL1rZQsJPBU2StolNg0aqvQswETPcYnNKL&index=0) - June 18, 2019 - ASP.NET Community Standup - .NET Core 3.0 Preview 6.
* [Blazor StateHasChanged: BlazePort part 3](https://www.twitch.tv/videos/440348759) - June 17, 2019 - Blazor StateHasChanged: BlazePort part  3. Video about creating BlazePort, a futuristic ride share app for space travel written in full stack .NET with Blazor. [Source Code](https://github.com/EdCharbeneau/BlazePort).
* [Blazor with Material Design Framework, part 1](https://www.youtube.com/watch?v=X4QYcVX6NCw) - June 16, 2019 - Blazor with Material Design Framework - MatBlazor (Part - 1).
* [Blazor StateHasChanged: BlazePort part 2](https://www.twitch.tv/videos/438942939) - June 14, 2019 - Blazor StateHasChanged: BlazePort part  2. Second video about creating BlazePort, a futuristic ride share app for space travel written in full stack .NET with Blazor. [Source Code](https://github.com/EdCharbeneau/BlazePort).
* [Blazing Pizza Deep Dive with Daniel Roth](https://www.youtube.com/watch?v=HxZTD0isAxQ) - June 11, 2019 - ASP.NET Community Standup - June 11th, 2019 - Blazing Pizza Deep Dive with Daniel Roth.
* [Blazor - You Want To Run .NET Where?!](https://www.youtube.com/watch?v=t9g-GogZDeo) - June 11, 2019 - Blazor - You Want To Run .NET Where?!.
* [Blazor SPA Framework C# with MongoDB - Part 1](https://www.youtube.com/watch?v=XHbOyEFoPV0) - June 9, 2019 - Blazor SPA Framework C# with MongoDB - Part 1.
* [Blazor in the cloud: Hosting a C# SPA app as a static website in Azure Storage](https://channel9.msdn.com/Shows/Azure-Friday/Blazor-in-the-cloud-Hosting-a-C-SPA-app-as-a-static-website-in-Azure-Storage) - June 7, 2019 - Blazor in the cloud: Hosting a C# SPA app as a static website in Azure Storage.
* [Building a C# Interactive shell in a browser with Blazor (WebAssembly) and Roslyn](https://www.strathweb.com/2019/06/building-a-c-interactive-shell-in-a-browser-with-blazor-webassembly-and-roslyn/) - June 7, 2019 - Building a C# Interactive shell in a browser with Blazor (WebAssembly) and Roslyn.
* [Blazor - Getting Started with Daniel and Mehul](https://www.youtube.com/watch?v=93OtjA8VUgc) - June 6, 2019 - Blazor - Getting Started with Daniel Roth and Mehul Harry, published by DevExpress.
* [Blazor client-side app with CRUD operations against a Web API endpoint](https://www.youtube.com/watch?v=wkSR3eo4Tek) - June 1, 2019 - Blazor client-side app with CRUD operations against a Web API endpoint.
* [Blazor StateHasChanged: BlazePort part 1](https://www.twitch.tv/videos/430658092) - May 27, 2019 - First video about creating BlazePort, a futuristic ride share app for space travel written in full stack .NET with Blazor. [Source Code](https://github.com/EdCharbeneau/BlazePort).
* [Blazor CRUD app tutorial - SPA Framework for .NET developers (Part - 2)](https://www.youtube.com/watch?v=TMiFNM_1oZI) - May 22, 2019 - Blazor CRUD app tutorial - SPA Framework for .NET developers (Part - 2).
* [Blazor application state management basics](https://www.youtube.com/watch?v=1o-_78ONM1s) - May 14, 2019 - Blazor application state management basics.
* [Blazor Q/A Live with Daniel Roth from Microsoft Build 2019](https://www.youtube.com/watch?v=zp9wQt8J6hY) - May 14, 2019 - Blazor Q/A Live with Daniel Roth from Microsoft Build 2019.
* [Upgrading to Blazor Preview 4 and Hacking SEO in Client-side Blazor](https://www.youtube.com/watch?v=i2eVseMWidQ) - May 14, 2019 - Upgrading to Blazor Preview 4 and Hacking SEO in Client-side Blazor.
* [Continuation of the Tulsa .NET User Group website](https://www.twitch.tv/videos/422982467) - May 10, 2019 - Continuation of the Tulsa .NET User Group website. [Source code](https://github.com/devsgarage/tulsa-dnug-website) here.
* [Scott Hunter Demos Telerik UI for Blazor](https://clips.twitch.tv/SpookyProudPineapplePeanutButterJellyTime) - May 10, 2019 - Scott Hunter Demos Telerik UI for Blazor.
* [Blazor: C# running in the browser via WebAssembly](https://www.youtube.com/watch?v=8De8DlrCzoY) - May 8, 2019 - "Blazor: C# running in the browser via WebAssembly" by Scott Sauber at the NDC Conference Minnesota. Slides and source code [here](https://scottsauber.com/2019/05/08/ndc-minnesota-talk-blazor-c-running-in-the-browser-via-webassembly/).
* [WebAssembly: Into the WASM'verse](https://www.youtube.com/watch?v=P8rSdOXiyEc) - May 8, 2019 - WebAssembly: Into the WASM'verse.
* [Full stack web development with ASP.NET Core 3.0 and Blazor](https://mybuild.techcommunity.microsoft.com/sessions/77033) - May 7, 2019 - Microsoft Build 2019: Full stack web development with ASP.NET Core 3.0 and Blazor.
* [Serverless web apps with Blazor, Azure Functions, and Azure Storage](https://mybuild.techcommunity.microsoft.com/sessions/77336) - May 6, 2019 - Microsoft Build 2019: Serverless web apps with Blazor, Azure Functions, and Azure Storage.
* [SPA revolution with WebAssembly and ASP.NET Blazor](https://www.youtube.com/watch?v=_gYgkZ1UBQ4) - April 23, 2019 - DevOneConf 2019 - Rainer Stropek - SPA revolution with WebAssembly and ASP.NET Blazor.
* [ASP.NET Community Standup](https://www.youtube.com/watch?v=ap60h3eQE5Y) - April 16, 2019 - ASP.NET Community Standup - Blazor Updates with Dan Roth and Steve Sanderson.
* [ASP NET Core + Blazor](https://www.youtube.com/watch?v=AXwD9S4rOFM) - April 12, 2019 - ASP NET Core + Blazor at the philly.NET Code Camp.
* [Continuation of the Tulsa .NET User Group website](https://www.twitch.tv/videos/409976640) - April 12, 2019 - Continuation of the Tulsa .NET User Group website. [Source code](https://github.com/devsgarage/tulsa-dnug-website) here.
* [Continuation of the Tulsa .NET User Group website](https://www.twitch.tv/videos/409075153) - April 10, 2019 - Continuation of the Tulsa .NET User Group website. [Source code](https://github.com/devsgarage/tulsa-dnug-website) here.
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
* [Introduction to Authentication with Blazor](https://chrissainty.com/securing-your-blazor-apps-introduction-to-authentication-with-blazor/) - July 3, 2019 - Introduction to Authentication with Blazor.
* [Configuring a Server-side Blazor app with Azure App Configuration](https://devblogs.microsoft.com/aspnet/configuring-a-server-side-blazor-app-with-azure-app-configuration/) - July 1, 2019 - Configuring a Server-side Blazor app with Azure App Configuration.
* [Creating a step-by-step end-to-end database Server-Side Blazor application](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/4318/Server-Side-Blazor-Reading-And-Inserting-Data-Into-A-Database-End-To-End.aspx) - June 28, 2019 - Creating a step-by-step end-to-end database Server-Side Blazor application.
* [Using Blazor Components In An Existing MVC Application](https://chrissainty.com/using-blazor-components-in-an-existing-mvc-application/) - June 25, 2019 - Using Blazor Components In An Existing MVC Application.
* [What Is Blazor](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/4336/What-Is-Blazor.aspx) - June 23, 2019 - What Is Blazor.
* [Working with local storage in Blazor](http://danpatrascu.com/working-with-local-storage-in-blazor/) - June 19, 2019 - Working with local storage in Blazor.
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
* [From Angular to Blazor: The Health App](https://blog.jeremylikness.com/from-angular-to-blazor-the-health-app-2e36077d641c) - January 3, 2019 - From Angular to Blazor: The Health App.
* [An Introduction to Templated Components in Blazor](https://visualstudiomagazine.com/articles/2018/12/01/blazor-templated-components.aspx) - January 3, 2019 - An Introduction to Templated Components in Blazor.
* [Archives of 2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#articles)
* [Archives of 2017](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2017.md#articles)
  
## Podcasts
* [MS Dev Show - Blazor with Ed Charbeneau](https://msdevshow.com/2019/06/blazor-with-ed-charbeneau/) - June 24, 2019 - MS Dev Show - Blazor with Ed Charbeneau.
* [.NET Core Show Podcast, Episode 27 - Blazored with Chris Sainty](https://dotnetcore.show/episode-27-blazroed-with-chris-sainty/) - June 14, 2019 - .NET Core Show Podcast, Episode 27 - Blazored with Chris Sainty.
* [Blazor with Ed Charbeneau](https://6figuredev.com/podcast/episode-095-blazor-with-ed-charbeneau/) - June 10, 2018 - The 6 Figure Developer Podcast, Episode 095 – Blazor with Ed Charbeneau.
* [Blazor - You Want To Run .NET Where?!](https://dotnetcore.show/episode-25-blazor-you-want-to-run-net-where/) - May 17, 2019 - .NET Core Show - Episode 25 - Blazor - You Want To Run .NET Where?!
* [The Cynical Developer - Blazor](https://cynicaldeveloper.com/podcast/108) - February 18, 2019 - Episode 108 of The Cynical Developer - Blazor.
* [Blazor in 2019 with Steve Sanderson and Dan Roth](https://player.fm/series/net-rocks-2353294/blazor-in-2019-with-steve-sanderson-and-dan-roth) - February 14, 2019 - .NET Rocks, Blazor in 2019 with Steve Sanderson and Dan Roth.
* [Archives of 2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#podcasts)
* [Archives of 2017](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2017.md#podcasts)

## Presentations slides
* [Blazor, a new framework for browser-based .NET apps](https://github.com/SteveSandersonMS/presentation-2019-06-NDCOslo) - June 20, 2019 - Blazor, a new framework for browser-based .NET apps, by Steve Sanderson at the NDC Oslo.
* [Hidden gems in ASP.Core and .NET Core 3.0](https://speakerdeck.com/davidfowl/hidden-gems-in-asp-dot-core-and-net-core-3-dot-0) - June 19, 2019 - Hidden gems in ASP.Core and .NET Core 3.0, by David Fowler and Damian Edwards at the NDC Oslo.
* [Meet the production-ready Blazor aka Razor Components](https://codecamp.ro/timisoaraSpring) - May 25, 2019 - Slides: [PPTX](https://codecampro.blob.core.windows.net/sessions-upload/1306-CCBlazor.pptx).
* [Iowa .NET User Group – Blazor: C# Running in the Browser via WebAssembly](https://scottsauber.com/2019/05/02/iowa-net-user-group-blazor-c-running-in-the-browser-via-webassembly/) - May 2, 2019 - Slides: [PDF](https://scottsauber.files.wordpress.com/2019/05/blazor.pdf) or [PPTX](https://scottsauber.files.wordpress.com/2019/05/blazor.pptx). Code: [Blazor ToDoMVC](https://github.com/scottsauber/BlazorToDoMVC) and [Blazor on Electron](https://github.com/SteveSandersonMS/BlazorElectronExperiment.Sample).
* [WebAssembly, C#, and Blazor at CodeStock 2019](https://blog.jeremylikness.com/presentation-webassembly-c-and-blazor-at-codestock-2019-ab2f8636356) - April 16, 2019 - Slides: [PDF](https://jlikme.blob.core.windows.net/presentations/ATaleOfShortLinks.pdf). Demo's source code: [GitHub](https://github.com/JeremyLikness/blazor-wasm).
* [Archives of 2018](https://github.com/AdrienTorris/awesome-blazor/blob/master/Archives/2018.md#presentations-slides)

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

## Other Languages
* [Blaze of Code](https://blazeofcode.com/) - [Portuguese] Blog about Blazor.
* [Blazor.ru](https://blazor.ru/) - [Russian] Old official documentation website translated in russian.
* [DevApps.be's podcast #47](http://devapps.be/podcast/47-typescript-uno-angular-docfx/) - [French] DevApps.be's podcast #47: "Actualités : TypeScript, Uno, Angular, DocFX, Database".
* [Modern web apps with Blazor](https://media.aspitalia.com/events/VS2019-Blazor.media) - [Italian] Video about Blazor.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Adrien Torris has waived all copyright and related or neighboring rights to this work.
