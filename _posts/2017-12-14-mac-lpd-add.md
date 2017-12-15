---
layout: post
title:  "Mac LPD Print Queue Script"
subhead: "Ruby terminal script to add LPD queues to macOS."
date:   2017-12-14 17:00:00 -0500
categories: projects
---

The purpose of this project is to automatically add and configure an LPD-based print queue on a client Mac computer. This script was written in Ruby and tested on macOS Sierra (10.12) and High Sierra (10.13). The idea behind the script is to configure the printer's info in the config.json file (such as address, queue name, driver options) and then run it via enterprise desktop management suites such as JAMF, Munki, SCCM or Ivanti. Code and instructions for the script can be found [here](https://github.com/DanTruong/Mac-LPD-Queue-Add).