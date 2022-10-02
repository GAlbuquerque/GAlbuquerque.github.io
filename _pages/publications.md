---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
I am an Applied Microeconomist with an interest in understanding violence. My research employs historic and administrative data to understand causes and consequences of crime and political repression, with a focus in Guatemala and Mexico. Here is my [research statement].(res_statement2.pdf)

<br/>

* <span style="color:black;font-weight:700;font-size:20px"> [From Violence to Violence? The Long Term
Effects of Conflict on Homicide Rates](Violence_to_Violence.pdf)  </span>

This paper studies the long term impact of large scale temporary violence
in long term homicide rates. I analyze the case of Guatemala’s
civil war massacres and assemble data on their locations and homicides
between 2016-2019, to test whether there is association between the two.
I find that highly victimized municipalities have fewer homicides today.
Exploring precipitation variation as an instrument for massacres, I provide
evidence that such relation is causal. Generalized trust is also higher in
municipalities with more massacres, suggesting a mechanism connecting
past violence and present peace through increased local cohesion.

* <span style="color:black;font-weight:700;font-size:20px">Indigenous communities and the containment of drug-war
violence </span>

Following a policy of increased repression to drug trade, Mexico experienced a large increase
in violence (drug war) since 2007. However, not the whole country was equally affected and
a large gap opened between majority indigenous and non-majority indigenous municipalities'
homicide rates since then. In this paper, I show that the presence of a indigenous majority
prevented a increase in homicide rates. Municipalities with that characteristic were less likely
to have the presence of a major Drug Trade Organization and their inhabitants were less likely
to be imprisoned by drug-trade related crimes. Finally, I show that within indigenous majority municipalities, the
ones with autonomous institutions are the ones with less homicides, less DTO presence and less imprisonment for drug-trade related offenses.

* <span style="color:black;font-weight:700;font-size:20px"> Civil-Police relations in an authoritarian context: An exploration of the Guatemalan
National Historic Police Archive </span>

This project explore police archives produced at a time when Guatemala had an authoritarian government fighting a leftist insurrection. I am leveraging recent machine learning developments (eg. OCR, Topic Modelling) to transcribe the whole police archive, organize it and quantify its contents in an automated and easily replicable way. In the next months, I will investigate how much police effort was directed to different goals, like combating robbery or repressing political dissent. Additionally, I will research how this effort varied with time and space, and whether this variation was correlated with the political changes Guatemala went through the studied period (1980-1990). 

<br/>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
