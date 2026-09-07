---
title: "Siber Siaga 2025: Finale"
description: "Geolocating a suspect from a single street-level snapshot using shopfront signage, Google Maps and a lot of patience."
slug: siber-siaga-2025-finale
date: 2025-10-01T09:14:47Z
image: img-02.png
categories:
  - Siber Siaga 2025
tags:
  - OSINT
  - Geolocation
draft: false
---

# The Starting Point

By Rizzykun

Category: OSINT

Description: 

One of our agents managed to locate one of the suspects. We lost contact before he could tell us where he was. This snapshot was the only documentation he could send. Can you find where this place is?

Note: Use the google map name if you have found the location.

Flag format: SIBER25{main_street-town_name-state_name-country}

Answer:

Resource:

![Screenshot 1](img-01.png)

So, this is the last place the suspect was seen, okay , Let’s lock in!!

First, we need to identify where is this place, maybe the shops could help?

![Screenshot 2](img-02.png)

So, he is near these shops. Let’s try locating every single store.

When googling each of the store names, almost every single one returns that it is a part of multiple branches of a store chain in Russia except for Клубника, салон фотопечати (Strawberry, Photo Printing Salon). This store is an independent and unique store, then, I find a city website named chaykovsky which holds info about the store.

![Screenshot 3](img-03.png) 

![Screenshot 4](img-04.png)

The website pinpoint the exact location of the store and give the address. Then, I enter the address in google Maps and it gave the result:

![Screenshot 5](img-05.png)

Then, we get the address , following the flag format we got : 

SIBER25{ulitsa_sovetskaya-chaykovsky-perm_krai-russia}

The suspect was last seen located near mall named ТЦ (Мега).
