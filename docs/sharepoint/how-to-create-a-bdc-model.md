---
title: "How to: Create a BDC Model | Microsoft Docs"
ms.custom: ""
ms.date: "02/02/2017"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "office-development"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "VB"
  - "CSharp"
  - "VB"
  - "CSharp"
helpviewer_keywords: 
  - "BDC [SharePoint development in Visual Studio], creating a model"
  - "Business Data Connectivity service [SharePoint development in Visual Studio], creating a model"
ms.assetid: e8b888d4-a531-4d13-9ebf-efbbd33eebc6
caps.latest.revision: 15
author: "kempb"
ms.author: "kempb"
manager: "ghogen"
---
# How to: Create a BDC Model
  You can create a Business Data Connectivity (BDC) model by using the template for that kind of item and then adding the model to any SharePoint project. For more information, see [Creating a Business Data Connectivity Model](../sharepoint/creating-a-business-data-connectivity-model.md). For more information about how to design the model, see [Designing a Business Data Connectivity Model](../sharepoint/designing-a-business-data-connectivity-model.md).  
  
### To create a BDC project  
  
1.  On the menu bar, choose **File**, **New**, **Project**.  
  
    > [!NOTE]  
    >  If your IDE is set to use Visual Basic development settings, choose **File**, **New Project**.  
  
     The **New Project** dialog box opens.  
  
2.  Under either **Visual Basic** or **Visual C#**, choose **Office/SharePoint**, **SharePoint Solutions**.  
  
3.  In the **Templates** pane, choose the **SharePoint 2013 – Empty Project** item, and then choose the **OK** button.  
  
     The **SharePoint Customization Wizard** opens.  
  
4.  On the **Specify the site and security level for debugging** page, specify the URL of a SharePoint site on the local computer, choose the **Deploy as farm solution** option button, and then choose the **Finish** button.  
  
     You will test the model on the SharePoint site that you specified.  
  
    > [!IMPORTANT]  
    >  You must deploy the project as a farm solution because BDC models support only farm solutions.  
  
     An empty SharePoint project is created.  
  
5.  On the menu bar, choose **Project**, **Add New Item**.  
  
6.  In the **Add New Item** dialog box, choose the **Office/SharePoint** node.  
  
7.  In the list of SharePoint templates, choose **Business Data Connectivity Model (Farm Solution Only)**.  
  
8.  In the **Name** box, specify a name for the BDC model, and then choose the **Add** button.  
  
     A **Business Data Connectivity Model** item is added to the project. By default, the model appears in the BDC designer. For more information, see [Creating a Business Data Connectivity Model](../sharepoint/creating-a-business-data-connectivity-model.md).  
  
## See Also  
 [Creating a Business Data Connectivity Model](../sharepoint/creating-a-business-data-connectivity-model.md)   
 [How to: Add an Existing BDC Model File to a SharePoint Project](../sharepoint/how-to-add-an-existing-bdc-model-file-to-a-sharepoint-project.md)   
 [How to: Use a Resource File to Specify Localized Names, Properties, and Permissions](../sharepoint/how-to-use-a-resource-file-to-specify-localized-names-properties-and-permissions.md)   
 [How to: Include a Custom Assembly in a BDC Feature](../sharepoint/how-to-include-a-custom-assembly-in-a-bdc-feature.md)   
 [Integrating Business Data into SharePoint](../sharepoint/integrating-business-data-into-sharepoint.md)  
  
  