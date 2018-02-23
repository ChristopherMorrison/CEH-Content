# CEH-Content
Collection of presentations and activities I've prepared for CYBER@UC, the UC OWASP chapter, focusing on the basics of the Certified Ethical Hacker (CEH) curriculum.

I am not an authorized CEH educator so these presentations will not count as CEH training sessions. However they should be a good start for understanding CEH content.

## Contents
[1: Introduction to Ethical Hacking](#1-Introduction-to-Ethical-Hacking)

[2: Systems Overview](#2-Systems-Overview)

[3: Cryptography Overview](#3-cryptography-overview)

## 1: Introduction to Ethical Hacking
[Slide Deck](https://docs.google.com/presentation/d/1TtOrD60MqqBp2jlWBEmcxb-_07pBMzGstDILy7Lp4u8/edit?usp=sharing)
#### Notes
- This is just the boilerplate of CEH in general, nothing to exciting

## 2: Systems Overview
[Slide Deck](https://docs.google.com/presentation/d/1qyFsFAmPrwXTrZpHmKUd9HqqAHjJk3DQRpRJtICLlH0/edit?usp=sharing
[Activity Slide Deck](https://docs.google.com/presentation/d/1r0jZh6l_-otz5E3umKjCD8pufRoJRL4O4yQoiAgNADE/edit?usp=sharing)
#### Notes
- Goes from the average single user computer all the way up to enterprise networks.
- Tries to display both network topology and protocols so it is without doubt lacking in some areas
- This is more of a catch up slide deck for people who know of such things but may not know exactly what they are or how they go together
#### Activity Notes
- The activity was to hosted on an AWS free instance
- The AWS instance had a VPN allowing people to run tools on an Ad-Hoc Cyber Range
- The AWS instance also had an Apache 2 instance sitting at port 63215 which both allowed us to have some fun in finding it and to demonstrate the slowloris DOS attack which cripples Apache 2 webservers
- Wireshark is touched here but really deserves its own workshop
- The prize for the aluminum challenge was a large piece of aluminum metal

## 3: Cryptography Overview
[Slide Deck](https://docs.google.com/presentation/d/17K8OSPL5mTLXwjHsPPlchVhKPDQEOr57LpW1Zux9n4s/edit?usp=sharing)
#### Notes
- The presentation was small enough that the presentation and activity can be in one slide deck
- The activity at the end was to identify a file from part of its hash and then to use a hash cracker and wordlist to find the password from the possible passwords list
- All of the passwords used in this presentation were from [SecLists](https://github.com/danielmiessler/SecLists) to make the hashes crackable
