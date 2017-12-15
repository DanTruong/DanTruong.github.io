---
layout: post
title:  "Windows Print and LPD Service Checker"
subhead: "Windows batch script for checking and repairing Print Spooler and LPD services."
date:   2017-12-14 17:00:00 -0500
categories: projects
---

The purpose of this project is to provide the mechanism for scheduled tasks to report back to the user the status of the Print Spooler and LPD service on Windows-based print server. How this works is that the Batch script "spool-checker.cmd" is run on an intermittent basis. If any outages were to occur, the script will attempt to rectify the outage by restarting the Spooler or LPD service. It will then log the error, as well as send an email out on its' status. This was tested with 64-bit versions of Windows 7, Windows 10 and Windows Server 2012. Code for the script can be found [here](https://github.com/DanTruong/Print-Service-Check).

