# Guide For Building IRC "Stack" 
(Debian + Nginx + UnrealIRCd + Anope + etc)
<br><br>
This is **NOT** a program, it is a step by step guide for you to build an IRC "Stack" on a Virtual Private Server (VPS) from a VPS company such as Vultr.
(This guide is not specific to Vultr, you can use other VPS providers). The intent is for the user to open a terminal window and then copy and paste the instructions provided. The intent of the guide is to help you understand what to do and **why** it is done a certain way.
<br><br>
It is called a "Stack" because this guide includes more than just building an IRC, you can combine the IRC with Mumble, Matrix and other things.
This guide uses UnrealIRCd for the IRC Daemon, it uses Anope for the IRC Services, and it uses Nginx for the webserver.
<br><br>
# Purpose for this guide
It is with genuine and benevolent intentions that this guide helps **ANYONE** build their own independent communications medium.
Censorship of **true & accurate information** on platforms such as Twitter, Facebook, etc have become more common.
Once you have your own server that you run, you won't have to worry about anyone "suspending" or "banning" you, except maybe the hosting company if things get extreme.
<br>
#### Side note, if you want to help make a version of this guide for hosting an IRC "stack" on a machine you have on your own property, that would be helpful. It would also be helpful if someone wanted to build this stack in a different order, like Debian -> Apache -> InspIRCd, etc.


You DO NOT need to know how to code, and hopefully you find this guide useful even if you don't have a lot of technical knowledge or skills.
This guide does assume you know how to use SSH to access your VPS, and it also assumes you know how to use sudo for root privleges.
<br><br>
If you want to contribute, please learn this project's philosophy. The philosophy is to start out with minimalism first (like flask), and then let the user add what they wish. Any feedback with essential things like security are appreciated.
