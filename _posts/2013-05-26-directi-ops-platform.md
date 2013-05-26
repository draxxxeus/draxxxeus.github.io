---
layout: post
title: Directi Ops Platform
---

1856.15

# Keywords
## Directi
## Operations

# Preface

I would like to give a brief introduction about the architecture at Directi so that you can understand it better why we went on to develop the platform.

Directi is primarily a hosting and email service provider. It has a large number of servers, some of which are publically accessible and others are accessible only from the intranet.
Also, like any other hosting or email provider we promise our customers a minimum time for which our services will be available (SLA).
Now, consider this:

* we have different tools that check the health of each of the servers and sends an alert if anything goes wrong with anyone of them.

    * Pingdom for checking HTTP, DNS etc on servers with public IP

    * Icinga for checking services like Load, Disk or any other custom services on servers with private IP

* there is no way to correlate an outage with the events received at that time.

* we have various log information that can be helpful

So, how
