---
published: true
title: How to Convert a dmg to an iso file in Linux
layout: post
tags: [dmg, img, Install, iso, Linux, Mac, OSX, Ubuntu]
categories: [Linux]
---
Press Ctrl + Alt + T on your keyboard to open Terminal. When it opens, run the commands below:

<strong>sudo apt-get install dmg2img</strong>

Once installed, change the directory to where the .dmg file is located and run the following command:

<strong>dmg2img <file_name>.dmg</strong>

This will convert the .dmg to an .img file. Run the following command to convert the .img to an .iso file.

<strong>mv <file_name>.img <file_name>.iso</strong>