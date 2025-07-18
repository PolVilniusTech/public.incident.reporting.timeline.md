#


### 2011

##### I ncident

According Delfi.lv the electronic census database of the Latvian Central Statistical Bureau (following — CSB) allows to view personal data of citizens who are registered in it. [@Delfi.lv](https://www.delfi.lv/news/national/politics/it-drosibas-incidentu-noversanas-vieniba-gatava-konsultet-csp.d?id=37139457) 

```

```
##### R esults 

According [@nra.lv](https://nra.lv/latvija/42527-izdevies-pieklut-tautas-skaitisanas-datu-bazei-csp-uzlabo-sistemu.htm) Internet search engines Indexed data of this database. CSB database allowed to  
```

```
##### L earning from Mistakes 

Currently there are more understanding on such occasions by adopting [General Data Protection Regulation](https://ec.europa.eu/info/law/law-topic/data-protection/data-protection-eu_en) (following — GDPR).

From such incidents there are possible to learn a lot. Against them it would reaquire to build:
* Awareness training for the Software Authors and Staff, InfoSec related persons;
* Review the requirements in the Software Specifications (following — Specs) and their life-cycle;
* According the Specs it needs to have functionality of the Software tests, including;
* Some level Security testing in/after development phase;
* Does merging (compatible) Software, which contain (compatible) information into higher (National|EU) Data Center are possible? Does it would increase|relocate costly IT personel into bigger Teams and potentialy would allow to build Computer Security Incident Response Teams or Computer Emergency Response Teams (depends by legal definitions).      

Other helpful tech:
* Review the Identification & Authentication & Authorisation procedures.
* underestimated the knowledge about ROBOTS.txt for sharing data with search engines and Ethical Software.
* [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)
* [OWASP Security Knowledge](https://owasp.org/www-project-security-knowledge-framework/)
```

```
### 2016

##### I ncident

According [@Delfi.lt](https://www.lrt.lt/naujienos/verslas/4/151326/del-galimos-duomenu-vagystes-jysk-praso-pirkeju-blokuoti-mokejimo-korteles) „Jysk“ company informed their Clients about Security related Incident and asks them to block their Credit Cards.
```

```
##### R esults 

Up to 500 Clients in Baltic States would be able to lose their private information.
Clients, who used „BankLink“ functionality should not be victims of possible leak of private data.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* When we dealing with merchandise or other payments which would be related with payment card processing we are dealing with PCI DSS or Payment Card Industry Data Security Standard version i.e. 3.2.1. or newer. 
* Do not store sensitive authentication data contained in the payment card’s storage chip or full magnetic stripe, including the printed 3-4 digit card validation code on the front or back of the payment card after authorization.
* [PCI Security](https://www.pcisecuritystandards.org/pci_security/standards_overview)
* Regularly Install Security Patches and Use Security Scan Tool from Official Site of the e-Commerce.

For Customers:
* Consider to replace Credit Card with new one, if lost information would do huge consequences.
* Consider possibility for restricting use of Credit Card after spending fixed amount of Money per Month.

Other ideas related to Physical Devices:
* Check Credit Card Scanner Device's for Security Issues, test it out and if necessary — fix it. 
```

```
### 2021

##### I ncident

According [@TheGuardian.com](https://www.rtlnieuws.nl/tech/artikel/5226954/deepfake-rusland-navalny-europese-politici) Latvian parlamentarian had video chat with other person, who used deepfake technology using distance audio-video communication Solution.
```

```
##### R esults 

Original person, „participant of video chat“, using Social Network Service approved that it were not him.   
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Authentication of the person is boundless and makes headaches.
* In recommendation to use more than one technique, which helps to answer to the question(s): 
    * What I know? (password,one time token...)
    * What I am? (looks, speech...)
    * What I have? (card, certificate, phone...)
    * Where I am? (in building, outside building, other specific location)
    * What I do? (in total results in non-existing damage, in total results in catastrophic damage)
```

```
##### I ncident

According [@Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1349079/kada-tiksliai-buvo-pavogti-citybee-klientu-duomenys-atsakymas-gali-lemti-20-mln-euru-bauda) more than 100 thousand Clients of the Automobile sharing Service „CityBee“ got notified about Anonymous intruders who disclosed their private information. 
```

```
##### R esults 

From database were leaked Client data like:
* names
* surnames
* personal identification codes
* phone numbers
* e-mails
* address of current residence
* drivers license numbers
* hashed passwords
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Keep less quantity of the Data as much as possible (You can't lose the Data, which You don't Own)
* Does while registering for new Customer there would be possible to build WorkFlow in Stages 1-N? i.e. during Stage 1 You collect required data about the Driver, on other Stage for finishing making Service Available You are removing some personal data of the Client and leave only essential data for the Service like "date when license of the Driver expires" or so?
* Testing for Security Flaws regarding access to the Database.
* Management of the Database backups; testing functionality of those backups.
* Does there are defined policy(-ies) who has ability to access those backups?  
* [Password Storage (OWASP)](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html)
* [Authentication (OWASP)](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html) 
```

```
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1403651/pasaulines-slaptazodziu-dienos-proga-pasitikrinkite-kaip-greitai-nulauztu-jusu-slaptazodi) some experts suggesting to input Your password into some website and check for it's security.
```

```
##### R esults 

People may be interessted to input their passwords into some website.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* If Bank Employees does not ask for any passwords, then does it has to be different for other e-Service? Your password must be secure and known only by You. Use Your password(s) only in the official place(s) of the e-Service.
* Does anyone are giving mutual trust for such Service? Let say, at least HTML link from the trusted Government Subject and other trusted third party.
* Does the Security of such Service is going thru the audit process? If yes, then who doing this audit? Does the Auditor could be trusted?  
* If there is legal need for several people to access the some content, then each person needs to use their own passwords.
* If You think that Your password are known, then You need to change it, but if there are Weaknesses in the Authentication mechanismus, then changing the password at best would help for the time depending how secure are used hash functions.
* Does hash rotation, when Security depend by not one, but several different strong hash functions, would improve the Security? If database would be leaked, then it would cost a lot more of computation power to reverse engineer different hash functions. 
* Does Services implement additional password security measures like pepper and salts? Pepper rotation depending by some status would help to improve the password security a lot.   
```

```
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/1440563/luminor-ispeja-klientus-padaznejo-finansiniu-sukciu-atakos-telefonu) trusted Bank Service is trying their best to report Security Incidents to the Public.
```

```
##### R esults 

Customers of the e-Service are more aware of possible Risks.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
*   Does Customer uses Social Networks or other Public means, which could let get more information about him? This information could be used against him during Social Engineering attack.
*   Does e-Services, which main aim aligns, does not cooperate with each other for the Main Task of creating Universal Best Practice Rulebook for their Customers? Threat for one e-Service could be the same and for other. 
```

```
### 2022

##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1613504/tyrimas-rodo-kad-du-trecdaliai-jaunimo-renkasi-nelegalu-turini) from four hundred participants a lot of them are using of De-Googled Services and Unlicensed Electronic Services.  
```

```
##### R esults 
Depending by Trust of those who Provide the Services there are still the Chance that during some period of time we will feel attack(s) of real huge Bot-net Networks.

```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* It's hard to describe if one day Unlicensed Services would start to go into Defencive stance of Humanity.
* Unlicensed Services usually does not guarantee the Quality of the Service, the Rights of the Client.
* If people has Hands on Unlicensed Services with Quality, then Country lack of Tools and Expertise to help the Service(s) for meeting Regulations of Segment in which it belongs, i.e. micro-service, small-service..
* If people has Hands on Unlicensed Services with Quality, then Country lack of Tools and Expertise to help the Service to do it in Legal way.
* In Unlicensed Service there could be pre-installed various Un-needed functionality, which could be threat to the Health of the Service Owner.
* Lack of Education Institutions for teaching about Open Source Services, which does not fit to be called as Unlicensed.
* Even if Open Source Service(s) are provided, there are a lot of disadvantages like Liability and Warranty, which mostly with the Community Support could be improved and (or) there still lack of information about it.
* Creators who live only from Donations could be exploited, someone are proposing ways for non-growth economical approach for at least until Crisis would be in the Past.
```

```
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/1625756/naujienu-portalas-tv3-lt-skelbia-patyres-kibernetine-ataka) e-Service Portal were attacked with constant useless requests with aim to shut down the e-Service.  
```

```
##### R esults 
The Attack were Graded as Puny. 

```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* If Country-State does not Prevent such Events in International Level, then it means there were Attack Conducted to the Foreign Country from Anonymous backed by Entity-State. These People who are doing, participating, purchasing, requesting, allowing that has to be Punished by International rule-based Law.
* If attack is Puny then there nothing more to add.
```

```
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1686353/latvijoje-sutriko-virtines-valstybiniu-istaigu-tinklalapiu-darbas) some institutions of the Public Service had issues with their e-Services.  
```

```
##### R esults 
The Technical Issues of the Assets. 
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Having Access to new Assets as replacement helps solve Anomalies of the Current Assets with Issues.
* Usualy Updates of the e-Systems are done after Hours, but does People would Pay more for the Night Shift?
* Public Service, which e-Services works in regular-common Way. Only the Idea for owning more Wider Data Center with better Quality of Work. 
```

```
##### I ncident

According [BNS](https://www.lrt.lt/naujienos/pasaulyje/6/1695112/baltarusija-bevizi-rezima-lietuvos-ir-latvijos-pilieciams-pratese-iki-2022-uju-pabaigos) and [-](https://www.lrt.lt/naujienos/pasaulyje/6/1725945/baltarusija-i-psichiatrine-uzdare-latvijos-pilieti-kuris-sms-zinuteje-kritikavo-lukasenka) Phone Networks are not Secure in the Foreign Country of Belarus.
```

```
##### R esults 
This looks like Phishing Attack.
People has the chance to be Prisoner and lose the Face in his own Homeland which is not the Belarus itself.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* If SMS thing would be forged, what the chance to tell that You have not sended such Message?
* If Your Phone is Vulnerable, what the chance that their own Friends not sended such Message?
* To what kind of Country People are Traveling, if there Privacy does not exists and no Freedom of Speech with known Etics code for speaking. 
```

```
### 2023

##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1950560/bilietai-lt-vadovas-klientu-finansiniai-duomenys-nebuvo-nutekinti) the Site of "Bilietai.lt" have/had flaw in source code which allows/allowed to access e.tickets data. [Bilesuserviss.lv](https://www.bilesuserviss.lv) has a chance to have something in common.
```

```
##### R esults
E.Service Clients data are/was leaked, which includes e.ticket information, Client first name, Client last (family) name, Client e.mail address, Client phone No. 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* If content linking mechanism could have flaw, then by finding "previous e.tickets" does not provide warranties that "current e.tickets" are not exposed to a flaw. 
* Awareness training [privacy and data protection of an entity](https://www.prisijungusi.lt/medziaga/norm/3) has a proper guidance how to deal with privacy and not only that.
* The Question for e.Service: Does the Site operate in Lithuania only? if not, then more Countries could be affected.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1986254/google-zengia-i-ateiti-be-slaptazodziu-prisijungimui-prie-savo-paskyros-jau-leidzia-naudoti-slaptarakcius) some company want to collect fingerprint and facial recognition data. The Article states that 83 proc. passwords could be „breaked“ in less than second.
```

```
##### R esults
Danger of Misinformation. 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* If You would take common MS „Windows“ Computer System, then after few wrong logins You gonna get one hour pause period and can't login. You simply can't brute force such authentication mechanism in couple of seconds.
* Great chance that in the Article taking in consideration the process named as breaking the hash.
* Let us consider this Question: Does data leaks in this case would lead in more damage to common people by creating impersonating media content?
```

```

### 2024

##### I ncident

According this Article [LETA](https://nra.lv/latvija/466554-atkartojas-intensivu-kiberuzbukumu-vilnis-pret-valsts-iestazu-majaslapam.htm) internet websites of a public sector institutions, a transport sector, several private sector organisations were not Available. They were DDoS'ed from around of the internet.
```

```
##### R esults
Unavailable Online Resources
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Depending by needs there is plausible to check what bandwidth are Available. According Network spec. try making decisions together with a telecommunication specialists.
* Check server-side capabilities and make available update.
```

```
### 2025

##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/pasaulyje/6/2470254/svedija-sulaike-laiva-itariama-latviu-optinio-kabelio-baltijos-juroje-sabotazu) a [LVRTC](https://www.lvrtc.lv) e.Services was interrupted.
```

```
##### R esults
Loss of Availability of LVRTC e.Services.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* The Article attaches previous similar News, so in this scope exists a Trend, that links in the end of the Article repeats & introduce what already were said from other Incident(s). It's not suggested to provide News in such Fashion. Some specialist could find comparision to Adware.
```

```
##### I ncident

According these Articles [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2605718/sutriko-tele2-tinklo-veikla-gyventojai-negali-prisiskambinti-neveikia-svetaine) and [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2605816/tele2-latvijoje-trikdzius-baltijos-salyse-leme-darbai-estijos-sviesolaidiniame-tinkle) Tele2 telecommunication services are unavailable & problem - maintenance in an outside of telecommunication infrastructure of the Origin Country.
```

```
##### R esults
Loss of Availability
```

```
