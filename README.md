# Kofax FastPack

## Overview

![images_community/download/attachments/121340697/icon.png](images_community/download/attachments/121340697/icon.png)

Kofax is an integrated platform of applications that streamline the transformation of different document types into structured electronic information, ready for delivery into business systems and
processes. Part of the suite includes document review and validation components. It is important to monitor and diagnose how these components are performing on the end users workstation. Kofax
provides their own monitoring solution, but you can get performance metrics by instrumenting this in dynaTrace.

## FastPack Details

|Name | Kofax FastPack
| :-- | :---
| Author | Derek Abing 
| Supported dynaTrace Version | >= 5.5
| License | [dynaTrace BSD](dynaTraceBSD.txt)
| Support | [Community Supported](https://community.compuwareapm.com/community/display/DL/Support+Levels#SupportLevels-Community+Supported)  
| Download | [Kofax System Profile](Kofax.profile.xml)
|| [Kofax Dashboard](Kofax_Daily_Performance_Report.dashboard.xml)

## Images

![images_community/download/attachments/121340697/Kofax_Sensors.jpg](images_community/download/attachments/121340697/Kofax_Sensors.jpg)

![images_community/download/attachments/121340697/Dashboard.jpg](images_community/download/attachments/121340697/Dashboard.jpg)

![images_community/download/attachments/121340697/Kofax_System_Profile.jpg](images_community/download/attachments/121340697/Kofax_System_Profile.jpg)

## Installation

Follow the following Steps:

  * Import the [Kofax System Profile](Kofax.profile.xml)

  * Instrument and Configure your Kofax Application to map the agent group defined in the System Profile (uses .NET Agent) 

  * Restart your application 

  * Open the Kofax [Kofax Dashboard](Kofax_Daily_Performance_Report.dashboard.xml)

