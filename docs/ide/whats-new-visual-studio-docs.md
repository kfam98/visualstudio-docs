---
title: "Visual Studio docs: What's new for August 2020 "
titleSuffix: ""
description: "What's new in the Visual Studio docs for August 2020."
ms.date: 09/02/2020
helpviewer_keywords:
  - "Visual Studio, what's new, docs"
  - "what's new [Visual Studio]"
ms.assetid: 89844796-621B-4EF5-9D76-197084B011CB
author: JoshuaPartlow
ms.author: joshuapa
manager: jillfra
ms.prod: visual-studio-windows
ms.technology: vs-ide-general
ms.topic: conceptual
ms.workload:
  - "multiple"
---

# Visual Studio docs: What's new for August 2020

Welcome to what's new in the Visual Studio docs for August 2020. This article lists some of the major changes to docs during this period. For information about what was new in previous months, see the [what's new history](whats-new-visual-studio-docs-history.md) topic.

## Azure

**New articles**

- [Add Azure Application Insights by using Visual Studio Connected Services](../azure/azure-app-insights-add-connected-service.md) - Connected services for VS 2019 16.7
- [Add Azure Cache for Redis by using Visual Studio Connected Services](../azure/azure-cache-for-redis-add-connected-service.md) - Connected services for VS 2019 16.7
- [Add Azure Cosmos DB to your app by using Visual Studio Connected Services](../azure/azure-cosmosdb-add-connected-service.md) - Connected services for VS 2019 16.7
- [Add Azure SignalR by using Visual Studio Connected Services](../azure/azure-signalr-add-connected-service.md) - Connected services for VS 2019 16.7
- [Add a connection to Azure SQL Database](../azure/azure-sql-database-add-connected-service.md) - Connected services for VS 2019 16.7

**Updated articles**

- [Adding Azure storage by using Visual Studio Connected Services](../azure/vs-azure-tools-connected-services-storage.md)
  - Connected services for VS 2019 16.7
  - Azure storage connected services article: update UI and project types supported

## Code quality

**New articles**

- [CA1310: Specify StringComparison for correctness](../code-quality/ca1310.md) - Add documentation for CA1310 and update documentation for CA1307
- [CA1837: Use Environment.ProcessId instead of Process.GetCurrentProcess().Id](../code-quality/ca1837.md) - Docs for CA1837
- [CA1838: Avoid `StringBuilder` parameters for P/Invokes](../code-quality/ca1838.md) - Add documentation for CA1838
- [CA2008: Do not create tasks without passing a TaskScheduler](../code-quality/ca2008.md) - Add documentation for CA2008
- [CA2249: Consider using String.Contains instead of String.IndexOf](../code-quality/ca2249.md) - Docs for CA2249
- [CA2361: Ensure autogenerated class containing DataSet.ReadXml() is not used with untrusted data](../code-quality/ca2361.md) - More DataSet/DataTable rules
- [CA2362: Unsafe DataSet or DataTable in autogenerated serializable type can be vulnerable to remote code execution attacks](../code-quality/ca2362.md) - More DataSet/DataTable rules
- [IL3000: Avoid using accessing Assembly file path when publishing as a single-file](../code-quality/il3000.md) - Add documentation for IL3000
- [IL3001: Avoid accessing Assembly file path when publishing as a single file](../code-quality/il3001.md) - Add docs for IL3001

**Updated**

- [CA1002: Do not expose generic lists](../code-quality/ca1002.md) - Add Configurability - Api Surface section
- [CA1046: Do not overload operator equals on reference types](../code-quality/ca1046.md) - Add Configurability - Api Surface section
- [CA1307: Specify StringComparison for clarity](../code-quality/ca1307.md) - Add documentation for CA1310 and update documentation for CA1307
- [CA1700: Do not name enum values &#39;Reserved&#39;](../code-quality/ca1700.md) - Add Configurability - Api Surface section
- [CA1707: Identifiers should not contain underscores](../code-quality/ca1707.md) - Add Configurability - Api Surface section
- [CA1822: Mark members as static](../code-quality/ca1822.md) - Add Configurability - Api Surface section
- [CA2351: Ensure DataSet.ReadXml()'s input is trusted](../code-quality/ca2351.md) - More DataSet/DataTable rules
- [Install third-party analyzers](../code-quality/install-roslyn-analyzers.md) - changed structure and titles for code analysis documentation

## Containers

**Updated articles**

- [Deploy an ASP.NET container to a container registry using Visual Studio](../containers/hosting-web-apps-in-docker.md) - Container Tools updates for Visual Studio 16.7 Publish UI
- [Get started with Visual Studio Kubernetes Tools](../containers/tutorial-kubernetes-tools.md) - Kubernetes tutorial: Add steps for removal

## Deployment

**New articles**

- [Visual Studio Installer Projects Extension and .NET Core 3.1](../deployment/installer-projects-net-core.md) - Creating new help page for installer projects .NET Core 3.1 features

**Updated articles**

- [Deploy your app to a folder, IIS, Azure, or another destination](../deployment/deploying-applications-services-and-components-resources.md) - Deployment updates
- [Deployment in Visual Studio](../deployment/index.yml) - Deployment updates

## Extensibility

**Updated articles**
- [Project Subtypes](../extensibility/internals/project-subtypes.md) - Fix list items indentation
- [Color value reference for Visual Studio](../extensibility/ux-guidelines/color-value-reference-for-visual-studio.md) - AB#1759333 Fix missing column headers

## Get started

**Updated articles**

- [Step 5: Deploy your ASP.NET Core app to Azure](../get-started/csharp/tutorial-aspnet-core-ef-step-05.md) - Video tutorial updates for new Connected Services UI

## IDE

**New articles**

- [Change the F1 help key in Visual Studio](./not-in-toc/change-f1-help-key.md) - Refactor default F1 Help page
- [F1 help for the text editor](./not-in-toc/default-f1-text-editor.md) - Refactor default F1 Help page
- [Convert `typeof` to `nameof`](./reference/convert-typeof-to-nameof.md) - Convert typeof to nameof refactoring
- [Simplify LINQ expression](./reference/simplify-linq-expression.md) - Simplify LINQ expression refactoring

**Updated articles**

- [Customize window layouts in Visual Studio](./customizing-window-layouts-in-visual-studio.md) - add monikered vertical document tabs info to Customize Window Layouts topic
- [How to report a problem with Visual Studio or Visual Studio Installer](./how-to-report-a-problem-with-visual-studio.md)
  - Added more info to NMI
  - Redid the whole Report a Problem page
- [F1 help](./not-in-toc/default.md) - Refactor default F1 Help page
- [AutoRecover, Environment, Options dialog box](./reference/autorecover-environment-options-dialog-box.md) - add info about updated autosave file locations
- [Options, Text Editor, Basic (Visual Basic), Advanced](./reference/options-text-editor-basic-visual-basic.md) - Added basic documentation for inline parameter name hints
- [Options, Text Editor, C#, Advanced](./reference/options-text-editor-csharp-advanced.md) - Added basic documentation for inline parameter name hints
- [Visual Studio performance tips and tricks](./visual-studio-performance-tips-and-tricks.md) - add 'disable map mode' and 'disable word wrap' info
- [What's new in Visual Studio 2019](./whats-new-visual-studio-2019.md) - update What's New in Visual Studio 2019 with 16.7 GA info

## RTVS

**Updated articles**

- [Work with SQL Server and R](../rtvs/integrating-sql-server-with-r.md) - corrected tables to include column headers

## Community contributors

The following people contributed to the Visual Studio docs during this period. Thank you! Learn how to contribute to the Visual Studio docs by following the guidance in the [Contributor Guide](/contribute/).

- [AlexB-SheldonMFG](https://github.com/AlexB-SheldonMFG) - Alex Black (11)
- [Youssef1313](https://github.com/Youssef1313) - Youssef Victor (8)
- [hyoshioka0128](https://github.com/hyoshioka0128) - Hiroshi Yoshioka (3)
- [AstroChoco](https://github.com/AstroChoco) - Qian Lu (Chocolate) (1)
- [athyunnath](https://github.com/athyunnath) - Athyunnath Eleti (1)
- [caro-oviedo](https://github.com/caro-oviedo) - Caro Oviedo  (1)
- [Evangelink](https://github.com/Evangelink) - Amaury Levé (1)
- [jethas-bennettjones](https://github.com/jethas-bennettjones) - Shafiq Jetha (1)
- [nebuk89](https://github.com/nebuk89) - Ben De St Paer-Gotch (1)
- [pcartwright81](https://github.com/pcartwright81) (1)
- [pkulikov](https://github.com/pkulikov) - Petr Kulikov (1)
- [riQQ](https://github.com/riQQ) (1)
- [tcmetzger](https://github.com/tcmetzger) - Timo Cornelius Metzger (1)
- [weitzhandler](https://github.com/weitzhandler) - Shimmy (1)