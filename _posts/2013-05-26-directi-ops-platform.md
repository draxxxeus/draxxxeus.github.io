---
layout: post
title: Directi Ops Platform
---

# Index
1. [Keywords](#keywords)
2. [Prologue](#prologue)
3. [Workflow](#workflow)
4. [Apps](#apps)
5. [Tools and Technologies](#tools)

<br><br>
---

<br><br>

# 1. Keywords
* [Directi](#directi)
* [Operations](#Operations)
* [SLA](#sla)

<br><br>
---

<br><br>

# 2. Prologue

I would like to give a brief introduction about the architecture at Directi so that you can understand it better why we went on to develop the platform.

Directi is primarily a hosting and email service provider. It has a large number of servers, some of which are publically accessible and others are accessible only from the intranet.
Also, like any other hosting or email provider we promise our customers a minimum time for which our services will be available (SLA).
Now, consider this:

1. we have different tools that check the health of each of the servers and sends an alert if anything goes wrong with anyone of them.

    * [Pingdom](https://www.pingdom.com/) for checking HTTP, DNS etc on servers with public IP

    * [Icinga](https://www.icinga.org/) for checking services like Load, Disk or any other custom services on servers with private IP

2. there is no way to correlate an outage with the events received at that time.

3. we have various log information that can be helpful

<br><br>
---

<br><br>

# 3. Workflow

<br><br>
---

<br><br>

# 4. Apps

The OPS Platform at Directi comprises for different apps. Here is a list:

* Contacts
* Products
* Event Processing Engine
* SLA
* Notifier
* Reports

<br><br>
---

<br><br>

# 5. Tools and Technologies

<br><br>
