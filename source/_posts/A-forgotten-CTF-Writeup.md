---
title: A forgotten CTF Writeup
date: 2022-06-11 15:18:50
tags: [ctf, python, networking]
author: "Lam"
categories:
- [Programming and Hacking, CTF]
---

## Foreword
This is my first ever CTF writeup I ever done in my life, since I ever delved into the rabbit hole of CTF and cybersecurity. 

The challenge is from the CTFFlag Asia Junior

I'll put a link here if you want to learn more:
[CTFFlag Asia Junior](https://junior.ctflag.asia)

(I never feel so dumb myself UwU.)

## The Kid Protocol - an UDP based application Protocol

### From the challenge description:

{% blockquote %}
**Kid Protocol** is an application-layer protocol that has just been created based on the UDP protocol.
The Python code below is the source code of the server running the **Kid Protocol**. If you have. Can you read this protocol and write a program to communicate with the server?
{% endblockquote %}


Access information:
{% codeblock %}
Server IP: 178.128.19.56 (Probably outdated, not working anymore)
UDP Port: 3108
{% endcodeblock %}


### Overview

Here's an overview of the kid protocol server code provided by the challenge
{% include_code lang:python kid_server.py %}