@title[Wer Agile sagt muss auch DevOps sagen]

## Wer 
# <span class="bolder">A</span>gile 
## sagt muss auch 
# <span class="dev"><span class="bolder">D</span>ev</span><span class="ops">Ops</span> 
## sagen
<div class="backDiag">
Wieso will eine 150 Jahre alte schweizer Versicherung DevOps einführen?<br/> 
Wer will das? <br/>
Und dürfen die das überhaupt? <br/>
Wie kommt man zu einem DevOps – Team? <br/>
Und was hat das alles mit Agile zu tun?<br/>
</div>

---?image=img/baloise.group.svg&size=contain&color=white
@title[Baloise Group]

---?image=img/hauptsitz.png&size=contain&color=black
@title[Baloise Hauptsitz]

---
@title[Matthias Cullmann]

Matthias Cullmann

* <span class="dev">Organisation</span>
  * Group CO ist mein n+5
  * 0 direct reports und 0 CHF budget
* Titel
  * Wirschaftsinformatiker, Niederes Kader
  * Competence Center Owner Software Engineering
  * Product Owner CI/CD
  * ~~bottle washer~~
* Inhalt
  * https://github.com/culmat
  * https://baselhack.ch
  * http://baselone.ch

Note:

Mal wieder in den Arbeitsvertrag schauen ;-)

---
@title[Wieso DevOps?]

Wieso <span class="dev">Dev</span><span class="ops">Ops</span>?

+++
@title[Continuous Delivery ]

# Continuous Delivery 

+++
@title[Continuous Delivery Mantra]

* Everything is in version control
* Bring Your Own Dependencies
* Automatic Update is the default
* Every Change is released
* Done means released
* Build exactly once
* Don't build it your way
* Slow builds fail
* Production first
* Deployments live and die
* DEV works offline
* humans are no robots
* Never repair a running system
* Everything valuable has an API

+++
@title[humans are no robots]

* Everything is in version control
* Bring Your Own Dependencies
* Automatic Update is the default
* Every Change is released
* Done means released
* Build exactly once
* Don't build it your way
* Slow builds fail
* Production first
* Deployments live and die
* DEV works offline
* <span style="color:#CC0099;">humans are no robots</span>
* Never repair a running system
* Everything valuable has an API

Note:
Let robots do robot jobs

+++?image=img/stop_killer_robots.jpg&size=contain&color=black
@title[Stop Killer Robots]

Note:
Let robots do robot jobs
Artificial intelligence -> DAO, Killerrobots -> Rechenzentrum, einkauf, verkauf, pricing ( werbung ), zertifizierungen. 

---
@title[Effizienz 1]

# How to build an inefficient organisation

Note:
lets build a system

+++?image=img/inefficient.organisation9.svg&size=contain&color=white
@title[Effizienz 2]

+++?image=img/inefficient.organisation8.svg&size=contain&color=white
@title[Effizienz 4]

+++?image=img/inefficient.organisation7.5.svg&size=contain&color=white
@title[Effizienz 7.5]

+++?image=img/v-engine.jpg&size=contain&color=black
@title[Effizienz V]

+++?image=img/inefficient.organisation7.svg&size=contain&color=white
@title[Effizienz 7]

+++?image=img/inefficient.organisation6.svg&size=contain&color=white
@title[Effizienz 7]

+++?image=img/inefficient.organisation5.svg&size=contain&color=white
@title[Effizienz 8]

+++?image=img/inefficient.organisation4.svg&size=contain&color=white
@title[Effizienz 9]

+++?image=img/inefficient.organisation3.svg&size=contain&color=white
@title[Effizienz 10]

+++?image=img/inefficient.organisation2.svg&size=contain&color=white
@title[Effizienz 11]

+++?image=img/inefficient.organisation1.svg&size=contain&color=white
@title[Effizienz 12]

+++?image=img/inefficient.organisation0.svg&size=contain&color=#373936
@title[Effizienz 13]

+++?image=img/antiyoy.jpg&size=contain&color=#373936
@title[Antijoy]

+++
@title[Zutaten ineffizienz]

Gewaltentrennung
Schichten
Schnittstellen

+++
# Conways law

"organizations which design systems ... are constrained to produce designs which are copies of the communication structures of these organizations."

+++
@title[Which kind of system do you want?]

Kapselung
Container
Hohe Kohäsion
Lose Kopplung
Microservices
Agentensysteme

Note:
Agenten = Hohe Verantwortung, eigenständigkeit

+++?image=img/scrum.jpg&size=contain&color=black
@title[Scrum rescue me]

+++?image=img/inefficient.organisation-1.svg&size=contain&color=white
@title[Effizienz -1]

+++?image=img/inefficient.organisation-2.svg&size=contain&color=white
@title[Effizienz -2]

+++?image=img/adam_smith_light.svg&size=contain&color=white
@title[Ineffiziente Spezialisten]
# Ineffiziente Spezialisten

+++?image=img/halbwertszeit.svg&size=contain&color=white
@title[Halbwertszeit des Wissens]

+++?image=img/halbwertszeit.svg&size=contain&color=white
@title[Abnutzung]

"But first me must acknowledge that it's human nature to lose interest in anything after a time...
People cannot be passionate about doing the same thing over and over."
- Ricardo Semler

(langeweile vs motivation) 

---?image=img/desk-notebook-watch-table-book-wood-1293599-pxhere.com.jpg&size=contain&color=black
@title[Geschichte]

# Reisetagebuch

+++?image=img/timeline2009.svg&size=contain&color=white
@title[Trennung  ITCH / CIT]
2009
# Trennung <span class="dev">ITCH</span> / <span class="ops">CIT</span>
 
+++?image=img/timeline2010.svg&size=contain&color=white
@title[Einführung Scrum ITCH]
2010
# Einführung Scrum <span class="dev">ITCH</span>

+++?image=img/timeline2013.svg&size=contain&color=white
@title[Git Self Service]
2013.04
# Git Self Service

+++?image=img/timeline2015.1.svg&size=contain&color=white
@title[Git Owner darf PROD deployen]
2015
# Git Owner darf PROD deployen

+++?image=img/timeline2015.2.svg&size=contain&color=white
@title[JIRA as Release Number]
2015
# JIRA
# as Release Number
 
+++?image=img/timeline2016.svg&size=contain&color=white
@title[PROD First]
2016
# PROD First
vollautomatische deployment pipeline
 
+++?image=img/timeline2017.1.svg&size=contain&color=white
@title[Appserver Migration]
2017
# Appserver Migration

+++?image=img/timeline2017.2.svg&size=contain&color=white
@title[Fachbereich PROD first]
2017.11
# PROD first
# Fachbereich

+++?image=img/timeline2017.3.svg&size=contain&color=white
@title[CICD team]
2017.12
# <span class="dev">CI</span><span class="ops">CD</span> team
 
+++?image=img/timeline2018.1.svg&size=contain&color=white
@title[CIT Ansible Schulung]
2018.01
# Ansible Schulung
# <span class="ops">CIT</span>
<span class="dev">ITCH</span> Kollegen sind eingeladen

+++?image=img/timeline2018.2.svg&size=contain&color=white
@title[Container Platform]
2018
# Container Platform

---
@title[Erfolgsfaktoren] 

# Erfolgsfaktoren

+++?image=img/chophead.svg&size=contain&color=white
@title[demonoply]

+++?image=img/1openfriday.png&size=contain&color=black
@title[Open Friday]

+++?image=img/scrum_master_as_a_service.svg&size=contain&color=white
@title[demonoply]

# scrum master
# as a service

+++?image=img/4ears.svg&size=contain&color=#a3cdfb
@title[4 ears]

+++?image=img/container.jpg&size=contain&color=black
@title[container]

Note: 

100 x Quantensprung, Züge 100 x schneller 

---
@title[Fragen]

# Fragen?

---
@title[Credits]

## Credits

---
@title[Lese-Empfehlungen]

## Lese-Empfehlungen

* https://www.amazon.de/Continuous-Delivery-Deployment-Automation-Addison-Wesley/dp/0321601912
* https://www.amazon.com/Seven-Day-Weekend-Ricardo-Semler/dp/0099425238
* https://speakerdeck.com/leandus/thank-god-its-open-friday-mit-corinna-baldauf

---
@title[License & contributions]

![CC0 logo](https://licensebuttons.net/p/zero/1.0/88x31.png)

To the extent possible under law, the person who associated CC0 with this work has waived all copyright and related or neighboring rights to this work. 


Contribute under https://github.com/baloise/pitches/blob/WerASagtMussAuchDSagen/PITCHME.md

