<img width="1280" height="720" alt="Profile copy" src="https://github.com/user-attachments/assets/73689147-8e82-430c-974d-8d998fde4bb0" />

**Technical Analysis**

When we enter the temporal axis in the analysis based on the Extended Diamond Model framework,
specifically by UNC6040 (AKA ShinyHunters / Scattered Spider), we notice a difference in how the initial
access occurred within the period from April 2024 to May 2025. In 2024, the operators began with a call
posing as IT support, also focusing on employees who do not have extensive technological knowledge.

However, in 2025, during the attacks against SalesForce, there was a notable shift. Even though it still
involved phishing activities, the T.A.s (Threat Actors) now use AI voice agents via VoIP calling services,
including Twilio, Google Voice, and 3CX, to complete the attacks. They used voice AIs such as Vapi and
Bland.

<img width="739" height="315" alt="image" src="https://github.com/user-attachments/assets/bddff4c6-8e54-440e-96b8-dca010305b49" />

The attackers can configure voice styles, including gender and regional accents, making the output sound
similar to a human rather than robotic. Unlike static robotic voice calls, the AI model generates voices and
dynamically adjusts tone and responses to maintain credibility and manipulate the target. This
combination of LLM (Large Language Model)-driven dialogue management and near-realistic synthesized
voice allows threat actors linked to the ShinyHunters group to execute successful large-scale vishing
operations. Faced with this situation, in the month of August, they began "soliciting" employees with
financial rewards for providing access
.
On August 31, 2025, the iT.EAM Threat Intelligence team detected the exact moment when the Telegram
channel "scattered LAPSUS$ hunters 4.0," operated by the ShinyHunters group, published a recruitment
message. The group was recruiting internal employees in corporate organizations who could provide
access to solutions such as Okta, Microsoft SSO, Citrix VPN, or Git version control solutions like Github
and Gitlab. This search for cloud applications aligns with the phishing campaigns observed and attributed
to the ShinyHunters team.

ShinyCorp offered financial rewards to employees of finance, insurance, aviation, telecommunications,
automotive, retail, hospitality, energy, and investment companies in exchange for providing network
access.

<img width="684" height="315" alt="image" src="https://github.com/user-attachments/assets/a3989bd3-f66d-4856-86ce-f6327c6af1b7" />

Another sign in the evolution of the APT, as part of the ShinyHunters' social engineering strategy, is that the
threat actors cloned the authentication flow and user interface of a legitimate Okta subdomain (trial-
6857053.okta[.]com). They replicated the login formwith the targeted organization's visual identity to create
a convincing phishing page that mimicked official Okta environments.

By pivoting from the domain name (trial-6857053.okta[.]com) and its phishing theme, 12 infrastructure
artifacts linked to the ShinyHunters' phishing campaigns were identified. When comparing the pivoting, the
fake Okta login theme closely resembles the phishing templates described in the ReliaQuest publication
fromAugust 12, suggesting an overlap in both tactics and targeting. Analysis of the phishing page indicates
that the Okta login form was first cloned on August 23, 2022 (Brazil time zone), suggesting a long-term,
systemic study.

<img width="743" height="127" alt="image" src="https://github.com/user-attachments/assets/3942bcba-c6e2-48bf-a841-def93e4fbfe6" />

Fromthis moment, we have the first behavioral analysis of the group, which constantly "trolled" FBI agents
publicly in their various groups.
The analysis of the Okta phishing infrastructure identified by pivoting revealed identical HTTP response
headers across all hosts, including references to fbi.gov.

The Server header consistently shows Apache/2.4.58 (Win64) with OpenSSL/3.1.3 and minor variations in
PHP versions (8.0.30 vs. 8.2.12), indicating a centralized configuration and management under the same
operation.

The main messages with direct provocations to the FBI contain "Fuck da/the
FEDS (Federals)", a phrase even used in the data leak announcement as a form of taunting. The members
were aware of the FBI's hunt and the infiltration of this and other agencies into their various groups.
<img width="380" height="339" alt="image" src="https://github.com/user-attachments/assets/f7f3a105-9205-48fc-b883-b650c2d283a8" />
<img width="539" height="792" alt="image" src="https://github.com/user-attachments/assets/88717335-0fde-4e4f-bd99-0d951fdebfd9" />


Coupled with this, the group's communication is a key point, as it became their behavioral identity.
Consequently, beyond the fame and unique characteristic, the provocations are a means of "pressuring"
companies at the moment of decision-making regarding payment to the group. Overall, besides
expressions of defiance and dark humor, the announcements also followthe same line of communication,
such as, for example, in the compromise of the Stellantis database:
<img width="541" height="663" alt="image" src="https://github.com/user-attachments/assets/cb5dc45e-8661-4b9a-9745-6ad4a0264e0d" />

As a direct consequence of the attack on SalesForce, other companies that are references in their
respective segments were compromised.
<img width="790" height="426" alt="image" src="https://github.com/user-attachments/assets/30ae3032-2505-4663-adeb-d49ef09663c5" />
<img width="723" height="206" alt="image" src="https://github.com/user-attachments/assets/c369d00b-2c6a-4cfe-9cad-741c7abb5906" />





