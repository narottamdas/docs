---
title: "Steps to define logic over destination mapping"
toc: true
tag: developers
category: "Transformation"
menus: 
    transformationbasic:
        title: "If-Else"
        weight: 4
        icon: fa fa-file-word-o
        identifier: transformationlogicsourcedest
---


## Steps to define logic over destination mapping

Mapping in APPSeCONNECT is done so that a Source Application can communicate with the Destination Application. APPSeCONNECT, introduces a new mapping structure `If-Else Mapping`. This Document will talk about this mapping process and in different levels where we can apply the If-Else Mapping.

## Pre-requisites for Mapping
1. Login to the APPSeCONNECT Portal with valid credentials.
2. Select the Application. [Click HERE](/getting-started/) to know more about selecting of Applications.
3. Create a Connection. [Click HERE](/getting-started/) to know more.

## Mapping Levels

Mapping is done at various level of Input Packet. Refer [here](/transformation/define-source-destination-transformation/)  
### Mapping at Attribute Level

The user/implementer can work on If-Else Mapping in the attribute level. Given below is the Screen where the If-Else Mapping is done at the Attribute level.  
![Attributelevel-Mapping](/staticfiles/Transformation/media/Attributelevel-Mapping.png)

The user can add condition and attributes from the drop-down option for which the If-Else mapping will work.

![Attributelevel-AddCondition](/staticfiles/Transformation/media/Attributelevel-AddCondition.png)

**Note: The user can add conditions (Else-If & Else) inside an IF Node similarly as shown in the screen below, except for the FOR-EACH LOOP LEVEL.**

* The above given mapping scenario is explained below 

The Condition default-address/country-code='US' in the IF Node describes that if the Country Code in the default address is US, the clause Country_Region_Code=HU is carried out.

The Condition default-address/country-code='IN' in the Else-If node describes that if the Country code in the Default Address is IN, the clause Country_Region_Code = GB is carried out.

And for the Otherwise (ELSE)Node,the given clause will be carried out.

Refer the screen given below:

![Attributelevel-ConditionView](/staticfiles/Transformation/media/Attributelevel-ConditionView.png)  
The User can also add Else-If and Else(Otherwise) and its clauses in the attribute Level. The following screen shows the Condition add for If-Else.  

![Attributelevel-Else](/staticfiles/Transformation/media/Attributelevel-Else.png)

**NOTE: The Add Condition window is for the condition marked in the Yellow Box**

### Mapping at Loop Level

The `If Mapping can be done at the For-Each Loop level`. Below is the screen which shows the **If Mapping** at the For-Each Loop Level.  

![LoopLevel-Mapping](/staticfiles/Transformation/media/LoopLevel-Mapping.png)

**Protip** In the For-Loop Level, only IF is used as this level is just for removing duplicate check and also removing junk data, for integration process 
{: .notice--info}

### Mapping at Complex Object Level

The user/implementer can work on the If-Else Mapping in the complex object level. 
Below is the Screen which shows the If-Else Mapping at the complex object level.  

![LoopLevel-Mapping](/staticfiles/Transformation/media/ComplexObject-Mapping.png)

Like other levels, the user can add Else-If and Otherwise and its conditions from the drop down. 

### Mapping at Complex Object Collection  Level

The If-Else Mapping can be done at the ComplexObjectCollection Level. Below is the screens which shows the Mapping at that level.  

![LoopLevel-Mapping](/staticfiles/Transformation/media/ComplexObjectCollection-If-Mapping.png)  
![LoopLevel-Mapping](/staticfiles/Transformation/media/ComplexObjectCollection-else-Mapping.png)