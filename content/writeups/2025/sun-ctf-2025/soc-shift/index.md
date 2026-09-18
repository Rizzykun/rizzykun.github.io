---
title: "SUN CTF 2025: SOC Shift"
description: "Filtering 10,000 rows of SIEM logs down to a single Malaysian entry and decoding the base64 payload hiding in it."
slug: soc-shift
date: 2025-10-07T01:45:49Z
image: img-01.png
categories:
  - SUN CTF 2025
tags:
  - Forensics
  - SIEM
  - Log Analysis
  - CyberChef
draft: false
---

Challenge : SOC Shift

Open excel file, have like 10,000 lines . Filter by country ISO code MY

![Screenshot 1](img-01.png)

Find sus base64 , go cyberchef
![Screenshot 2](img-02.png)
Me get flag, me happy ;D

sunctf25{S1EM_b4s1cs_f0r_l0g_4n4Lys1s!}
