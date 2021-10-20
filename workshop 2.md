---
lang: en-Us
title: "Scientific Research Methodology"
subtitle: "Workshop 2"
authors:
  - Arsène Lapostolet
  - Maud Gellée
...

# Introduction

What is smart city
what is smart grid
sustainabilty and energy saving

# Challenges of an adequate smart grid

## Components - Arsène

Ubiquitous Computing / IoT

Virtual power plants

## Processes - Maud

Demande Reponse (DR) balancing & aggregation

There are already many studies concerning demand response balancing in smart homes, but it is becoming necessary to extend it to smart cities scales. But, demand response is an effective measure to influence the behaviors of demand, in order to save money and energy.

Demand response is the variation of the amount of energy usage from the normal consumption pattern in response to electrecity prices. The goal of managing the demand response is to improve the power systems' flexibility (A power system flexibility is the extent to which a power system can modify electricity production or consumption in response to variability expected or otherwise) and peak load scheduling (for example by moving peak load to an off peak hour). Thanks to this management, it will decrease energy costs for customers and the producer will be able to manage available energy more accurately with less cost.  

In order to maximise demand response balancing benefits, energy providers have create demand response programes, that are entirely dependant on consumer participation. There are two types of demand response schemes : incentive-based and price based. The first one encourage consumer ton adapt their consumption depending on a crontactual agreement, while the second one offers to customer time varying rates that reflect the value and cost of electricity for different time period (peak load are when energy is the most exepensive). For exemple, in France there was hours in the day, that were called "heures creuses" where elecrecity costed less (usally middle of the day when everyone was at work). 

However, demand response balancing is becoming harder as the power system changes and becomes less and less centralized. Indeed, new energy sources must be integrated on the existing power system, and the overall power system is only increasing in size and complexity as time goes by. There is also the apparition of prosumers, those are actor of the power system that consume and produce energy, they will also store surplus energy that they are recieving in order to sell it (it is called energy trading). 

Finally, there could be the solution of Energy storage system (ESS) that have been mentionned earlier, that stores surplus electric powet to redistribute it later, this systems are essential, and needed in every power system to avoid to muche energy loss, but are also very expensive, where best demand response model could replace most ESS, by avoiding surplus production.

This is where smart grid would actually enable an efficient demand response management despite all the difficulties that are appearing. Smart grid would enable bi-directional communication between end costumer, energy providers and prosumers of power spike, poer loss and their localization. Finally, even if classical demand response balancing are still quite usefull, the main problem is that all consumers are penalized by little numbered selfish consumer that rise global energy consumption level, and increase energy prices. With smart grid and location system like GIS (that we will see later in this paper) it would be possible to locate more accurately the energy consumption of each individual in order to adapt prices depending on personal consumption.

Low voltage network analysis

For now, most studies concerning the distribution of network towards smart grid have focused on automation of medium or high voltage network. Hopefully, this has change recently after the rapid growth in the penetration of distributed energy resources in LV network grid.

We are now going to see what is low voltage network analysis and why it could become essential to smart grid. First, what is low voltage network : in a power system, there are three level of voltage, high, medium and low. Most customer are connected to the distribution transformaters via low voltage network (1kV to 52kV). Low voltage network is then connected to medium voltage network, which is then connected to high voltage network to distribution system operators. Thus, it is this network that contains the most precise information about the user energy consumption behavior. As we saw in the last part, demand response is the key to improve energy savings, but for demand response balancing to be as efficient as possible, we need all the information possible to make the best choices, and low voltage network contains many of these usefull datas. 

These information are already collected by what are called automatic meters (like the "compteurs linky" in France). However those permit only one way information transfers, that are mostly used for billing and are not exploitable for real time demand response management, since there would be to many information to process. But some duties and new tasks that will appear with smart grid can be decentralized to lower level automation system like smart meters. As we saw earlier, smart meters are a component of the smart grid, that implement a two-way communication to detect temper, theft, manage peak demand or fault and can help monitor and make planning concerning the network. 

Simple decision could be made at lower level and smart meters would only transfer information needed for billing by DSO, which could concentrate the global smart system on High and medium voltage management. Thanks to LV network analysis, it would be possible, among other things to : 

- manage LV network fault by providing to the control center real time informationabout LV network fault and the cicumstances, in order to reduce outage time and improve safety of LV network operations. Smart meters are able to detect fault, by sending information to the Control center about the faulting LV network, the lattercould identify the faulted area with more precision by trying to locate other smart meters presenting issues. If no other smart meters are faulted, then it is certain that the problem comes from the LV network, otherwise it is probably in the MV network. In any case, precise information and localization can be sent to the DSO.
- manage power flows and voltage level in the network, by controlling DERs by means of smart meters and HEMs. Doing so would manage congestion inside the network, to detect where and how much control is needed (increse/decreqse demand/production).

Big Data / ML

Finally, we will see how the decision making concerning Demand response process will be made via Big data and machine learning. 

Machine learning is a branch of Artificial Intelligence where machine learn without direct invelvement of human, by looking for pattern and relation in data. Machine learning based on Big data reduces decision making error and uncertainty, while offering better understanding of users behaviors, and improving interconnectivity of components. 

With Machine learning based on Big Data we could in addition: 
- estimate transformator loss of life, by pryoriazing and maintenance necessities and warn of needed replacement before outage
- Power quality events detection, making smart grid self healing
- Energy dispach decision, by forecasting demand response peak to avoid loss or overload
- improve security, since many information will be exchange via Wifi, and many of those information could be considered as private one, it is needed to be extra careful. ML could detect abnormal behavior, intrusion and maliciouse activities to warn competent actors before to much damage have been made. 

However fully labelled data are necessary and some events (like transformator loss of life) are rare so the corresponding model would take time before being correct. Moreover, for the security information, it is necessary to realise that cyberattacks evolve quickly so the model should be frequently update. 

Finally, Big data could also be used in order to increase DSO and customer profit by using Business intelligence to comprehend user's precise behavior and propose solution to optimize pricing. 

# Information Systems to the rescue - Arsène

## Architectural constraints

Distributed P2P Architecture

Networks & Protocols

## Software solutions

GIS

Middlewares

Service Oriented Architecture

# Stakes of a successful smart grid - Maud

## The problems

Climate change

Urban population through the roof

***j'ai fait une seule partie en fait sinon les deux etait trop vide***

Nowadays, we are facing the issues of an overall increasing population in most contries and a mouvement of population towards urbanized area. Major cities currently only occupy 5% of the earth, but 68% of people will live in cities in 2050. Moreover, cities account for 75% of the world's fossil fuel usage, and it is not going to decrease over the years. 

We will probably have other pandemic like covid 19 in future years, and lockdown situation have redefined the role of our urban environment with the democratisation of e-learning, work from home or remot medical assistance. With each of theses new behavior comes an increase in the consumption of electricity. 

Sadly the increase in energy consumption is not without impact over the world. Our energy production does not mostly come from renewable energy like wind or solar energy. Even if some contry like France do not rely on fossil fuel to produce its energy, in 2019, 64% of the world's energy cqme from fossil fuels, which is the main reason behind global warming. With global warming comes many disasters that are well known, including the rise of the ocean, which would probably increase the cities population since shore would be flooded.

## Solution

Energy Saving

With the urban population that will increase, also comes the question of energy repartition and management. While we could just construct more power plants or other energy resources, we know for certains that most of them will not be renewable energy, and would create a vicious circle. 

Hopefully, there is another way. As we explained along the paper, smart cities aim to improve energy saving management, and the smart grid is one of the many solution that we have to avoir energy waste. By saving energy, we could tackle the future proble;e of urban population increase and avoit the creation of new energy production that could harm the planet. 

Obviously, there are other big consideration to take into account and that samrt cities could help tackle, like people's health, smart tensportation, security of the individuals ... 

# Discussions

# Conclusion








