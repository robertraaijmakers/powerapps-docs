---
title: "Embed a canvas app on a model-driven form | MicrosoftDocs"
ms.custom: ""
ms.date: 12/10/2018
ms.reviewer: ""
ms.service: "crm-online"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "get-started-article"
applies_to: 
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
  - "PowerApps"
ms.assetid: 00e62904-2ce9-4730-a113-02b1fedbf22e
author: "Aneesmsft"
ms.author: "matp"
manager: "kvivek"
tags: 
  - "PowerApps maker portal impact"
search.audienceType: 
  - maker
search.app: 
  - "PowerApps"
  - D365CE
---

# Embed a canvas app on a model-driven form

Canvas apps enable makers to easily design and create custom layouts using the low-code, WYSIWYG canvas app designer. Canvas apps also enable makers to connect and display data from over 200 data sources on their forms.

> [!NOTE]
> This feature is currently in preview. <br />
> [!INCLUDE [cc-preview-features-definition](../../includes/cc-preview-features-definition.md)] <br /><br />
> This feature is currently available in all regions, except the US and Europe. It should be available in the US and Europe early January 2019. If you want to try the feature right away, you can create an environment in regions where it is currently available such as Australia, Canada, India, or Japan.

With embedded canvas apps, makers can bring the power of canvas apps to their model-driven forms. Using embedded canvas apps, you can easily create rich visual areas on a form and display data from a variety of sources right next to data from the Common Data Service.

   > [!div class="mx-imgBorder"] 
   > ![](media/embed-canvas-app-in-form.png "Embedded canvas app in a model-driven app form")

Canvas apps are embedded in model-driven forms in the same way other custom controls are added. An embedded canvas app includes rich data integration capabilities that bring in contextual data from the host model-driven form to the embedded canvas app.

The steps to embed a canvas app in your model-driven form vary based on the data context that you want the host model-driven form to provide to the embedded canvas app.
-	Pass the current record as data context. More information: [Pass the current record as data context with an embedded canvas app](pass-current-embedded-canvas-app.md)
-	Pass a list of records related to the current record as data context. More information: [Pass a list of related records as data context with an embedded canvas app](pass-related-embedded-canvas-app.md) 

<!-- After you have added an embedded canvas app to your model-driven form, learn how to share your embedded canvas app with other users (LINK TO ARTICLE #4).  -->

<!-- For things to keep in mind when working with embedded canvas apps and to help troubleshoot any issues you might encounter, see (LINK TO ARTICLE #5). -->

## See also
[What are canvas apps in PowerApps?](../canvas-apps/getting-started.md) <br />
[Add and configure a canvas-app control in PowerApps](../canvas-apps/add-configure-controls.md) <br />
[Overview of canvas-app connectors for PowerApps](../canvas-apps/connections-list.md) 