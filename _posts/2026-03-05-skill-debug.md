---
layout:       post
title:        "openclaw skill debugging process"
author:       "Deming"
header-style: text
catalog:      true
tags:
    - openclaw
---

> -Original Second Article-

openclaw skill debugging process
Yesterday, I submitted a python program (watermark removed) to openclaw, so that it could be automatically rewritten into skill. Because the library that called an ocr could not be downloaded, he downloaded a simple ocr library by himself, and the generation effect was very different from the previous one. Therefore, I used various methods to test, and finally solved it.
1. My development computer is mac, copy the python file to the win host computer of openclaw after the mac is upgraded;
Install dependencies using vscode copilot on win and run the debugger.
3. Change all the arguments in the program to external input (originally written in the program)
4. After successful debugging, copy the complete command executed and tell openclaw to generate a sill according to this command and py file.
5, test results in the flying book, completed.

List of questions:
1. During debugging yesterday, I found that although I had installed self-improving-skill, I did not record the things I thought I could not do in the session. I still used openclaw to adapt a simple watermark removal program and needed to be reminded every time. Watch it today and see if it works.
2. openclaw terminal reminds you to install the chrome plug-in, but you can't find it in the plug-in market. I don't know what's the matter?
3. Want to know how to let openclaw command multiple agents work, do not know where is a more complete tutorial?

Wall climbing Problem:
Yesterday, I always felt that there was something wrong with clash on win. The network was up and down. Later, I found that it was because I did not choose to automatically select nodes.