---
title: "On SMS Phishing Tactics and Infrastructure"
collection: publications
permalink: /publication/2024-02-01-SMS-Phishing
excerpt: 'A deep-dive into the tactics and infrastructure used by SMS Phishing Operations.'
date: 2024-02-01
venue: 'the 2024 IEEE Symposium on Security and Privacy'

---


**Abstract**: In 2022, the Anti-Phishing Working Group reported a 70% increase in SMS and voice phishing attacks. Hard data on SMS phishing is hard to come by, as are insights into how SMS phishers operate. Lack of visibility prevents law enforcement, regulators, providers, and researchers from understanding and confronting this growing problem. In this paper, we present the results of extracting phishing messages from over 200 million SMS messages posted over several years on 11 public SMS gateways on the web. From this dataset we identify 67,991 phishing messages, link them together into 35,128 campaigns based on sharing near-identical content, then identify related campaigns that share infrastructure to identify over 600 distinct SMS phishing operations. This expansive vantage point enables us to determine that SMS phishers use commodity cloud and web infrastructure in addition to self-hosted URL shorteners, their infrastructure is often visible days or weeks on certificate transparency logs earlier than their messages, and they reuse existing phishing kits from other phishing modalities. We are also the first to examine in-place network defenses and identify the public forums where abuse facilitators advertise openly. These methods and findings provide industry and researchers new directions to explore to combat the growing problem of SMS phishing.


> [Link to the paper (pdf)](../files/sms-phishing-paper.pdf)


> [Link to the conference presentation (on YouTube)](https://www.youtube.com/watch?v=HqRstw_y1Qk)



#### BibTex

```Bibtex
@INPROCEEDINGS {sms_phishing__,
author = { Nahapetyan, Aleksandr and Prasad, Sathvik and Childs, Kevin and Oest, Adam and Ladwig, Yeganeh and Kapravelos, Alexandros and Reaves, Bradley },
booktitle = { 2024 IEEE Symposium on Security and Privacy (SP) },
title = { On SMS Phishing Tactics and Infrastructure },
year = {2024},
volume = {},
ISSN = {},
pages = {1-16},
keywords = {Uniform resource locators;Privacy;Regulators;Law enforcement;Phishing;Organizations;Logic gates},
doi = {10.1109/SP54263.2024.00169},
url = {https://doi.ieeecomputersociety.org/10.1109/SP54263.2024.00169},
publisher = {IEEE Computer Society},
address = {Los Alamitos, CA, USA},
month = {May}
}

```