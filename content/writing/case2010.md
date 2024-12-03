---
title: "CASE: A Framework for Computer Supported Outbreak Detection"
date: 2010-03-12
lastmod: 2024-12-03
tags: ["outbreak detection", "software", "epidemiology"]
author: ["Baki Cakici", "Kenneth Hebing", "Maria Grünewald", "Paul Saretok", "Anette Hulth"]
summary: ["We present a technical framework designed and implemented at the Swedish Institute for Infectious Disease Control for computer supported outbreak detection, where a database of case reports for a large number of infectious diseases can be processed using one or more statistical methods selected by the user."]
description: ["We present a technical framework designed and implemented at the Swedish Institute for Infectious Disease Control for computer supported outbreak detection, where a database of case reports for a large number of infectious diseases can be processed using one or more statistical methods selected by the user."]

editPost:
    URL: "https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/1472-6947-10-14"
    Text: "BMC Medical Informatics and Decision Making"
---
---

##### Background
In computer supported outbreak detection, a statistical method is applied to a collection of cases to detect any excess cases for a particular disease. Whether a detected aberration is a true outbreak is decided by a human expert. We present a technical framework designed and implemented at the Swedish Institute for Infectious Disease Control for computer supported outbreak detection, where a database of case reports for a large number of infectious diseases can be processed using one or more statistical methods selected by the user.

##### Results
Based on case information, such as diagnosis and date, different statistical algorithms for detecting outbreaks can be applied, both on the disease level and the subtype level. The parameter settings for the algorithms can be configured independently for different diagnoses using the provided graphical interface. Input generators and output parsers are also provided for all supported algorithms. If an outbreak signal is detected, an email notification is sent to the persons listed as receivers for that particular disease.

##### Conclusions
The framework is available as open source software, licensed under GNU General Public License Version 3. By making the code open source, we wish to encourage others to contribute to the future development of computer supported outbreak detection systems, and in particular to the development of the CASE framework.

##### Citation