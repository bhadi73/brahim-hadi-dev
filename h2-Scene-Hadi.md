## H2 Assignment (Brahim Hadi / a1504665):

## A) Podcast/Listened: Darknet Diaries, the Nickolas Sharp / Ubiquiti story (EP 178: UBIQUITI) Summary: 
* Nick Sharp was a senior cloud engineer at Ubiquiti paid at $250,000 a year, but he felt unrespected and underpaid. He also felt management ignored his security warnings and advices.
* In December 2020 (COVID time) he used his own wide access, plus a shared admin account and a VPN, to download more than 100 private code repositories. Then he deleted the logs to hide what he has done.
* Pretending to be an outsider hacker, he asked about $2 million in Bitcoin. He was also part of the internal team investigating the attack hiding in the crowd.
* Ubiquiti refused to pay the ransom. Nick then leaked the data publicly. 
* His mistakes caught him: a short internet outage exposed his real home IP address, his router logs showed a second laptop moving large amounts of data, and he had paid for the VPN with his own PayPal account about 6 month ago before his evil act.
* He anonymously told journalist Brian Krebs the truth about Ubiquiti’s insecure systems and showed that Ubiquiti had misled its customers about the incident. Ubiquiti  stock dropped 20%, which is about $4 billion in value.
* He pleaded guilty and was sentenced to six years in prison.
# My question: 
Nick was right about real problems: too much access, shared admin accounts and weak monitoring. Yet no alarm went off while one person copied 100+ repositories in the middle of the night. How many companies could even detect an insider like this? Would least privilege and alerts on unusual downloads have stopped him before he started? 

Reference: https://darknetdiaries.com/episode/178/

## B)Blog read: Citrix NetScaler vulnerabilities exploited in Finland (1 Oct 2026)
* Serious security holes in Citrix NetScaler devices are being used by attackers in Finland.
* Attacks started before the fix came out, so updating alone isn’t enough. Organisations also need to check whether someone already got in.
* NCSC-FI found hundreds of these devices in Finland and warned their owners.
# My question: 
If devices like this keep getting hacked before a fix exists, should companies assume they might already be breached and check these devices regularly?

Reference: https://www.kyberturvallisuuskeskus.fi/en/news/citrix-netscaler-vulnerabilities-exploited-finland

## C)Linking h1 to Darknet Diaries , the Nickolas Sharp / Ubiquiti story (EP 178: UBIQUITI) podcast.
Theory from h1 assignment:  Filiopoulou et al. (2026) found that cloud security failures are “almost never purely technical”. They turn into costs: disruption, recovery, lost revenue and operating overhead. They also note that detection works as a financial control, and that the shared responsibility model moves costs around rather than removing them.

**Podcast**: Darknet Diaries – Nickolas Sharp / Ubiquiti
* An insider copied over 100 private repositories from GitHub and AWS, and no alarm went off. Weak detection lead the company found out about the security issue only after the ransom demand.
* The financial impact largely exceeded the $2M ransom. Ubiquiti’s misleading “third-party cloud provider” statement and the later data eak led to a 20% stock drop (~$4B). That fits the review’s point that failures show up as lost value, not just technical damage.
* Ubiquiti blamed the cloud provider, but the biggest problem was on the customer’s side: access control and logging. That’s exactly the shared responsibility cost gap that was poorly studied.

## D)Download Debian. Download Debian 13-Trixie installation image on the computer
<img width="827" height="372" alt="image" src="https://github.com/user-attachments/assets/992c0ea5-4049-41f3-a761-5b6c5d49ebeb" />
