---
title: "Steps to Register URL"
toc: true
tag: developers
category: "API-Management"
menus: 
    quickstartapi: 
        icon: fa fa-gg
        weight: 2
        category: "Quickstart"
        title: "Register URL" 
        identifier: quickstartapiregister
---

## Steps to Register URL

1. If you do not have a registered URL with **APPSeCONNECT** you have to Register a URL for your organization.Here is how to do it.
  Click on Register URL button. Upon clicking you will get a  popup like this.

![Register Url Org](/staticfiles/api-management/media/register-url-org.PNG)

2. Activate the Cloud hosting enabled. And provide a unique name in Register Url for your organization.For example,veonconsulting.
  So the Base URL for the organization would be `veonconsulting.appseconnectapi.com`.
  
  If you want to create Proxy API stack please provide details like Description,Title,Terms and Conditions and license.
  After this,click on save button and your url would be saved.

 The Screen shows the license types configured while registering the URL.  
![register-url-org1](/staticfiles/api-management/media/register-url-org1.PNG)

* Apache License 2.0: The Apache License, Version 2.0 requires security of the copyright notice and disclaimer.

* BSD 3-Clause Revised License- Prohibits others from using the name of the contributors to stimulate derived products without written consent.
* GNU General Public License Version 3.0 - The GNU General Public License is designed to guarantee, freedom to share and change all versions of a program to make sure it remains free software for all of its users. 
* The Unlicense- The Unlicense is a template for disclaiming copyright monopoly interest in software, in other words, it is a template for dedicating your software to the public domain.
* The BSD 2-clause Simplified License- The BSD 2-clause license allows the user almost unlimited freedom with the software which includes the BSD copyright notice in it.

## Scenario of Registering URL 

1: If the API Proxy or Webhook is to be executed on cloud, Registering the URL is must in such case.

2: If the user wants to keep its IP Public while running the webhook  from the OP agent. The URL is needed to be registered in order to enhance security in the transaction process. 

3: Register URL is needed to be mandatorily done if the user has network issues. 
If not done, then in case of loss of data loss may happen.