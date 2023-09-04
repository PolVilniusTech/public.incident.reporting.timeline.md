### References for the Research:
* https://cybersec.ee/
* ...


### 2007

##### I ncident

According BNS Estonian web pages were hit by large-scale DDoS (following — Distributed Denial of Service) attacks, which began in the government sector and later spread to the education, media and private sectors. [@err.ee](https://news.err.ee/592250/cert-chief-estonia-s-cyber-crisis-management-capability-improved-in-decade) 

Other sources:
* [Kibernetinis saugumas: ar veiksmų imsimės tik po savo „bronzinio kario“?](https://www.lrt.lt/naujienos/lietuvoje/2/168557/kibernetinis-saugumas-ar-veiksmu-imsimes-tik-po-savo-bronzinio-kario)
* ...
```

```
##### R esults 

According [@Latvian Institute of International Affairs](https://www.liia.lv/en/publications/the-riga-conference-papers-2019-nato-at-70-in-the-baltic-sea-region-815) these attacks kept the whole state in chaos for weeks. Although North Atlantic Treaty Organization (following — NATO) responded to Estonia’s call for assistance, it was restrained by the legal limitations, but also by the lack of necessary capabilities. 
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. Against such cyber-bullies, who uses DDoS attacks, would reaquire to build:
* Better infrastructure which could manage to Respond or Redirect huge number of Requests;
* Secured Internet Connection Lines;
* Trained Incident Response Teams.

More in detail:
* [OWASP](https://owasp.org/www-community/attacks/Denial_of_Service)
* [Blocking DDoS](https://owasp.org/www-community/controls/Blocking_Brute_Force_Attacks)

Other helpful tech:
* [DNSSEC support](https://www.isc.org/blogs/bind-9-10-dnssec-crypto-and-changes-to-existing-behavior/)
* [reCAPTCHA](https://www.google.com/recaptcha/about/)
```

```
### 2011

##### I ncident

According [@err.ee](https://www.err.ee/357975/fbi-usa-taotleb-eestis-vahistatud-kuberkurjategijate-valjaandmist) the Criminals have taken control of millions of Computers around the World with Malware called DNSChanger. 
```

```
##### R esults 

According [@err.ee](https://www.err.ee/357975/fbi-usa-taotleb-eestis-vahistatud-kuberkurjategijate-valjaandmist) the Malware allowed the Victims to be redirected into mallicious Places and made them susceptible to other Malware.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Against such Malware exists tools like this one [malwarebytes.com](https://blog.malwarebytes.com/detections/trojan-dnschanger/);
* For such Incidents there should be available the Raport(s), including how to fix the Problem(s), i.e. [fbi.gov](https://www.fbi.gov/file-repository/dns-changer-malware.pdf/view).
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

According [@TheGuardian.com](https://www.rtlnieuws.nl/tech/artikel/5226954/deepfake-rusland-navalny-europese-politici) Estonian parlamentarian had video chat with other person, who used deepfake technology using distance audio-video communication Solution.
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
* Does there are defined policy(-ies) who should be able to access those backups?  
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
* If Bank Employees does not ask for any passwords, then does it should be different for other e-Services? Your password must be secure and known only by You. Use Your password(s) only in the official place(s) of the e-Service.
* Does anyone are giving mutual trust for such Service? Let say, at least HTML link from the trusted Government Subject and other trusted third party.
* Does the Security of such Service is going thru the audit process? If yes, then who doing this audit? Does the Auditor could be trusted?  
* If there is legal need for several people to access the some content, then each of person should use their own passwords.
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

According [LRT.lt](https://www.lrt.lt/naujienos/pasaulyje/6/1601514/puga-estijoje-sutrikde-skrydzius-eisma-elektros-tiekima) people in some regions lost access to the electricity.
```

```
##### R esults 

Blizzard damaged Peoples Assets, they lost access to the electricity.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
*   like Internet connection could be used from multiple sources, look for electricity from multiple sources.
*   own uninterruptible power supply (UPS), so You would be able to finish the work and (or) save Your work.
*   for specific period of time electricity from gas, oil, renewable could be used as additional source, Datacenters with special information system Services has such way for prolonging it's uninterruptible work.
*   with multiple sources of Connectivity and (or) Electricity would need to maintain it's functionality and safety.
```

```
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

According [-](https://www.err.ee/1608541747/nyt-iisrael-blokeeris-eestis-ja-ukrainas-pegasuse-nuhkvara-kasutamise) some entity, who has not integral borders by 100% (The Gaza Strip), don't allowed to use their Software Applications.
```

```
##### R esults 
State could not use specific Software Application for their needs. High chance that this are related with International Law.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* The Terms and Conditions of the [NSO Group Pegasus licence](https://www.nsogroup.com/terms-conditions/) looks more like Criminal Code of Specific Country or State, so at least You would know the Consequences, if You would wish to attemt and do something Fishy. Unfortunately other Country or State Law not equal to another Country or State Law, or has huge-smaller Similarities.
* Reglaments during the War and for so called Special Operations with Army, Militants, Military, Special Forces which would negatively effect the Country and (or) other Countries, Regulars and Commoners may not work as it should. And later on by Wasting of the Time would lead into searching for ScapeRabbit.
* Problems with Countries with Institutions who are using such Apps usualy lack or without concern of having Specialists who would approve and permit usage of such App. These Specialists could be linked to the Human Rights, Law Enforcement. Who would wish to tie their Arms? Some Immigrants had tied their Arms while in Lithuania. Who asked, if they are dangerious?
* If such Apps would be used by Corrupted States-Countries. It would be needed to Ban the usage of mobile phones, laptops, smart gadgets in specific Sector where information leak would negatively affect Global Security Rating (counting cost of the loss and count of total damage).
* Such Apps could work by following (random ideas): I. reporting the Weakness and (or) Glitch to the Product of Tech Company and until it is not fixed by update or patch. Until then this Weakness would be used against somebody; II. by not having some Weakness and (or) Glitch to the Product of Tech Company would lead into not working App of Such Company as desired; III. some Weakness and (or) Glitch could be created with the intention and it is especially dangerious when there would be no Tech Professionals who would Fix it or in other words - the Product is too dangerious to be keept in the Production.
```

```
### 2023

##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1950560/bilietai-lt-vadovas-klientu-finansiniai-duomenys-nebuvo-nutekinti) the Site of "Bilietai.lt" have/had flaw in source code which allows/allowed to access e.tickets data. [Piletilevi.ee](https://www.piletilevi.ee/) has a chance to have something in common.
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
##### I ncident

According this Article [en.wikipedia.org](https://en.wikipedia.org/wiki/Zone-H) exists Site, which lists archive of defaced websites. Provided Statement that the Service were established in Estonia.
```

```
##### R esults
The Organisation is not showing any Registration Proof for providing e.Service in the Country. 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Exists a number of Cybersecurity Companies & Services, which has jurisdictional backing. Some of their Founders even "Hackers" themselves.
* The Public Wikipedia Page could be filled by anyone. Even so there is no simple Link or Reference to the "hacker" Term. If those "hackers" are shown as in the ISO Database as "Technically sophisticated computer enthusiast who uses his or her knowledge and means to gain unauthorized access to protected resources", then does the Service copperate with law enforcement, which are more in the Protection Side?
* The Service could very simply explain how to make this "hacking" approved. At the Beginning: at least Consent from the Site Owners to conduct the "hacking". In nowadays a lot of those enthusiast People are just fooled by some Third Party, which has their own Goals and more Unlawful than that.
```
