# About I2P ( The Invisible Internet Project )

I2P (The Invisible Internet Project), is a fully encrypted private network layer that has been developed with privacy and security by design in order to provide protection for your activity, location and your identity. 
The desktop software ships with a router that connects you to the network and includes applications for sharing, communicating and building.

The network has the same capabilities as the Internet: you can create and vistit I2P sites, email, create forums and share content. If you are an application developer, you can create your own I2P applications. 
The protocol and software is Free-Open Source and community built. It has been in active development since 2001.

![img](https://user-images.githubusercontent.com/50714166/165985249-800bac22-818b-4b69-abe1-5f9e4cad500e.png "style=height:500 width:200")

# Getting Started
1. Create a Transifex Account:
If you have not have a Transifex account, you can create one [here](https://www.transifex.com/signup/).

2. [Join the I2P Translation Team](https://www.transifex.com/otf/I2P/):

3. [Download I2P Desktop](https://geti2p.net/en/)
    [Download I2P Android ](https://play.google.com/store/apps/details?id=net.i2p.android)

Download I2P for Desktop and or I2P for Android. This is an important step to familiarize yourself with I2P.  I2P desktop offers the full range of application access, and admin options. I2P Android has less options and different usability workflows. This is also where you can familiarize yourself with the original English strings and translations in context.

4. Review the **Translation Guidelines** (https://geti2p.net/en/get-involved/guides/new-translators).
5. Review the resources, and guidelines for specific language teams: https://wiki.localizationlab.org/index.php/Category:Language_Teams


# Translation Priorities

**Urgent**

routerconsole

Website

readme

Router Status

welcome

I2P News

Core Library

**High**

HTTP proxy error pages

manpages

Hidden Services Manager (i2ptunnel)

Web Server Help (eepsite)

I2P Android

AddressBook (susidns)

I2P Android Helper Library

**Normal**

System Tray ( Desktop GUI)

Website /misc/

Command line option errors (getopt)

Email (SusiMail)

Website/docs

I2PSnark Bittorrent Client

Streaming

itoopie-router control app

Router Startup Script (i2prouter)

Website /about/

Website /comparison/

Website /research/

Website /get-involved/

Website /blog/

countries

Debian Installer

# Localization Focus

Language outreach needs to consider router distribution as well as where there is a need for using I2P. This requires strategy for localization balance so that it supports building a greater anonymity sets with more routers in regions where I2P does not face restrictions for operation.

To this end, focusing on localization efforts in French, Mandarin, and Portuguese can have a benefit for strengthening overall router distribution and creating a better opportunity for a increased anonymity for people who need to use I2P in more restricted regions.

Our current requested languages are:
Turkish
Russian (Traditional, Ukrainian)
Greek
Slovenian
Spanish(Latin America)
Turkmen

# Regarding Strict Countries and Hidden Mode: Protection For I2P Participants Where Use May Be Prohibited

I2P provides measures within its network and protocol design that provide circumvention, privacy and DPI protection for traffic and communication.
What supports the I2P network technical capabilities is router distribution: having as many people as possible all over the world participating in the network. In recognition of countries where making use of privacy and anonymity technologies, protection for individuals participating in routing traffic have been put in place.

The Java implementation of I2P includes a "Strict Countries List." This list is used to decide how routers should behave within regions where applications like I2P may be limited by law. While no countries that we know of prohibit using I2P, some have broad prohibitions on participating in routing traffic for others.

The development team relies on the research provided by civil and digital rights organizations in order to make decisions that offer protections for its users. In the case of compiling a Strict Countries list, the ongoing research provided by Freedom House has been referenced. General guidance is to include countries with a Civil Liberties (CL) score of 16 or less or an Internet Freedom score of 39 or less (not free).

Routers that appear to be in the "Strict" countries will automatically be placed into "Hidden" mode.

**What Hidden Mode Means**

When a router is placed into hidden mode, three key things change about its behaviour.

1. It will no longer publish a routerInfo to the NetDB. (Network database)

2. It will no longer accept participating tunnels.

3. It will reject direct connections to routers in the same country that it is in.

These defences make the routers more difficult to enumerate reliably, and protect them from restrictions on routing traffic for others.

**Router Distribution and Traffic Considerations**

1. Hidden mode routers need non-hidden routers to provide them with a path to participate in the network. More is usually better, because this is where enumeration of non-hidden routers to interfere with their tunnels and connectivity might happen.

2. More traffic on the network results in better protection for everyone.

3. The network needs mostly non-hidden routers.

The Strict Countries list can be found here : https://geti2p.net/en/about/restrictive-countries
