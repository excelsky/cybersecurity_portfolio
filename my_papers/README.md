Abstract

EU data localization regulations limit data transfers to non-EU countries with the GDPR. However, BGP, DNS and other Internet protocols were not designed to enforce jurisdictional constraints, so implementing data localization is challenging. Despite initial research on the topic, little is known about if or how companies currently operate their server infrastructure to comply with the regulations. We close this knowledge gap by empirically measuring the extent to which servers and routers that process EU requests are located outside of the EU (and a handful of 'adequate' non-EU countries). The key challenge is that both browser measurements (to infer relevant endpoints) and data-plane measurements (to infer relevant IP addresses) are needed, but no large-scale public infrastructure allows both. We build a novel methodology that combines BrightData (browser) and RIPE Atlas (data-plane) probes, with joint measurements from over 1,000 networks in 20 EU countries. We find that, on average, 2.2% of servers serving users in each EU country are located in non-adequate destination countries (1.4% of known trackers). Our findings suggest that data localization policies are largely being followed by content providers, though there are exceptions.

Keywords: Data Localization, GDPR, Internet Measurement

Published at [PETS 2025](https://doi.org/10.56553/popets-2025-0107)
