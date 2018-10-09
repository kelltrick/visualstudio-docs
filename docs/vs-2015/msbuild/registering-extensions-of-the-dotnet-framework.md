---
title: "Registering Extensions of the .NET Framework | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "Add References dialog box, registering extensions of the .NET Framework"
  - "MSBuild, registering extensions of the .NET Framework"
  - ".NET Framework extensions, registering"
ms.assetid: deee6f53-ea87-4b88-a120-bea589822e03
caps.latest.revision: 8
author: mikejo5000
ms.author: mikejo
manager: "ghogen"
---
# Registering Extensions of the .NET Framework
[!INCLUDE[vs2017banner](../includes/vs2017banner.md)]

The latest version of this topic can be found at [Registering Extensions of the .NET Framework](https://docs.microsoft.com/visualstudio/msbuild/registering-extensions-of-the-dotnet-framework).  
  
  
You can develop an assembly that extends a specific version of the .NET Framework. To enable the assembly to appear in the Visual Studio **Add References** dialog box, you must add the folder that contains it to the system registry.  
  
 For example, assume that the Trey Research company has developed a library that extends the .NET Framework 4, and wants the library assemblies to appear in the **Add References** dialog box when a project targets the .NET Framework 4. Also assume that the assemblies are 32-bit assemblies running on a 32-bit computer or 64-bit assemblies running on a 64-bit computer, and that they will be installed in the C:\TreyResearch\Extensions4\ folder.  
  
 Register this folder by using this key: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\\.NETFramework\v4.0.21006\AssemblyFoldersEx\TreyResearch\\. Give the key this default value: C:\TreyResearch\Extensions4.  
  
> [!NOTE]
>  The build number of the .NET Framework version may be different.  
  
 To register a 32-bit assembly on a 64-bit computer, use the Wow6432 node, for example: HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\\.NETFramework\v4.0.21006\AssemblyFoldersEx\TreyResearch\\.  
  
## See Also  
 [Visual Studio Integration](../msbuild/visual-studio-integration-msbuild.md)


