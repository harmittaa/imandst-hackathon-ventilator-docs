# Recommendations for makers of emergency ventilators in México


# Background 

What is the problem, what is the solution, call to action, which value you add. Don't be academic, better be hands on.

Of the people who contract COVID-19 virus roughly 5 % percent develop serious or critical symptoms [[https://www.worldometers.info/coronavirus/](https://www.worldometers.info/coronavirus/)]. The patients with these statuses can be in need of ventilator support. This sudden spike has created a tremendous demand for ventilators, as the medical facilities are not equipped for a pandemic the COVID-19. Due to the shortage of mechanical ventilators, the maker community has come together to build last resort emergency ventilators [[https://www.bbc.com/future/article/20200401-covid-19-the-race-to-build-coronavirus-ventilators](https://www.bbc.com/future/article/20200401-covid-19-the-race-to-build-coronavirus-ventilators)].

The desire to help has created a multitude of different open source emergency ventilator designs, especially those that are aimed for makers to build from locally sourced parts [[https://github.com/PubInv/covid19-vent-list](https://github.com/PubInv/covid19-vent-list)]. However, the projects are in varying stages of development, from those with first prototypes just being built to those which have are already in clinical trials [[http://www.germanstrias.org/news/195/new-ventilator-device-developed-by-the-hospital-clinic-germans-trias-i-pujol-and-barcelona-university-with-protofy-xyz-gets-the-go-ahead-from-the-aemps-for-clinical-trials](http://www.germanstrias.org/news/195/new-ventilator-device-developed-by-the-hospital-clinic-germans-trias-i-pujol-and-barcelona-university-with-protofy-xyz-gets-the-go-ahead-from-the-aemps-for-clinical-trials)].

Selecting a design to build requires thorough consideration, as malfunctioning of a device could lead to serious injury or even the death of the patient. This document is intended to facilitate that decision making process and to provide up-to-date information on participating to building emergency ventilators. This document addresses low-cost, last resort ventilators that can be built by the makers for use when the existing methods for helping patients have been exhausted.


# Regulatory considerations

The medical ventilators fall under Class II medical devices, meaning that they would require, among other testing, clinical trials before being allowed to be used in hospitals [[https://www.nsmedicaldevices.com/analysis/uk-ventilator-regulation-coronavirus/](https://www.nsmedicaldevices.com/analysis/uk-ventilator-regulation-coronavirus/)]. As the emergency ventilators discussed here are meant to help with acute ventilator shortage, the time frame nor the resources of individual makers, do allow for a full clinical trial to be performed. With this in mind, it is unlikely that, at least at the current state of virus in Mexico, hospitals would take into use any home made ventilators.

However, the ventilators discussed here are aimed to be provided as last resort devices for the medical institutions with the most dire needs. Considering the rapid advancement of the pandemic, it is possible that the requirements for the medical ventilators could be laxed and even last resort ventilators could be put into use in hospitals.


## Documentation

The Mexican government has released a document describing the requirements for the ventilator production: [https://www.gob.mx/cofepris/articulos/disposiciones-para-la-adquisicion-y-fabricacion-de-ventiladores-durante-la-emergencia-de-salud-publica-por-coronavirus-2019-covid-19?idiom=es&fbclid=IwAR0x3wMG-P88LaqueSmDusmNnOzzFP3M1LCdMZwnJ8qWbqAirB6E3e7qCds](https://www.gob.mx/cofepris/articulos/disposiciones-para-la-adquisicion-y-fabricacion-de-ventiladores-durante-la-emergencia-de-salud-publica-por-coronavirus-2019-covid-19?idiom=es&fbclid=IwAR0x3wMG-P88LaqueSmDusmNnOzzFP3M1LCdMZwnJ8qWbqAirB6E3e7qCds). It should be noted that these provisions are only valid during the pandemic.

The Colegio de Ingenieros Biomédicos de México A.C. has also published a set of regulatory requirements for mechanical ventilators available here: [http://cib.org.mx/Covid19/20200406EspecV1.pdf](http://cib.org.mx/Covid19/20200406EspecV1.pdf).


# Ventilator requirements

The current requirements for emergency ventilators are listed in the above links. Further information regarding the requirements can be found from a number of different governmental sources such as:

[https://www.agorize.com/en/challenges/code-life-challenge/pages/guidelines?lang=en](https://www.agorize.com/en/challenges/code-life-challenge/pages/guidelines?lang=en)

[https://www.gov.uk/government/publications/coronavirus-covid-19-ventilator-supply-specification/rapidly-manufactured-ventilator-system-specification?fbclid=IwAR2IgOyENgHJTsLouIiikpuiwgwupdB8d8Aun2he8nzMPWGfhBVhaG_sMqo](https://www.gov.uk/government/publications/coronavirus-covid-19-ventilator-supply-specification/rapidly-manufactured-ventilator-system-specification?fbclid=IwAR2IgOyENgHJTsLouIiikpuiwgwupdB8d8Aun2he8nzMPWGfhBVhaG_sMqo)


# Open source designs

Two open source designs, Oxygen and e-vent, have been selected here for local makers to implement.

Oxygen ([https://www.oxygen.protofy.xyz/](https://www.oxygen.protofy.xyz/)) features two different versions: the M version intended for makers and the IP version intended for mass production. The latter has passed clinical trials. The downloadable materials are available here: [https://www.oxygen.protofy.xyz/download](https://www.oxygen.protofy.xyz/download).

MIT E-VENT ([https://e-vent.mit.edu/](https://e-vent.mit.edu/)) is a low-cost emergency design developed by a team at the MIT. The materials for the E-Vent are available here: [https://e-vent.mit.edu/resources/downloads/](https://e-vent.mit.edu/resources/downloads/).


## Safety

The first selection criteria for the designs is safety. Both of the projects have gone through at least some level of testing, the Oxygen project’s IM model has passed clinical testing in Spain while the E-Vent is has undergone the fourth porcine study. The latter cannot be considered a clinical test, however compared to a plethora of other designs this can be considered to be at an advanced stage.


## Price

Second criteria is the price of manufacturing. As the devices are intended to be built by makers with limited resources, the price must be relatively low. Both of the selected projects aim to provide a low-cost, easily producible device.

The Oxygen project has over 150 builds [source], hinting at the relative ease of creating it. The Mexican maker community has commented that the estimated price for the production of the Oxygen IP model is $12,000 MXN.

The MIT E-vent does not mention specific prices, besides that it is a low-cost device.


## Community

Third criteria is the community. The importance of the community is especially relevant when makers source materials for their builds. As both of the chosen designs have been developed outside of Mexico, it is important that the local maker community is able to share experiences about materials and the build process.

The Oxygen project has a very lively community on Discord which features both English and Spanish channels ([https://discord.gg/yyYQxEG](https://discord.gg/yyYQxEG)), as well as a Mexican Oxygen makers’ group ([https://www.facebook.com/groups/1347740022075853](https://www.facebook.com/groups/1347740022075853)). 

The E-vent project is actively discussed on the project’s website.


<!-- Docs to Markdown version 1.0β21 -->
