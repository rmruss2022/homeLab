---
description: >-
  ATTENTION! Go to https://russellm22.gitbook.io/homelab/ for documentation!
  Hello there! Welcome to Matt's homelab/automation documentation. I am a VT
  student studying computer science and psychology.
---

# Welcome to Matt's Home Automation!

### Introduction 

Towards the end of my second year, I began an interest in the HomeLab subreddit. I wanted to learn more about networking and devlop a system I could experiment with new technologies. Unsure of where exactly to begin, I looked towards the most obvious and exciting option: home automation. Throughout the summer, I built open source solutions for lighting, temperature control, and security while learning about the psychological applications this data generates. 

### Stack

There are many players in the home automation market offering their own nuanced ecosystem. Amazon, Google, and Apple offer top tier software, device compatibility, and voice assistant, but lack developer control. They are centralized services that work out of the box, and for most consumers, that is the best option. Open source services such as Home Assistant or OpenHab offer a plug and play format that offers high compatibility while also giving the user more control over the tech. These great solutions inspired the functionality and design I wanted out of my system.

These specifications led me to a LAMP \(Linux, Apache, MySQL, PHP\) webserver. This traditional stack allowed me to control my devices from a web page anyone on the network/wifi could access. There was no separate app that would eliminate desktop access or necessitate my roommates to download \(further splitting into iOS/Android\). There was just a local IP that could be saved to any phone home screen. 

### Lighting

* hue lights
* php http curl requests
* load, off/on, brightness, scene

### Security

* rf lock
* rp4 flask api receives call from web server
* circuit - optoisolator connects to remote to turn on button when signal received from api 

### Thermostat

While there are many smart thermostats on the market, I needed an API versatile enough to fit into my ecosystem. Unfortunately, I could not find a suitable candidate within a reasonable price range. Therefore, I was left to create my own. I researched the wiring for my AC system, and wiried a relay switch 

### Sensors

limsum



{% tabs %}
{% tab title="Lighting Front End" %}
![](.gitbook/assets/img-8332.jpg)
{% endtab %}

{% tab title="Thermostat Front End" %}
![](.gitbook/assets/img-8391.jpg)
{% endtab %}

{% tab title="Thermostat Hardware" %}
![](.gitbook/assets/img-8357.jpg)
{% endtab %}
{% endtabs %}







## Psychology impliciations of Smart Home Data 

I began my interest with smart home applications of a homelab. My goal was to aggregate data generated from within my own house and layer psychological principles to reach a greater understanding of some human behavior or cognition. After spending the summer reading about the implications of smart home technology in psychological research and building my own smart home \(with the intent of generating data for my own case study\), I have come to a greater understanding of this evolving technology's role in our daily lives, mental health, and medical needs.            

![](.gitbook/assets/psycstudy.png)

## Limitations

Before I discuss my findings, it is important to understand and respect the limitations of smart home technology for varying use cases. I live with three roommates, so when I started planning the technology to integrate into the house, I had to keep the privacy of my roommates in mind.      



