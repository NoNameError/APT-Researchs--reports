<img width="1280" height="720" alt="Diamond Model copy" src="https://github.com/user-attachments/assets/f144b3ae-2c23-4d22-99ac-b38527ba5c74" />

**Analysis Summary**

For a better understanding of the methodology for studying these Activity Clusters, i used a framework
suitable for addressing the evolution of current TTPs and technologies. This allows us to correctly map their
activities over time, thus genuinely characterizing an APT study.

The Extended Diamond Model, an evolution of the framework created in 2013 (the Diamond Model),
provides guidance regarding activities involving APTs and Threat Actor analyses in the realm of Threat
Intelligence. This framework covers a considerable gap in other correlations because its concepts, called
Meta-Features, encompass a timeline of TTP evolution, tech stacks (technologies used by the group), and
socio-political motives, also covering the psychology behind an attack and its motivation. Thus, it traces an
Activity Thread over time, along with the attacker-victim relationship, enabling the historical visualization
and evolution of an APT.

The activity cluster targeted in this report - Scattered LAPSUS$ Hunters - shows evolutions not only in its
internal infrastructure but also in the execution of its initial access. Its first major attack occurred against
SalesForce, improperly accessing repositories on the company's GitHub, downloading all content, and
simultaneously compromising the company's AWS environments. There, OAuth tokens linked to partner
services in the technology sector and other companies were obtained. This impact also resulted in lateral
movement through Okta,M365, and Amazon S3.

However, in 2024, their initial access was limited to false technical support calls, linked to the SIM
Swapping technique (SIM Card Swap, Technique T1451 - Mobile - MITRE ATT&CK®), used by the LAPS$US
members.

Since the beginning of the group's activities, they targeted SalesForce as the main objective, where they
gained access to employees with potentially elevated credentials, instigating them to "install" a false
integration, which granted the T.A (Threat Actors) access to the company's environment APIs, leading to
the first impact: the Google and Cisco leak. This was the first evolution, across a 1-year difference
between the attacks, fromphishing to the compromise of almost the entire infrastructure.
