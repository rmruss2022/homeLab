---
description: >-
  ATTENTION! Go to https://russellm22.gitbook.io/homelab/ for documentation!
  Hello there! Welcome to Matt's homelab automation documentation. Here I will
  explain the purpose and functionality of my work
---

# Welcome to Matt's Home Automation!

### The Inspiration

Towards the end of my sophmore year, I started an interest in the HomeLab subreddit. People had grandious racks of servers and networking equipment that blew my software limited mind. I decided to embark on my own homelab journey by building out a custom home automation system.     

### Beginnings

I began outlining the functionality I wanted control, and narrowed my focus to lighting, temperature, and security. In hindsight, the homelab subreddit created a slightly misleading idea of what processing power was necessary for this project. I bought a Dell T420 PowerEdge Server, Router, Switch, and Wirless Access Point to understand the secrets behind these homelab-er's enterprise networking setups. 

![R.I.P Dell T420 PowerEdge](.gitbook/assets/mydellpic.jpg)

Now I was ready to rock - I installed pfSense on my router and went to work creating VLAN's for my Wifi, setting up a VPN for some VLAN's, perfecting firewall rules, and securing my network with Suricata IDS \(Intrusion Detection System\). 

Initially, I set up Proxmox virtualization software on the PowerEdge. I planned to set up my home automation web server on one virtual machine and separate other envioronments for a Python cryptocurrency trading bot and Plex Media Server. While I learned a lot about iDRAC and virtualization, it proved unnecessary long term. I transferred my webserver to a Raspberry Pi 4 and suffered no loss of performance. 

### LAMP Web Server

I knew I wanted my own system  

### Let There Be LIGHT!

The first application of any self-respecting home automation system has to be lighting.  

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







## Smart Home Data 

I began my interest with smart home applications of a homelab. My goal was to aggregate data generated from within my own house and layer psychological principles to reach a greater understanding of some human behavior or cognition. After spending the summer reading about the implications of smart home technology in psychological research and building my own smart home \(with the intent of generating data for my own case study\), I have come to a greater understanding of this evolving technology's role in our daily lives, mental health, and medical needs.            

![](.gitbook/assets/psycstudy.png)

## Limitations

Before I discuss my findings, it is important to understand and respect the limitations of smart home technology for varying use cases. I live with three roommates, so when I started planning the technology to integrate into the house, I had to keep the privacy of my roommates in mind.      



