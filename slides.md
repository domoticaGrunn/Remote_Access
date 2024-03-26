# Remote Access

---

## Wat is het niet ...

<p class="fragment" data-fragment-index="3">Human = Mens/Persoon</p>
<p class="fragment" data-fragment-index="1">Presence = Aanwezigheid</p>
<p class="fragment" data-fragment-index="2">Detection = Waarnemen</p>

<!-- .slide: data-menu-title="Home Assistant" data-background-image="img/et_phone_home.gif" data-background-opacity="0.6" -->

Note: Het "Mandela-effect" is het fenomeen waarbij we iets verkeerd onthouden en waarbij die fout zo hardnekkig is, dat ze zich als een nooit bestane herinnering in onze hersenen gaat nestelen. Drew Barrymore, wie heeft haar herkend? 1982: "E.T. home phone"

--

## Wikipedia

> Human presence detection is a range of technologies and methods for detecting the presence of a human body in an area of interest (AOI), or verification that computer, smartphone (or other device controlled by software) is operated by human.

<p class="fragment" data-fragment-index="1">Hmm, Human Operated?</p>

--

## Human Sensing

> Human sensing (also called human detection or **human presence detection**) encompasses a range of technologies for detecting the presence of a **human body in an area** of space, typically without the intentional participation of the detected person.

---

## Home Automation

> "Automatiseren van processen,
> in en om een woning"

<p class="fragment" data-fragment-index="1">Event-driven orchestratie,</p>

<p class="fragment" data-fragment-index="1">reageren op een gebeurtenis ...</p>

Note: Orchestratie of Choreografie

--

## Events

- Bewoner komt thuis.
- Bewoner gaat weg.
- Twee bewoners, eentje gaat weg.
- Niemand thuis.
- Iemand is thuis maar geen bewoner ...

<p>&nbsp;</p>
<p class="fragment" data-fragment-index="1">Verschillende events, </p>
<p class="fragment" data-fragment-index="2">verschillende acties</p>

--

## Event & Sensing

![](img/indiana-jones-harisson-ford.gif)

Wat meet een sensor?

---

## Sensing

- Acoustic sensors
- Image recognition of human shapes
- Infrared detectors
- Pressure-sensitive (floor tiles)
- Radar
- Chemical sensors
- Personal device detection via Wi-Fi or Bluetooth.

Note: Personal device: mobieltje, of smart-watch. Waarmee/Hoe detecteren we een persoon? Light curtain (doorbreken van IR stralen)

--

## Acoustic sensors:

- Meet: geluid
- Voorbeeld: Google Nest, Amazon Echo, Apple HomePod

![](img/google_nest.png)

--

## Image recognition

- Meet: Beeld analyse, persoon of gezicht
- Voorbeeld: Camera bewaking, deurbel-camera

![](img/human-presence-detection.jpg)

--

## Infrared detectors

- Meet: Infra-rood licht
- Voorbeeld: PIR

![](img/passive-infrared-sensor.png)

--

## Pressure-sensitive

- Meet: Verschil in druk
- Voorbeeld: Druk-sensor onder een deurmat of onder de latten-bodem van het bed.

Note: Deurmat is tijdelijk, bed voor langere duur.

--

## Radar

- Meet: Verschuiving in radio-frequentie
- Voorbeeld: FMCW 24 GHz

![](img/FMCW-24GHz.png)

Note: Doppler sensor. "That guy with the Swiss accent" review, FMCW 24 GHz

--

## Chemical sensors

- Meet: Chemische samenstelling van de omgeving in gas of vloeistof.
- Voorbeeld: CO<sub>2</sub>-sensor, rookmelder

<!-- .slide: data-menu-title="Chemical sensors" data-background-image="img/rookmelder.jpg" data-background-opacity="0.3" -->

--

## Personal device detection

- Meet: Signalen van een persoonlijk device
- Voorbeeld: Smart-watch, Smart-phone, Hals-sensor, Schoen

<!-- .slide: data-menu-title="Personal device detection" data-background-image="img/map.png" data-background-opacity="0.3" -->

---

## Home

Garage & Badkamer

![](img/aquara-motion-sensor.png)
<!-- .slide: data-menu-title="Home" data-background-image="img/home.jpg" data-background-opacity="0.2" -->

--

## Garage

- Sensor: Aquara motion sensor
- Actie: Shelly zet garagelicht aan (3 min.)

![](img/Shelly1.png)

--

## Badkamer

- Sensor: Aquara motion sensor
- Actie: Licht gaat zachtjes aan

![](img/hue-ceiling-light.png)

--

## Home Assistant

- Bewegings-sensoren via Zigbee aangestuurd via Zigbee of Wi-Fi.
- Tot nu toe twee ruimtes:
    - Garage en
    - Badkamer
- ToDo lijst:
    - Radar sensoren voor de studeerkamer
    - Bewegings-sensoren vervangen door Radar sensoren

<!-- .slide: data-menu-title="Home Assistant" data-background-image="img/homeassistant.png" data-background-opacity="0.2" -->

---

## Conclusie

- Tot ziens PIR, hallo Radar
- Snelle gewenning, veel gemak
- Batterij maar toch liever bedraad

---

<!-- .slide: data-menu-title="That's all folks" data-background-image="img/Thats_all_Folks.jpg" data-background-opacity="1.0" -->
