---
layout: post
title: "What do I need to do incase I see Microsoft Office customization installer error?"
date: 2019-11-05 08:44:38 -0400
category: apps4pro 
author: ajita
short-description: Microsoft Office customization installer error
tags: [Apps4.Pro Desktop add-in]
image: https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQbURBBPTkO7_JuJzDTydHQYSkQzWhk2uZopUtqQF9_cHUKucDy
---
Change the following registry value and check it again.  

HKEY_LOCAL_MACHINE\SOFTWARE\MICROSOFT\.NETFramework\Security\TrustManager\PromptingLevel\MyComputer from "Disabled" to "Enabled",  

And  
 
HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\MICROSOFT\.NETFramework\Security\TrustManager\PromptingLevel\MyComputer from "Disabled" to "Enabled", 

 
