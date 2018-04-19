---
layout   : default
permalink: design/smartphone-app/
published: true
# Custom Page Variables
# ─────────────────────
title: Smartphone-app
---
## Research
### Layout Principles
#### Floating action button <br>
Een zwevende actie button representeert een enkele gepromote actie.

#### Designing layouts for dp
When designing layouts for the screen, calculate an element’s measurements in dp:
dp = (width in pixels * 160) / density
For example, a 32 x 32 px icon with a screen density of 320 equals 16 x 16 dp.

Het is handig om te layouten vanuit een grid.

#### Touch Target size
De touch targets moeten minstens 48 x 48 dp zijn. De aanbevolen target size voor touchscreen objecten is 7-10mm.

#### Structuur
Een permanente app bar, zijnavigatie overlapt alle andere structuren. De interface mag niet verdeeld worden in te veel sectoren, verdelen in sectoren kan gebeuren door witruimte te gebruiken.
Randen kunnen gebroken worden dmv zwevende actie knoppen of kaarten.

#### App bar
De app bar wordt gebruikt voor branding, acties te ondernemen, zoeken en navigatie.
Iconen aan de rechterkant zijn voor app gerelateerde acties terwijl iconen aan de linkerkant gebruikt kunnen worden om de navigatie te openen, ...

Kleur <br>
alle iconen moeten hetzelfde kleur hebben

Afmetingen <br>
Mobiel landschap: 48 dp<br>
Mobiel portret: 56 dp<br>

#### Full Screen
Lean back <br>
Het best full screen type voor het bekijken van content met weinig interactie (vb.videos)
Door eender waar op het scherm te tikken, komt de systeem bar terug tevoorschijn.

#### Zijnavigatie
kan zweven over overlays of vastgezet worden.
Voor mobiel is de breedte van de zijnavigatie gelijk aan de breedte van het scherm - 56 dp.



