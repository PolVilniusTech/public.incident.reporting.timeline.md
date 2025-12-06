### References for the Research:
* site-check.cert.lt
* https://www.nksc.lt/tikrinti.html
* https://www.cert.orange.pl/aktualnosci/raport-cert-orange-polska-za-2020-rok 6-13 p.

### Table of Contents

* [2016](#2016)
* [2017](#2017)
* [2018](#2018)
* [2019](#2019)
* [2020](#2020)
* [2021](#2021)
* [2022](#2022)
* [2023](#2023)
* [2024](#2024)
* [2025](#2025)

### 2016

##### I ncident

According [@lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/151146/vrk-rinkejo-puslapis-bus-isjungtas-kol-bus-pasalintos-gresmes) temporarily were shut down "Voter Page" Portal (following — System), because security gap has been found. Reported the  (following — VRK, engl. lang. CEC).
```

```
##### R esults 

According [@lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/151125/kaltinimai-vrk-ne-tik-del-informacines-sistemos) the System didn't worked smoothly and safely, there were a threat to voter personal data, it was easy to access data of the System.
According Š. Černiauskas the System allowed to generate list of voters personal data by changing integers in end of the address.
According the VRK access to the System were limited. (Only identified persons)
According D. Lazauskas the System allows to create personal shared Environment for Voters.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Conduct functionality tests of the System;
* Review User Roles and their access to the Data. Test it out;
* Define what kind of information has to be available for the User of the System;
* Review Identification & Authentication & Authorization Mechanismus;
* Question of Documentation and Specification understanding and clarity from Client/Requestor perspective;
* Question of Documentation and Specification understanding and clarity from Contractor/Company perspective.

```

```
##### I ncident

According [@Delfi.lt](https://www.lrt.lt/naujienos/verslas/4/151326/del-galimos-duomenu-vagystes-jysk-praso-pirkeju-blokuoti-mokejimo-korteles) "Jysk" company informed their Clients about Security related Incident and asks them to block their Credit Cards.
```

```
##### R esults 

Up to 500 Clients in Baltic States would be able to lose their private information.
Clients, who used "BankLink" functionality should not be victims of possible leak of private data.
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
*  Credit Card Scanner Device's for Security Issues, test it out and if necessary — fix it. 
```

```
### 2017

##### I ncident

According [@lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/247992/strigo-vrk-puslapis-didelis-srautas-lauze-sistema) connectivity to the Web Site(s) for VRK to do their job is jamming because of huge data flow.
```

```
##### R esults 

According @lrt.lt the view of newest results, interactive maps is jamming.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Test out, if Hardware has enough resources to function properly.
* Test out the characteristics of the Web Server.
* Look for the ways how to upgrade the Hardware and the Web Server.
*  if Servers Ethernet interface needs upgrade into latest fiber-optic Ethernet. 
* Distributing Resources and aligning to the Server capability at serving the Customers.
* Look for cache capability for speeding up processes.
```

```
##### I ncident

According [@Delfi.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/188552/antradieni-ryte-buvo-sutrikusi-dalis-telia-paslaugu) there was a disruption to the operation of "Telia" platform for sending SMS. Partly because of this, an web site of "Ežys" are not operational either.
```

```
##### R esults 

Failure on one Service lied into disruption of second Service.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Look for ways how to implement functionality with processes to fail safely.
* Depending by Tasks of the specific Service use separated operational Environments.
* Test out processes that one failure would not do any impact to other process.
```

```
##### I ncident

According [@Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/179665/liuties-padariniai-portalas-meteo-lt-neatlaiko-vartotoju-srauto-ir-luzineja) Lithuanian Hydromeorological Service Web Site meteo.lt no longer withstand Data flows. According to the senior specialist, the Web Site can only withstand up to 1,000 Connections at a Time. After completion of the improvements, 10 thousand Users will be able to read the Forecasts at the same Time.
```

```
##### R esults 

Website no longer withstand Data flows because the Server does not have such capability.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Increase Servers capability to manage more Clients at one time.
* Usage of Round-robin DNS and similar techniques.
* Technique of DNS Failover & non-stop Monitoring for distributing Users from 2 to N Web Servers.
* [Configuring Web Server Functionality](https://docs.oracle.com/cd/E14571_01/web.1111/e13701/web_server.htm#CNFGD192)
* [Avoiding and Managing Overload](https://docs.oracle.com/cd/E14571_01/web.1111/e13701/overload.htm#CNFGD146)
```

```
##### I ncident

According [@Delfi.lt](https://www.lrt.lt/naujienos/lietuvoje/2/172790/dar-vienas-ispuolis-pries-vilniaus-inovatyvios-medicinos-centra) in some Computers-Servers of the Santara Valley were breached and some of their documents were encrypted for the Ransom.
```

```
##### R esults 

Breach into the Server of the internal Network.
The Subject does National-wide long-term Academic Research, Collaborative experiments, the Aid to the various Institutions, which are related to Medical Protection.  
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Increase System capability to detect Internal Breaches.
* Learn how to handle different backups with various timestamps.
* Does new technologies and research on them has correct importance in the Country level and are the Engine of Innovations? 
```

```
#### I ncident

@2019 Data leak of the Website "Grožio chirurgija"
```

```
### 2018

#### I ncident

@2021 Flaw of the System of e.sveikata 
```

```
### 2019

##### I ncident
According [@Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/244671/su-kinijos-valdzia-siejamus-isilauzelius-aptiko-vilniaus-it-imones-specialistai) this Article non-Local Origin Company Computer Network got breached by already known Hacker Group.
```

```
##### R esults 
No Impact to the Company and Client Data.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* The Idea that "already known" Entities completed Breach is puzzling. No additional Data given. In some sense when Internet connection goes through other Country there could be Middle-Man in between who has such Motives, i.e. he could fool that something were done from other Entity.
* Blocking Internet connection with Firewall and allowing for anyone to make breaches all around the State-Country Borders just show that this State-Country just don't want International Cooperation and does not abide to the Law(s), i.e. Local ones and of course International Laws and Regulations. This could show probable very bad place for Investment, because in that Area there will be no Aid in solving Foreign Incidents and You just have to move away. Some bad Agents could create Artificial Entities around the Borders to do this instead of their own, and this show even less wish to Invest in such Area.
```

```
##### I ncident
According this Article [@Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/1057412/lrtk-prasys-teismo-blokuoti-nelegalia-muzikos-irasu-svetaine) exists number of Web Sites who contain illegal content of Lithuanian and Foreign Music Authors. 
```

```
##### R esults 
From Site(s) non free and open source content are downloaded without consent of original Author(s).
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Lithuanian platform sample where are possible to get legal content [pakartot.lt](https://www.pakartot.lt/).
* Foreign platform sample where are possible to get legal content [spotify.com](https://open.spotify.com/).
* Amoung Site(s) who contain illegal content are plausible to get phisihng attack(s), because those Sites has more visibility from malicious adversaries.
```

```
##### I ncident

According [@Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1067988/lietuvos-interneto-vartotoju-duomenys-be-ju-zinios-per-yandex-ir-toliau-keliauja-i-rusija) in local market it's possible to purchase routers with integrated DNS service, which operates outside of the Country.
According E.Kerza during communication with the DNS server DNS data requests and responses are sended outside of the Country, this data potentially are stored there. „<...> routers does not meet security requirements. Users main router passwords are stored in unencrypted form, updates and data from the control servers flows unencrypted“. Given advices:
* to use DNS servers, which are offered of the Internet Service Providers;
* change routers non-secure factory settings, passwords into more secure ones.
```

```
##### R esults 

According E.Kerza there are companies who sell poor quality Goods and Services, which does not ensure the minimal security requirements of the EU.
Let's form the Question: Does there are enough Goods and Services for blocking the Malicious Content (i.e. adult, gambling sites and darknet limited access sites)?:
* https://www.iwf.org.uk/what-we-do
* https://www.betterinternetforkids.eu/
* https://www.draugiskasinternetas.lt/kas-mes/apie-programa/
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Internet Service Providers typically provides recursive and caching name servers for their customers.
* I.e. to prevent for the DNS Iterator to get more information DNSSEC and previous recursive Chain of Trust could be implemented.
* ISP providers are registering their Incident Resonse Teams and are shown in ENISA portal [CSIRTs list](https://www.enisa.europa.eu/topics/csirts-in-europe/csirt-inventory/certs-by-country-interactive-map#country=Lithuania)

For Buyers:
* If DNS server is returning outdated or incorrect results, then it's better to change your DNS servers and flush the DNS cache.
* [DNS Lookup Service](https://dnser.org/)
* [About DNS and it's configuration on Windows, Mac, Ubuntu](https://dnser.org/dns-articles/how-dns-works-how-to-find-dns-of-your-pc.html)
```

```
##### I ncident

According [@Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1078670/gps-alternatyva-vis-dar-neveikia-del-to-galileo-ekspertai-isteige-anomaliju-analizes-komiteta) European Navigation System "Galileo" is not Available. This system has at least 22 Satellites and provide service for computer users, mobile phone users, transportation sector. 
```

```
##### R esults 
Single Navigation System is unavailable.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Devices has chance to swap their navigation service with other company(ies) Satellites. This is called a Global Navigation Satellite System (GNSS). This include at least five to six independednt Systems.
* GNSS testing software could be found here [github.com](https://github.com/barbeau/gpstest). This software is using Apache v. 2.0 license.
```

```
##### I ncident

According [@Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/1079449/vmi-gresia-iki-60-tukst-euru-bauda-del-nutekejusiu-duomenu) in the Portal of the State Tax Inspectorate [VMI.lt]() "Mano VMI" were possible to view Confidential Information of legal persons and subjects for limited number of people. 
```

```
##### R esults 

Chance of data loss.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
*  functionality and test out the Configuration of the System.
*  legal documents and ensure that System are tested for Governance Compliance.
```

```
##### I ncident

According [@BNS](https://www.lrt.lt/naujienos/lietuvoje/2/232540/grozio-klinikos-klientu-duomenu-vagystes-reketininkai-is-mediku-norejo-0-5-mln-euru) One Person leaked and Two disclosed Personal data from the Website of Grožio chirurgija.
More references:
* [@15min.lt](https://www.lrt.lt/naujienos/lietuvoje/2/170482/is-grozio-klinikos-pavogti-garsiu-klientu-duomenys-ir-intymios-nuotraukos)
* [@Delfi.lt](https://www.lrt.lt/naujienos/lietuvoje/2/170816/duomenu-is-grozio-chirurgijos-vagyste-santazistai-paskelbe-savo-reikalavimus)
* [@15min.lt](https://www.lrt.lt/naujienos/lietuvoje/2/174796/paviesinti-visi-grozio-klinikos-duomenys-uz-siuntimasi-gresia-baudziamoji-atsakomybe)
* [@BNS](https://www.lrt.lt/naujienos/lietuvoje/2/1112648/grozio-chirurgijos-duomenu-vagystes-byla-i-teisma-negrizta-sprendziant-del-kvalifikavimo)
```

```
##### R esults 

Personal data of Local and Foreign People were leaked. 
Ransom money by specific Clients of the Grožio chirurgija with aim to not disclose it were paid.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* If exists Personal data, before disclosing it, You have to get Approval of the Person to which it belongs.
* Documents, with misinformation for sharing data to the third party does not always are correct, because the Person, who Approves could misunderstood on some points, so more "boxes" for vital points have to be ed.
* Limit access to the Authentication mechanism for the external Entities and Users. 
* What would be an Impact to the Company, when through shared & uncontrolled User Account personal data would be lost?
* Programming Applications, Software, Devices with functionality to scan and breach the Websites, Portals, or even Systems, according the [@BNS](https://www.lrt.lt/naujienos/lietuvoje/2/232540/grozio-klinikos-klientu-duomenu-vagystes-reketininkai-is-mediku-norejo-0-5-mln-euru), are illegal (p.s. if it is used in Computer Network(s), Websites, Portals, or even Systems without proper or legal Approval). It's in the list of dual-purpose objects, which could be used for testing Security with Aim to fix, or vica versa.   
```

```
### 2020

##### I ncident

According [@Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1176660/ekspertas-yandex-taxi-programele-gauna-prieiga-prie-visu-duomenu-ir-siuncia-juos-i-rusija) Application of the Business subject in democratic country are collecting and sharing Private data of the Citizens with the Servers from non-democratic order.

More:
@2019 Flaw of the System of Yandex
```

```
##### R esults 
Privacy of People can't be established.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
*  In democratic country even Policeman or Parlamentarian don't have any chance to Win in Courthouse, if they would tried without Citizens consent to dig into the private data of the Citizen.
*  In non-democratic country any subject could be stated as Terrorist and by their request has to lose Privacy in all around the World.
*  don't use Service, if it would require to provide Private Data (Name, Surname, etc.)
*  pay in non electronic Cash and pay without change
*  in Country, where exists democratic order, subjects from non-democratic country has to abide the order. Sharing Private data in this case would lead into the consequences to the non-democratic Government, who are requesting the data from the subject.
*  in Country, where exists non-democratic order, subjects from democratic country has to abide the order where they are doing the Business. 
```

```
##### I ncident

According [@Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/1144796/isilauzta-i-panevezio-teritorines-ligoniu-kasos-internetine-svetaine) Application creators thought to use Services, which are serving it's functionality from abroad of country, which supports different order of the country.
```

```
##### R esults 
Privacy of People, who are using such functionality can't be established.
Possible Safety and Information Security Issues.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
*  ease availability of the functionality, which You are Searching, in the Start could be valued similarly as Phishing attack.
*  functionality providers has to persuade their Users that they are working in specific country and order, which would help to see the possible consequences of using such Service.
*  conducting Risk analysis to the Data of the Application would easily show the possible consequences.
*  control of functionality of the system should be distributed to specific role aligned privileges.
*  organisational and technical control, documentation/legislation are required for sending or leaving notice(s) of unknown and uncontrollable access to the system and it's Data. Integrity of such information require to be preserved.
```

```
### 2021

##### I ncident

According [@Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1349079/kada-tiksliai-buvo-pavogti-citybee-klientu-duomenys-atsakymas-gali-lemti-20-mln-euru-bauda) more than 100 thousand Clients of the Automobile sharing Service „CityBee“ got notified about Anonymous intruders who disclosed their private information. 
More references:
* [@Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/1553145/del-nutekejusiu-duomenu-110-tukst-euru-bauda-citybee-valdanciai-prime-leasing)
* [@BNS](https://www.lrt.lt/naujienos/verslas/4/2299818/teismas-citybee-tures-atlyginti-100-tukst-zala-del-nutekintu-klientu-duomenu)
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
* Does there are defined policy(-ies) who could be able to access those backups?  
* [Password Storage (OWASP)](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html)
* [Authentication (OWASP)](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html) 
```

```
##### I ncident

According [@Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1349079/kada-tiksliai-buvo-pavogti-citybee-klientu-duomenys-atsakymas-gali-lemti-20-mln-euru-bauda) more than 275 thousand of Personal Accounts were leaked from Web Site of Orakulas.lt. 
```

```
##### R esults 

Personal Account Data leak. According [ELTA](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1395373/duomenu-apsaugos-inspekcija-tyrimas-del-citybee-klientu-duomenu-nutekinimo-gali-buti-baigtas-ne-anksciau-nei-uz-poros-menesiu) for the Incident to be fully Researched and Documented is needed at least two months.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Fix issues of the Security Flaw and report to the Clients to change Login Credentials.   
* [Password Storage (OWASP)](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html)
* [Authentication (OWASP)](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html) 
```

```
##### I ncident

According [@Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1349079/kada-tiksliai-buvo-pavogti-citybee-klientu-duomenys-atsakymas-gali-lemti-20-mln-euru-bauda) more than 400 thousand of Personal Data were leaked from Web Site of DarniPora.lt. 
```

```
##### R esults 

Leaked email addresses and Login Credentials.
According @Lrt.lt there is way to purchase desired Client Data.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Fix issues of the Security Flaw and report to the Clients to change Login Credentials.
* Use General Data Protection Regulation and legal documents in Your favour to remove the Data and protect Your Clients.   
* [Password Storage (OWASP)](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html)
* [Authentication (OWASP)](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html) 
```

```
##### I ncident

According [@Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1349079/kada-tiksliai-buvo-pavogti-citybee-klientu-duomenys-atsakymas-gali-lemti-20-mln-euru-bauda) more than 65 thousand of Personal Data were leaked from Web Site of the Filmai.in. 
```

```
##### R esults 

Leaked email addresses and Login Credentials.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Fix issues of the Security Flaw and report to the Clients to change Login Credentials.
* Filling the Gap of local Video Streaming Service Industry by paying taxes would allow to use more legal ways to protect Your Clients. 
* [Password Storage (OWASP)](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html)
* [Authentication (OWASP)](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html) 
```

```
##### I ncident

According [@TheGuardian.com](https://www.rtlnieuws.nl/tech/artikel/5226954/deepfake-rusland-navalny-europese-politici) Lithuanian parlamentarian had video chat with other person, who used deepfake technology using distance audio-video communication Solution.
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

According [@diena.lt](https://www.diena.lt/naujienos/verslas/ratai/regitra-pranesa-apie-sukciavimo-atvejus-automobiliai-parduodami-neva-su-kodu-1023220) people are spreading desinformation about having what is yet un-available.
```

```
##### R esults 

[Regitra.lt](https://regitra.lt/lt/naujienos/ka-butina-zinoti-apie-nuo-2021-m-geguzes-1-d-ivedama-nauja-transporto-priemoniu-savininku-sistema) lists detailed information about how to get the required proccess done.   
[VMI.lt](https://www.vmi.lt/evmi/-/vmi-primena-nuo-gegu-c5-be-c4-97s-1-d.-parduoti-galima-tik-sdk-turin-c4-8dias-transporto-priemones) posts detailed information about why it's needed to enhance the Current Situation.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Don't trust for User Input;
* Test functionality of the Website for User Inputs of required information option;
* Help Your Customers to build tradition for Using ServiceBook from beginning to the end of life of Your Goods;
* Vehicle(s) probably has it's own Registration, Service and Support electronic Page(s) over the Internet/Intranet, or at least for unique identifier VIN code. 
```

```
##### I ncident

According [@Lrytas.lt](https://www.lrytas.lt/it/ismanyk/2021/04/28/news/skelbiama-apie-parduodama-pigu-lt-vartotoju-duomenu-baze-parduotuve-neigia-kad-duomenys-yra-ju-19177673/) Anonymous person put the offer to sell some data of the Pigu.lt Clients in one Darknet Website. Representative of Pigu.lt rejected the possibility of the data leak.
```

```
##### R esults 

[@Lrytas.lt](https://www.lrytas.lt/it/ismanyk/2021/04/28/news/skelbiama-apie-parduodama-pigu-lt-vartotoju-duomenu-baze-parduotuve-neigia-kad-duomenys-yra-ju-19177673/) lists probable leaked data of Resident Identification Number, Email Address, Password Hash, Resident Address, Phone Number, Balance Information.

[Pigu.lt](https://pigu.lt/lt/gdpr) lists the Customer information, which they are collecting. Clients were informed to change Login Credentials without being sure there were data leak or none.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Having unified Page for Security related News could help to share Information faster, but may damage the Reputation. It could be used for giving Tips how to be more Secure during the (e-)shopping.
* Does there are Available information about Brute-Forcing Login Credentials of the Authentication Mechanism? Evil-doer could brute-force and afterwards Hash the Credentials with Basic and (or) Non-Secure Hash for giving more Trust in the Data he shares. There are more Flaws of the Websites, which does not require Brute-Forcing, i.e. OWASP Top10:2013.
* Very sensitive Information from Client-Side could be asked to Enter each time when info are necessary and later on Not-Available for Viewing from Client-Side. Especially, if this information are needed in rarerily Fashion.
```

```
##### I ncident

According [@15min.lt](https://www.15min.lt/gazas/naujiena/gatve/policija-paaiskino-kuo-gali-baigtis-valstybiniu-numeriu-slepimo-mechanizmo-naudojimas-221-1493346) in Social Media spreads offers to sell the Road Vehicle upgrades, which would allow to hide from the current speed scanning Cameras.
```

```
##### R esults 

More people may start using prohibited mechanisms.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* It's needed to be sure, that those Cameras are allowed to send and sends the Signal(s), when it's not possible to scan the Number of Vehicles License Plate.
* It's needed to review the Legislation and Rules to be clear what are allowed and what not. Local Citizens and foreign Visitors has to be informed about possible Penalty and (or) Punishment.
```

```
##### I ncident

According [@Lrt.lt](https://www.lrt.lt/naujienos/eismas/7/1409594/vilniaus-rajone-nupjautas-ir-padegtas-greicio-matuoklis) stationary Speed Scanning Camera were damaged.
```

```
##### R esults 

More people may put others in Danger by their behavior.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* For Physical Security it's neccessary that at least two Video Cameras would have Visibility of each other. Speed Scanning Camera could be made to give the Visibility of one Video Camera too.
* Increasing Communication and collecting the Feedback from the Citizens would allow to get the points where exists the Legal Problems.
```

```
##### I ncident

According [BNS](https://www.lrt.lt/naujienos/verslas/4/1408969/lietuvos-institucijos-net-ir-ispetos-toliau-naudoja-nesaugia-rusiska-programine-iranga) exists attachments to the specific Software. It increases the Fear for spread of the Viruses like [@Wikipedia](https://en.wikipedia.org/wiki/Petya_(malware)) to spread into specific Operating System Environment(s).

More sources:
* [ELTA](https://www.lrt.lt/naujienos/mokslas-ir-it/11/178192/petya-ne-virusas-o-galingas-naikinimo-ginklas)
* [ELTA](https://www.lrt.lt/naujienos/verslas/4/178342/valstybine-ukrainos-imone-teigia-patyrusi-nauja-kibernetine-ataka)
* [Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/178417/nustate-kas-gali-buti-atsakingas-uz-petya-atakas)
```

```
##### R esults 
Additional Software & Hardware Manufacturing Companies and their Goods gonna be added into Black-list of usage/selling because of National Security.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Having poor Hygiene of Information Security enforcement in the Country/Union leads into more Bans for their Companies and Goods.
* Mobile Businessess could adapt faster by changing their Environment into Locations where are less burden to their Businessess and less chance to be attacked by Cyber-Criminals.
* Banning Malicious Scans of the (Server) Network, which are done without Agreement.
* Allowing the use of Cyber-Criminal tools Only for specific professions and (or) groups of People.
* Building Responsible Disclosure Policy and tools for various Errors and Flaws of the Hardware & Software.
* Faster and more Quality in Response against the Incidents.  
```

```
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/1417661/viesojoje-erdveje-pradejo-plisti-netikra-galimybiu-paso-interneto-svetaine) exists Web Portal with similar functionallity.
```

```
##### R esults 

Around the Interwebs Citizens could click on the „masked“ Links and onwards They would get redirected into different Web Portal of Their choice.
Does Web Portal could be Trusted? and there exists no harm into entering Personal (or not for Public) data?
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
*   Before using some resource in the Interwebs You shall ask the following "rhetorical" Questions for Yourself:
*        Do You really need for such Service?
*        Does Your data in such Service are going to be safe or misused?
*   Need to get some awareness training for the Basic Security Measures while surfing the Interwebs.
*   Professional Services provides some Guidelines how to avoid negative Impact from Criminals or people, who spread Misinformation unintentionally.
*   There may be troubles in handling for such Services, especially when they are spread accross the Interwebs, so Professional Responce helps to avoid higher total Damage to the Citizens. 
```

```
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/1421635/lietuvos-bankas-nurode-blokuoti-dvi-interneto-svetaines) in the Global Network of the Internet exists illegal Web Sites, which offers their (e-)Services without legal backing in the Homeland.
```

```
##### R esults 

Internet Service Providers are implementing blocking measures, so their Customers (Citizens) would be Safe from such illegal Content.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
*   There could be a Way to privide the proof of the (e-)Service legitimity, i.e. for local Business certificates: [VMI.lt](https://www.vmi.lt/cms/verslo-liudijimu-duomenu-tikrinimas1).
*   For other Way: 
*        Does in Your Country exists such (e-)Service, which offers their (e-)Services legally?
*        Does similar and legal (e-)Services has some drawbacks, which decreases their popularity? What are those drawbacks? 
   
```

```
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1428867/nutekinta-didele-apimtis-kilobaitas-lt-klientu-duomenu-rekomenduojama-pakeisti-slaptazodzius) there were found the data leak in the e-Shop Kilobaitas.lt.
```

```
##### R esults 

About 191 thousand chunks of Data of the e-Shop Clients were lost including name, surname, email address, phone number, living apartament adress, encoded passwords.

According Privacy Policy of the e-Shop [kilobaitas.lt](https://www.kilobaitas.lt/Pub/default.aspx?Page=privatumopolitika):
* exists huge chance that Data of the Bank Account No. are leaked too.
* Data, which are needed to protect the Homeland Security, with Criminal code related issues and etc. (i.e. IP address, device number and other) are in Question.
* By providing name, surname, e-mail address it are possible to retrieve goods.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e. for Customers/e-Shops:
*   Don't use the same password in different Software Systems.
*   If there is no need, then don't provide Personal Data.
*   Use password managers, i.e. physical notebooks w/o risky Networks.
*   In physical shops does not ask for personal data, unless purchase are done using electronic means.

For e-Shops:
*  For how long You are going to keep the Data?  
*  What purpose of collecting personal data of the Citizens?
*  Does such Data are required to use every day/week/month/year?  
*  Does there are way to authorize Customers to the Service using, i.e. e-Government Gateway solutions and not keep the Data at all?
*  Does politics about Incident Response is in place and effective?
*  If you accept or process payment cards data, the PCI Data Security Standards apply to you, which one of the Goals — "Protect Cardholder Data". 
*  [PCI Security](https://www.pcisecuritystandards.org/pci_security/standards_overview)
*  Regularly Install Security Patches and Use Security Scan Tool from Official Site of the [cert.lt](https://site-.cert.lt/).
   
```

```
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1429971/sukciai-megino-prisijungti-prie-tele2-programeles-naudotoju-paskyru) some persons got access to the e-Service Accounts of specific People and took some Money from their Account Balance.
```

```
##### R esults 

Affected Persons lost Security of the e-Service.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e for Customers/e-Services.
* If the Client owns the Device of the e-Service, then it could be a way to try and enforce 2 (two-way) Authentication for selected dangerious operations. 
* Usage of the strong Passwords are only one Side of the Grail.
* If the e-Service gives You the Device and can't enforce more Secure Authentication mechanismus, then You are lucky, if Your loss are/got compensated.

For e-Services:
* Generiousity could be abused in long term.
* Most often the prisoners get hands on such scam.
```

```
##### I ncident

According [LRT.lt](https://www.lrt.lt/ru/novosti/17/1439369/ne-rabotaet-sait-seima-litvy-vnutrennie-informatsionnye-sistemy) some of the e-Parlament & e-Government Systems are not accessible because of the electricity loss.
```

```
##### R esults 

Internal and External Users lost access to the e-Services.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e for Customers/e-Services.
* Additional Source of the electricity is able to feed the Equipment or adding the possibility to switch into separate electricity Line could help. 
* Uninterrupted Power Supplies (UPS) helps to solve the Problem for some Time.

For e-Gov:
* Ministry of Economics and Innovation are knowledgable about Company which could help in such occasion with Example of the Australia.
```

```
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/1441302/prisidengiant-lietuvos-pasto-vardu-plinta-apgaulingi-laiskai-kuriuose-prasoma-sumoketi-muito-mokescius) some people are getting Notifications to pay the Tax for the International Parcels.
```

```
##### R esults 

People may pay for false Service, which in reallity were not Orderd.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e for Customers/e-Services.
* If Your are not waiting for the Parcel to come, then it's no point to trust for such Notification. 
* Don't spread the Word around the World Wide Web to other people that You are waiting for the Parcel to come.
* According [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/1441302/prisidengiant-lietuvos-pasto-vardu-plinta-apgaulingi-laiskai-kuriuose-prasoma-sumoketi-muito-mokescius) all post related notifications are send from Domain Name of the „post.lt“. Beware of the similar Domain Names „pos1.lt“ and other tricks of hidding the real Domain Name from the Customer.  


For e-Post:
* State Tax Inspectorate [VMI.lt](https://www.vmi.lt/) are cappable to locate local Bank Accounts and People who owns them.
* Only small number of people are using the Cryptocurrencies in the Country, so damage from such payments are void.
* Does there already exist platform for paying Some Kind of Taxes? If yes, then does it would be cheaper for the Country to Pay them with the same Infrastructure?
* Does it would be much simpler for the Customer himself that after the purchase in the e-Shops there would be made a Ticket in some kind of e-Post System? If yes, then does in the Country exists Services with some kind of API's (Application programming Interfaces) [lt.wiki](https://lt.wikipedia.org/wiki/Aplikacij%C5%B3_programavimo_s%C4%85saja)?
```

```
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1403651/pasaulines-slaptazodziu-dienos-proga-pasitikrinkite-kaip-greitai-nulauztu-jusu-slaptazodi) some experts suggesting to input Your password into some website and  for it's security.
```

```
##### R esults 

People may be interessted to input their passwords into some website.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* If Bank Employees does not ask for any passwords, then does it is different for any other e-Service? Your password must be secure and known only by You. Use Your password(s) only in the official place(s) of the e-Service.
* Does anyone are giving mutual trust for such Service? Let say, at least HTML link from the trusted Government Subject and other trusted third party.
* Does the Security of such Service is going thru the audit process? If yes, then who doing this audit? Does the Auditor could be trusted?  
* If there is legal need for several people to access the some content, then each person has to use their own passwords.
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
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/1467245/bandyta-surengti-kibernetine-ataka-pries-uzsienio-reikalu-ministerija) and LRT TV in Darknet Site is possible to purchase leaked public electronic mail-box of the Ministry of Foreign Affairs of Republic of Lithuania (following — Ministry). Ministry not provided any real useful comments on this event.

More sources:
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/1495642/ziniasklaida-informacija-apie-tyrima-del-kibernetinio-isilauzimo-i-urm-islaptinta)
```

```
##### R esults 

There exists possibility that data leak happen for real.
There exists possibility that between the data exists Confidential Documents and (or) Confidential Conversations.
State Control of Republic of Lithuania in the Past evaluated Ministry of Foreign Affairs of Republic of Lithuania Systems as Ad-hoc level.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
*   Public electronic mail-box, phone lines, mobile phones, Internet are not suited for Confidential Document transfer and Confidential Communication, Conversation.
*   Confidential Communication Networks shall be separated from Public Communication Networks and Communication shall be incapsulated with strong background of functioning Crypto Ciphers, so no leak from third party would be feasible.
*   In 21st Century there are Countries where Government, Ministries and Foreign embassies operates with each other in Secrecy "Chambers" and whitecollars have chance to register for Conversation using specific Handset or Device in the "Chamber" only.  
```

```
##### I ncident

According [BNS](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1488684/ekspertai-ispeja-naujas-kibernetinio-sukciavimo-budas-lietuvoje-gali-apgauti-net-budriausius) experts reports that there exists unknown subject who resells e-services by offering them with x20 higher price. 
```

```
##### R esults 

Worst situation for some company would be: lost money, because the e-service is a lot cheaper, and (or) lost purchase. And there is possibility for being dependent by unknown party without legit background.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Every time try to find out, if offered e-services are legit. Look for guidance in [State Tax Inspectorate](https://www.vmi.lt/)
* Every time try to find out, if company, which offering the e-service is legit. Look for guidance in [State Tax Inspectorate](https://www.vmi.lt/)
* Try to answer the question, if You really need such service: — Does in local Market there are e-services, which offers what I need, instead cheaper and for the same or better deal. If Your Customers comes from world-wide, then instead of "local" Market look for "local and global" Market.   
```

```
##### I ncident

According [BNS](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1366793/policija-pradejo-ikiteismini-tyrima-del-duomenu-nutekinimo-is-vilniaus-kolegijos) [I.]() were found data leak in one Lithuanian College and [II.]() Computer Systems were infected with Ransomware in the Lithuanian University. 
```

```
##### R esults 

Personal Information related with person and his competence, were disclosed for the Public.
Systems had to be restored from the Backups to get rid of the Ransomware.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* It's required to test out the Security of the Channel(s) between two or more Systems.
* Do backups of the System more often, i.e. when the Network load is at minimum, compared to the statistic of relevant period of time, would be good and safe choice.
* Get to Know, who have access to the Data, and create separate limited Accounts for person, or the system, which has to use the Data.
* After high impact incident(s) conduct awareness training for the employees, so they would be able to detect these incidents, would know how to act during the incident and to respond faster to the right place.      
```

```
##### I ncident

According [BNS](https://www.lrt.lt/naujienos/verslas/4/224408/registru-centra-paliko-e-sveikata-kuraves-a-bagdonavicius) e.sveikata Portal has Flaws. According [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1365413/programisiu-atakoms-tesiantis-ekspertams-didziausia-nerima-kelia-e-sveikata-saugumo-spragu-cia-yra-iki-siol) e.sveikata portal, which helps for the doctors to communicate with their patients, still has flaws, because of possible data leak. According [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/218723/e-sveikatos-spraga-aptikes-specialistas-si-sistema-tokiu-pinigu-neverta) Security Expert found the Flaw in the Architecture of the e.sveikata Portal. 
```

```
##### R esults 

Possibility of Data loss of the Local and Foreign Citizens. 
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Lack of Security Architects of the Information Systems would lead into poor quality of the System.
* Proper Security s were not implemented during Design and Prototyping.
* System were not tested manually for dangerious possible User Input of the System.
* Automated tools lacks functionality to test out from different User Roles perspective, because mostly Automated tools don't include Unit-tests according Privileged and (or) Un-Privileged Role?       
```

```
##### I ncident

According [Facebook](https://www.facebook.com/paysera.lt/posts/%EF%B8%8F-d%C4%97mesio-internete-aptinkami-netikri-paysera-puslapiai-b%C5%ABkite-atsarg%C5%ABs-ir-savo-/4660419064008610/) exists fake website, that try to represent original service. Existence of Facebook Account proves the organization's Contact Information [paysera.lt](https://www.paysera.lt/v2/lt-LT/index).

```

```
##### R esults 
Exists look-a-like scamming site.
```

```
##### I ncident

According [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/1538042/buhaltere-ikliuvo-i-sukciu-pinkles-o-prienu-savivaldybes-istaiga-neteko-daugiau-nei-35-tukst-euru) Article  some Employee of the Institution got fabricated e-mail with the Request from Director of this Institution. 
```

```
##### R esults 
Plausible loss of money.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* According the Article [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/1538042/buhaltere-ikliuvo-i-sukciu-pinkles-o-prienu-savivaldybes-istaiga-neteko-daugiau-nei-35-tukst-euru) it suggesting to use additional method to prove that the Request is correct. Then more Networking Technologies would be needed to manage at the same time, then does Institution will pay for that? Does longer period of time to complete the Request is Acceptable?
* Regular e-mail's problem is the Signature, which is plain text of Statements, which describes the Person or in this Sample (Requestor). If Anyone would try to send the e-mail with the same Text as Signature, then even in this Situation exist chance to be Victim of fabricated e-mail. Being Pro in finding out that e-mail is fabricated in long term will not help, because You still someday would do the Mistake and no warranties in protecting Yourself from this.
* There exist Asymmetric Cryptography for helping in this Situation and by having two Parts of Information (Public and Private) would be possible to protect e-mails, like everyday HTTPS tries to prove that Site, which You are browsing is original and not fabricated one. Does applications allows Protection of e-mail Signatures? each Person in Institution would send his e-mails by signing it with help of Digital Signature.
* The Site where Emploee work lists pretty much all Contact information of Institution and it's Employees, so this is not only Problem for the e-mails. If Director is "Public" Person, then he probably have to provide alot of Data about him.
* If Money would be sended to Foreign Country, then does it would not look too suspicious? would it be possible after some time to retain Money, if it would be sended to this specific Bank Account? Not all Payments are "Instant".
```

```
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/1470479/vel-uzfiksuotas-isilauzimas-i-prienu-savivaldybes-puslapi-paskelbta-melaginga-zinute-apie-migrantu-neva-nuzudyta-kuniga) in August were noticed breach in website of prienai.lt
```

```
##### R esults 
Criminals posted false information about event, which does not happen.
The posted information were Publicly Denied by Local Law Enforcement.
There were more past breach incidents to this Portal.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Allow Administration of the Portal with Privileges to post information only for Auth Personnel.
* Deny false information in broader range of Public Information Feeds, which are collected and reported about this and similar Incidents (Events).
* If this Incident repeats would be good to conduct Risk Assesment for determining possible loss of Trust as Online Portal.
```

```
##### I ncident

According [ELTA](https://www.lrt.lt/naujienos/verslas/4/1477558/lietuvos-bankas-dave-nurodyma-blokuoti-viena-interneto-svetaine) exists Portals, which offers illegal Services or e-Services.
```

```
##### R esults 
Government asks to block the Public Access to these Services or e-Services.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Keep Documentation of Service and e-Service up to date.
* Register Service and e-Service and meet the Legal Requirements for serving such Service and (or) e-Service.
* Get Approval as Legal Entity, which would have its own Entity Code and all the Rights to offer its Services and (or) e-Services.
```

```
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1488684/ekspertai-ispeja-naujas-kibernetinio-sukciavimo-budas-lietuvoje-gali-apgauti-net-budriausius) exists fake Institutions or Companies who offers Services and (or) e-Services illegally.
```

```
##### R esults 
Citizen are not backed by Country Legislation. 
Such Service and e-Service could be Scam.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Find Out Attributes, which could help to Identify that Service or e-Service is Real and could offer their Services.
* Find Out ways how to Report that You don't accept Spam messages, i.e. automatic-reply for messages, which has huge chance to be Scam and Spam.
```

```
##### I ncident

According [LRT.lt, ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/1559305/seime-chaosas-del-interneto-trikdziu-kuri-laika-neveike-svetaine-dalis-politiku-neprisijungia-prie-teises-aktu-sistemu) for some time Website of Seimas were not Available. There were problems with the Server (Hardware and (or) Software).
```

```
##### R esults 
People who require the Information of this Website could not get it.

```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Test Website Updates not on Production environment.
* Additional Server with Load Balancing could help to Serve Data until other Server is in Faulty Status.
```

```
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1572040/sukciai-elektroniniu-pastu-platina-kenkejiskas-programas-prisidengdami-valstybes-institucijomis-specialistai-pataria-kaip-isvengti-tokiu-atveju) over email Citizens of Baltic States get Malicious Programs. They are sended as from legal entities.
```

```
##### R esults 
By opening Infected File there are Possibility to spread Misinformation, Infect Your Device, participate in sending similar Programs to other Entities without knowing.

```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* More Security Tools for various range of Devices needed.
* The European Computer Driving Licence (ECDL) could educate to know more about Devices and how to use them Safely. Citizens could get support by Country's Government, so more Citizens would have easier access and would know how to operate during extreme Events and Incidents.
* Paying reasonable Price for Security tools and legal Operating Systems would be the option to keep better Safety. Some Linux Operating Systems are Free of Charge, but needs to be learned how to be used Safely.
* Need to have common sense in Actions You do. 
```

```

### 2022

##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/1601557/sekmadienio-ryta-be-elektros-buvo-apie-9-tukst-namu-ukiu-daugumai-elektra-atstatyta) in some regions people lost access to the electricity.
```

```
##### R esults 
Blizzard destroyed peoples Assets and access to the electricity.

```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
*  like Internet connection could be used from multiple sources, look for electricity from multiple sources.
*  own uninterruptible power supply (UPS), so You would be able to finish the work and (or) save Your work.
*  for specific period of time electricity from gas, oil, renewable could be used as additional source, Datacenters with special information system Services has such way for prolonging it's uninterruptible work.
*  with multiple sources of Connectivity and (or) Electricity would need to maintain it's functionality and safety.
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

According [Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1639172/stiprus-kartu-internetine-svetaine-patyre-kibernetine-ataka) there were DDos Attack to the stipruskartu.lt Site from Foreign Network Sources.
```

```
##### R esults 
Internet Service and Service could have some Interruptions. 
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* For Regular there are hard to distinguish, if the Site are Real Site, in these Concerns would need to prove it's Availability with True Intentions if there were App/Site Dynamic Code directly taken from such sites like VMI.lt (nowadays we already have a lot of online sources like pretty icons or bootstrap), so if State-Country can't provide Technological means, then every Person has to waste their time with Mobile Phones and search the Untrusted Web especialy, if there would be DNS Secure not implemented.
* Someone have left notice that: Information technologies Security Doctrine does not work. Maybe that's only something like this: While were asked only for some food, the People took and gave some Weapons?
* Similar Sites could be created nowadays in split of second, so who do You Trust? are these Actions is Real? why everything are going that each State-Country would live in their own Bubble of Information?
```

```
##### I ncident

According Various Sources around the Inter-webs People spreading News, when they not even Signed by Required Authorities. (Paranoa is Virtue)
```

```
##### R esults 
Possibility of Information to be an miss-information. 
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* mur mur jurisdiction.
* signing with e-signature, e-stamp and (or) using e.document system with public view would give better proof of the events.
* Placing the Bet or Bid of the events in this Country has huge Regulations already.
```

```

##### I ncident

According [-](https://www.lrt.lt/naujienos/verslas/4/1659104/premjere-reikia-nepamirsti-kad-dideli-rusijos-bankai-dar-neatjungti-nuo-swift) Some States wanted to Turn Off the Financial Stream on International Channels for specific Object.
```

```
##### R esults 
Turnin OFF in International Level probably are Impossible because of lack of personel.
Prices of i-Goods and i-Services and their Diversity would change.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* If International Communication made-done using Public channels, which has the chance to be faked with disinformation, then News and Information could not be trusted for 100 percent.
* Lack of personel could be made-done by having High requirements to which no one wants to apply. And sometimes, if You would take such person, the Higher Ups would Strip You down. Building better atmosphere in the Workplace would be good way for showing that Leaders and Mid-Bosses are Human and has to take the Action to solve every day Problems. Problems, which Higher-Boss, don't want to solve, but in contrast, if these Problems gonna build Up, then later on it could to Blow with more Damage.
* If people lack of Knowledge, then they could be given some time to Learn Stuff including specific Rules, Policies and Legislations for specific Job. Periodical -up of new updates and full Active document would be needed to take into the consideration. Usually such s are made for Practice on First-Aid and Fire Protection knowledge and actions -up.
* Conducting Risk Assessment on various organisational Risks is First for Organisations with High Profit and In Huge countity of Personnel. Smaller Organisations could not catch up with Risk Assessment and Management.    
```

```
##### I ncident

According [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/1665362/sutriko-vyriausybes-interneto-svetaines-veikla) there were some interruption in Government Web-Site.
```

```
##### R esults 
During the time of interruption no one could access the Web-Site and get their e-Services (probably including second domain of *.lrv.lt).
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Data Center usualy tries to Secure Availability 24 (twenty-four) hours per week and 7 (seven) days per Month.
* From Public Space were given nothing informative regarding this Incident. 
```

```
##### I ncident

According the view of [-](https://web.archive.org/web/20220420093617/http://eimin-lrv.lt/lt/naujienos/ministerija-pateike-premjerei-ingridai-simonytei-siulymus-del-valstybes-valdomu-imoniu-optimizavimo) there were registered second level domain address (i.e. http:/ /third.second.top) which are very similar to the other portal of third level domain [@lrv](https://eimin.lrv.lt/) and according of [domreg.lt](https://www.domreg.lt/paslaugos/whois/?search=eimin-lrv.lt) one of them were blocked.
```

```
##### R esults 
People may be in confussion because of not knowing which of those domains are real and which ones a copy and (or) wrong one.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Lithuania have around two organisations which cares for Copyright rights and defends the Authors of their Authorship.
* Such organisations in long run could start to defend Authorship of Authors Voice (i.e. for AudioBooks) and Authors Face (i.e. against "Photoshoped" Pictures and Videos) as intelectual property of the Author in usage of various Technological Situations, unless Authors allows it.
* In more early beginning people have to get Technological literacy which would help to distinguish which is real and which one is not (the impersonation).
* In search of History Defending Sides. Usually smaller Side can't Protect himself good enough, because they do not have capacity to do it.
* You need to pass the data, which are given to You, and if You know that the Site could be Trusted then try to search for specific Path for Yourself to the Object about which You are interested. Usual Law for Countries to offer Three Click rule to the access to the Sites Content.
* By opening random documents they may lead into some (un-)known vulnerabilities. Your Desktop would be more Secure, if You would use Minimal Installation from the Start. Finding and responsibly reporting such vulnerabilities could help for some organisation to fix their poor Quality Products. Such vulnerabilities may harm Your own Products, if they are not prone to these vulnerabilities.    
```

```
##### I ncident

According the [-](https://www.lrt.lt/naujienos/verslas/4/1691880/sukciai-vel-siaucia-siuncia-sms-pranesimus-su-fiktyviomis-swedbank-nuorodomis) SmartPhones has Security issues regarding spread of Short Message Service with internet-based-links.
```

```
##### R esults 
SmartPhone users possibly could leak sensitive information or even inject their Phone with Malware code, which are directed to (specific) Phones.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Usual approach during the Work for Law enforcement Sector — prohibited use of Personal Phones, SmartGadgets.
* Usual approach for Children up to 12-14 (Years) — prohibited use of Personal Phones during Lessons in the School time.
* Rest is up to You, because Phones are every time with You. Any small direct vulnerability could lead into specific leak of information (location, voice recognition service, microphone control, data in physical storage, data in dynamic storage). By knowing location it's only question of how precise data is which could lead into unknown consequences, if they would be leaked into bad-negative intentions toward You containing entity.
* Look for indications of possible phishing Site. In last resort it's always is good point to know where is Physical Office of the Service, which You are owning, in Your Country. 
* Various Professional Services has Monitoring Capabilities and sends notifications, if something is up, just like in this case.
```

```
##### I ncident

According this Article [-](https://www.lrt.lt/naujienos/lietuvoje/2/1693454/stiprus-kartu-kreipesi-i-policija-del-sukciavimo-atsiradus-istaigai-identisku-pavadinimu) the Police have to interfere for solving the problem of two distinct and similar entities, which has one year difference in registration.
```

```
##### R esults 
People could be fooled by not knowing of their wanted entity.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Internet is horrible place, because when You are registering hostname-domain name then everything are take cared by registration authority, if some name are already taken, then they would suggest similar name and sometimes not pretty one, incl. numbers, symbols, etc.
* One of those entities has electronic mail, other does not have yet, so one of them has already registered hostname-domain name.
* Don't allow to register microsoft.<country_initials>, google.<country_initials>, because You would be sued for phishing attack on the Big Tech Company? There still exists problem for names like m1crosoft.<country_initials> or goog1e.<country_initials>, because this could be used for creating fake hostname-domain name services over Internet, over Digital e.Space.
* By returning back to previous entities, they sound similar, but one of them are with longer sentence. Usually people are too lazy to type more, so with shorter sentence hostname-domain name already with advantage, rest is only question of quality of service. Does those (up to year old) services saying the Truth in their Slogans. ing legitimacy for Payed Taxes to the Country Budget could be begint-started at first.
* Nowadays big tech companies are extending their Volume-Size by Creating Bigger Brand Name, so if those entities align in the purpose, which has the same target Audience, then it would be wise to do collab entity. Your Customers don't need to pay, i.e. twice with less money in both places. But if something happends with one fishy deal, other could reach the required destination.
* The Bigger Question in Letting register such names with capital and (or) non-capital letters which starts as "europol" shown in here as [BNS](https://www.lrt.lt/naujienos/verslas/4/1693782/gazprom-pranese-nutraukiantis-duju-tiekima-vamzdynu-jamalas-europa) and it could have links to entity, which are located in The Hague, Netherlands and is main law enforcement agency in the Continent.
```

```
##### I ncident

According this Article [-](https://www.lrt.lt/en/news-in-english/19/1697439/lithuania-s-mod-website-targeted-by-massive-cyber-attack) Ministry of Defence had "massive" Cyber Attack.
```

```
##### R esults 
Not enough details of the attack.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Let's say guess: one Department updated functionality, second Department tested security in Production env., no report were made for updating-testing their own Product.
* website update could mean: it contain full server swap with new and more robust server, before testing it's security using automated tools-instruments according the Law from the Constitution and International Order down to Law of Institution level would need to communicate for Availability of security-pentesting.
* if website would be updated into popular known frameworks, then would require to  for keeping it updated in regular basis.
* if website would be used only for representation reasons, then does full capacity of flashy functionality would be needed? probably not so, if security is a mission. 
* Hardening the server would mean: adding aditional security measures, minimizing it's functionality for required only. 
* What You don't know could be the issue for the Unknown consequences. Separation of public website from internal portal would help to minimize consequences of outside attack. 
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/eismas/7/1700185/alytaus-rajone-pasikesinta-i-vidutinio-greicio-matuokli-ji-nupjove-ir-apgadino) someone damaged Cameras which collects speed data of the Vehicles.
```

```
##### R esults 
Law enforcement will need to do more purchases. 
People who pay taxes gonna pay for it.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Usually speed data collection could be done in these ways: Using Automobile with or without integrated Spec Camera; Stationary Cameras, which were damaged according the Article; Mobile (small-medium size) Cameras, which could be used by Law enforcement Specialist or with Protection; Speed collection using Satellites from Above.
* When last one Tech will come in place, then there will be no motivation to do such things which were shown in the Article.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/eismas/7/1700557/policija-pasidalijo-draguno-sulaikymo-irasu-atlikejas-pludosi-necenzuriniais-zodziais-ir-pasipriesino-pareigunams) were shown how Police arrest Suspect for holding something in his hand while Driving.
```

```
##### R esults 
Suspect does not have phone holder in his Vehicle for using phones correctly.
Police does not have laptop holder in their vehicle for using laptop correctly.
Both sides are in error.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Nowadays You could Purchase electric Vehicle's with Cameras and in-build IPad Control device directly in the Vehicle.
* There are lacking of awareness trainings of the Commoners for using specific devices for pedestrians, drivers, pilots.
* Idea: Does everything could be ended up to 3:17 with the Notice for need to pay for the error, which were done by the driver, if final cost of the Punishment is very low?
```

```
##### I ncident

According this Article [Vilnius.lt](https://vilnius.lt/lt/gyvenamosios-vietos-vilniuje-deklaravimas/) there are given link to get Information for Foreign Entities how successfully declare their Residence Location in Vilnius. The links given for LT, EN, EU, etc. The EU link are directed to Russian speaking section (non Ukrainian). 
```

```
##### R esults 
No translations given for simple Service as Declaring Your Residence Location in Vilnius.
Confussion for people.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Adding link for Foreign Future Citizens and linking it named as "LT" according LST ISO 8601:2006 and LST ISO 3166-1:2020 in Informative Annex D for "Lithuanian" citizen is not appropriate enough. Could be added at least: "News for LT", "For interesants of LT", etc.
* The web-site gives the Question for which Citizens according LST ISO 3166-1:2020 are given Guidance: uk/ukr and (or) ru/rus?
* Reading the old and well known News in the Media does not show that "LT" Country is treated as with Democratic Background Country/State or whatever [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/77745/lietuvis-paryziuje-gali-valyti-langus-ne-visur-trukdo-kilme-ir-svetima-istorija) 
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/eismas/7/1726347/lietuvos-gelezinkeliai-susiduria-su-kibernetinemis-atakomis-keleiviams-interneto-svetaines-gali-buti-laikinai-nepasiekiamos) Train Public Infrastructure, i.e. Websites which allows to Purchase Tickets, are getting DDoS attacks.   
```

```
##### R esults 
Regular Customers has issues for Services over Internet like:
* purchasing e.Ticket
* viewing Train Routes and Timetable
* reading Service related information 

Other Customers, who communicate over Internet for their e.Services, could be Jammed for their new Requests and get Responses back. 
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* use other communication network like payd phone service;
* printed brochures and booklets with planned Routes and Timetables;
* temporarily exchanging signed documents with e.signature via other platforms like Google Docs; 
* look for own Country Cappability to build Internet Service for their Institutions, Critical Infrastructure which is similar to those Services offered by [Cloudflare](https://www.cloudflare.com/). 
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/pl/wiadomosci/1261/1727874/trwa-zmasowany-cyberatak-na-rzadowe-witryny-internetowe-i-uslugi-cyfrowe-wladz-publicznych) in Information Systems and Websites of the Lithuania are spreading harmful automatic logins as non-stop repetition to get access into these Systems.       
```

```
##### R esults 
Does automatic tool and (or) person has real Rights to access some System to get e.Service?
Systems could get DDoS with those repeatitive actions.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Review of Treaties, Agreements, Contracts would be wise way to find solution for such attacks to stop.
* Does System and (or) simple Application has Security Controls in place to make such attack wasteful for the Attacker?
* All Country Systems has meet at least minimal Requirements which are enforced by help of National Cyber Security Center of Republic Lithuania under Ministry of National Defence. 
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/1730599/scholzas-maskvos-kaltinimai-imperializmu-absurdiski) there is High Chance for need of the Global Awareness training about the Cyberbullying.
```

```
##### R esults 
Entity Country would be bullied through the Web, because it is very easy to do so.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Nowadays even Mayor of the City in Modern way stream his Cabinet (Online/Live) for wanting to be Available for everyone to Judge his Work.
* It's not rare that Higher Position of the Person, then Higher Effects of Cyberbullying would be done.
* In the Web exists more dangers to find Fake and Untrusted Information, i.e. with Photoshopped or Media-Video Edited Content, from which Popular-Influental Peoples Face-Body-Voice would be used against their Will to make some "meme" Content with hidden idea/aim of the Message. Maybe it would be Wise to try and send back all the message. Maybe it would help to find out, if sender really mean that, or it was just "in the Mind" of his or someone. 
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/1733853/vdai-pradejo-tyrima-del-svaros-broliu-klientu-duomenu-saugumo) there was Incident who lead into loss of information of the Internet Service Users from the following: name, surname, e.mail, phone no., automobile registration plate. 

```

```
##### R esults 
50 thousand of users lost their personally identifiable information.
[ELTA](https://www.lrt.lt/naujienos/verslas/4/1993539/svaros-broliai-neskus-vdai-sprendimo-del-dalies-klientu-nutekintu-duomenu).
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* From some Information Security Professionals nowadays You could hear suggestions to write only Information with the Asterisk* - required. Systems could hold Information in separated environments, i.e. from Public Website registration form the Information could be taken into Internal Network Site which does not have any direct and (or) physical links with Public website.
* Automobile registration plates are popular in various Parking Places which helps to remind where You have left the Automobile and (or) drive in/out the Parking Place. For getting the Identity of the Owner the Road Police Systems and other sensitive information Databases could be the Target in External/Internal fashion.  
* According [The State Data Protection Inspectorate](https://vdai.lrv.lt/en/) Personal data - any information about natural Person which Identity has been determined or could be determined. According [THE EUROPEAN PARLIAMENT AND OF THE COUNCIL](https://eur-lex.europa.eu/) No. 2016/679 regulation of General Data Protection Regulation's (GDPR) 30th preamble displays the concern of Internet Protocol (IP) address which were used to determine the Attackers of the Site. The Problem with the Article - it does not say, if natural persons has lost/not lost their IP addresses. Leaked IP addresses could be used further to penetrate into deeper Network for finding out the real Identity of the Natural person and in this case such Telecommunication Networks of "Tele2", "Telia", "Bitė" would be the next Target. If the Internet Service Providers (ISP) distribute Static IP Addresses, then information of IP address would be personally identifiable information for Years in their Databases. If we would assume small - medium size ISP, then there would be question: does You with the Client renew the Contract with Customers? because of new regulations around, i.e. GDPR.  
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1735660/ignitis-grupe-skelbia-patirianti-didziausia-kibernetine-ataka-per-desimtmeti-atnaujinta-svetainiu-veikla) Web Site(s) of the e.Service are getting DDoS attacks. 
```

```
##### R esults 
Customers of the e.Service for some time had latency issues for accessing Public Internet Site for their Services.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Public Web Sites are not linked with SCADA or Critical Infrastructure.
* Constant DDoS connections could be dropped to the /dev/null fashion.
* These DDoS attacks does not contained any breach and data leak characteristics. If Successful DDoS breaks Availability of the e.Service and Access for the Business/Enterprise and common Citizens. In Modern Ways there would be possible to Turn Off the Foreign Traffic and allow only Local One depending if there exists Business/Enterprise Customers outside of the Country.
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1738954/alio-lt-skelbia-patyrusi-kibernetine-ataka-galejo-nuteketi-345-tukst-klientu-duomenys) somebody tried to guess real account ID's and phone numbers in the Portal alio.lt
```

```
##### R esults
Up to 345 thousand of Customer data like email, phone no. including credential related information could be leaked.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Sensitive information: Bank Account No., Payment Card Data, Personal Codes, Home Address were not stored in the Portal alio.lt.
* Exists probability that Portals functionality upon creation were not tested for inputing specific information from Universal Resource Locator place.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1730298/killnet-smoge-ir-verslios-lietuvos-klientams-pranesama-apie-pavogtus-asmeninius-duomenis) were stolen Customer Information who were registered for use of https://skaiciuokle.verslilietuva.lt Calculator.
```

```
##### R esults
Customer information like first name, last name, email address, phone no., home address and credential related information were stolen.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* If home address information were lost, then it would be called as Sensitive information.
* Finance related information were not collected for registration to use Calculator.
* The Question: Does the Calculator is really worth for the Registration Form? 
* Nowadays exists number of Calculators who would help for the Small-Medium Businesses to make their bureaucratic work simplier and faster. More benefits for the Portal would be instead of Registration form to provide "Money Donation" link for specific "Business Goal" and (or) cause.
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1769335/turto-bankas-patyre-kibernetine-ataka-buvo-sutrikusi-svetainiu-veikla) the WebSites like turtas.lt and valstybesturtas.lt were not accessible for 30 (thirty) minutes becaus of the DDoS attack.
```

```
##### R esults
Some Service in described period of time would be not served to the true Customers. 
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* There exists Risks that some Customer could Bid in Auction and DDoS for Winning his Bet.
* There exists Risks that Institution choosen not appropriate term of "putinOut". "Put" means "to Place something somewhere", "in" could start with Cap letter for meaning "to get something into/inside" and "Out" means "to get something outo/outside". The only question how is it related to the electricity bills? these tricks are usualy found in produced "Postage Stamps" or even "Envelopes".
* For proper naming it would be advisible to use native language letters [vlkk.lt](https://vlkk.lt/naujienos/kitos-naujienos/internetas-darosi-daugiakalbis-ir-lietuviskas) or, if there is meaning related to specific foreign language, then use this specific language, because in other words it is stupid.
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/verslas/4/1779812/ziniasklaida-uber-planuoja-uzdaryti-it-padalini-lietuvoje) Technology companies meet shortage of human resources in the IT field. Because of this reason they will need to leave from the region.
```

```
##### R esults
Less of advanced technology sector companies gonna lead into even less inovations in the sector for which tech company are good at.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Information technology (IT) sector is one building block in successful technology management in the company. By having not enough personel could lead into situation when proper organisation management are not possible and Quality of Customer Service in longer term would decrease drastically.
* IT sector and Advanced IT companies are challenged by Risks to area of their Information and Information technology Security and CyberSecurity. Relocating their assets is only one approach of managing current-future Risks.
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/verslas/4/1787006/bankines-sistemos-tiekeja-bankinglab-patyre-kibernetine-ataka-pradetas-tyrimas) BALTIC AMBER SOLUTIONS (private limited liability company) Site had intrusion from external sources and some private data were leaked. Representative of the company are telling that no critical private information were leaked and access to the money is secured.
```

```
##### R esults
Some of Customer data were leaked.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Incidents and breaches has to be reported according Cybersecurity Law like following formulation "The cyber security policy is implemented by the National Cyber Security Center, the State Data Protection Inspectorate, the Lithuanian Police and other institutions whose functions are related to cyber security.".
* The private limited liability company has the Site of URL	https://bankinglab.com which are using popular Content Management System which in the year of 2022 accumulated around of 1000 security vulnerabilities. Regular approach of Security in here to keep up with the updates which fix the problems.
* Specific Banking applications and it Hardware & Software manufacturers must provide their Issues in the same way how these companies are doing URL: [Oracle.com](https://www.oracle.com/security-alerts/#SecurityAlerts), because they want to be Available in such Banking Transactions.
* Does Certificates of the Public key Cryptography of the SSH are regularly updated like SSL Certs for Site Security?
```

```
##### I ncident

According this Article [-](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1187414/lrt-faktai-vagystes-is-bekontaktes-korteles-ar-galima-ja-laikyti-kelniu-kiseneje) strange Videos are comming from Internet Social Networks, high chance that is from Foreign Country. People are attacked by Pickpocketers with Contactless Payment Card Scanners.
```

```
##### R esults
People would lose money, if someone would approach with such Device with intent to scan Your card.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* In normal environment of the Banking Institutions and Gov Regulations it would be impossible to use locally selld devices in the E.U. Banking system.
* Who knows, if there would be Foreign Devices and Foreign Services which would be able to do the Scans. 
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1820550/melynu-varneliu-chaosas-twitter-apsisaukeliai-apsimeta-itakingais-asmenimis-o-platforma-nezino-kaip-su-tuo-tvarkytis) Crow Sign (Symbol) does not every time (always) mean: What You See Is What You Are.
```

```
##### R esults
People may be fooled by entities on the Platform which has proof of their Identity.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* In some extend Social media of "Facebook" are trying to keep whole users community base as non-Fake Accounts. In that case each Union/State/Country has representatives who help to block those Fake Accounts, in instance by initiating and clicking Button to Report the User as Fake Account.
* Identity  and Private and Personal Information storage and management requires additional Compliance to specific jurisdictional and standard regulation. Does the Company are compliant with any of those standards?
* In this Situation: does there will be enough of employees to manage the problem? 
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/1832729/daliai-vartotoju-sutriko-mano-vmi-veikla) State Tax Inspectorate Site over the Internet has irregular Workflow.
```

```
##### R esults
Part of the Clients can't access their Services as usual.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Irregularities could be caused by Application/System Wide update(s), system policy change, i.e. password policy.
* Not proper SSL/TLS Certificate change(s) would find Internet Browser Apps. 
* Common Service provider Apps which are installed into the SmartPhone are another part of the Clients who are accessing the Site Infrastructure. 
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/en/news-in-english/19/1833149/over-220-000-lithuanian-numbers-among-leaked-whatsapp-data-media) Single Service of American Company Meta had huge data leak of User Private information.
```

```
##### R esults
Two hundred twenty thousand Users from Lithuania are potential victims of this Service.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Big Tech Companies are promoting Huge Security Shields in which case You have to share the Private information like Mobile Phone Number.
* Two step verification in usual fashion may require/requires mobile phone number, or System are directly connected to the specific Telephone Number.
* Nation/Union/State promoting easier way to swap their Telecommunication Company Service with moving their Mobile Phone Numbers between them, but in this case if Private data are leaked, then every Script-Kiddie would be able to link specific phone number with some Individual. In many cases Individual loses his Private Life, if the data would be used, i.e. for Fraud and Scam attacks by calling to the elderly for the Ransom or Racket.
* There are jurisdictional questions about the Place of the data which were kept during the Leak and does the Citizens from Countries like Lithuania has a chance to say "General Data Protection Reglament" or so. There are lacking for various Services where People would leave their opinion on further actions with more ease.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/1834461/sutriko-elektroniniu-valdzios-vartu-veikla-gyventojai-pranesa-negalintys-prisijungti-prie-sveikatos-ir-administraciniu-paslaugu) exists messages with problems to Authenticate via epaslaugos.lt
```

```
##### R esults
Some Customers will not be able to access their Services for some duration. 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Via Platforms there are number of ways to connect, i.e. Direct-connection, Bank-link, Single sign-on, Identity Card. Providing more detailed information, which Auth mechanism has problems would give more Ideas and more rich Picture about what is happening.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/1849845/maskolija-ir-putino-zombiai-nesuprasdamas-lietuviu-kalbos-facebook-blokuoja-net-ir-renkancius-parama-ukrainai) the foreign service - Facebook (Meta) does not block (according Google translate "questionnaire's") and probably data puts, and posts, which directly questions & asks to do threat to the Human by taking his life.  
```

```
##### R esults
AI with human error functionality are not perfect, which has chance to lead into Atomic Nuclear Disaster & Catastrophe in the Future.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Minority languages and ethnic groups usually has less data for machine learning. If the language are not used, then there are no way that somebody would create tool or instrument for small size Community.
* Usually language could be misinterpret, if there would be taken wrong mapping of the dual-language data or some mistake were done by some adversary with the intent.
```

```
### 2023

##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/1863426/vegele-tikina-neregistraves-internetinio-domeno-prezidento-rinkimams) there were registered Web Domain from Unknown Source.
```

```
##### R esults
Anyone are cappable to register any Unique and non-registered Domain, i.e. www.uniqlo.lt which does not exist in the Republic of Lithuania at this time. 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Domain Name tells nothing, begause "vegele2024.lt" could be misstook/taken something as following URL https://www.vegeta.us.com
* There exists chance that some huge Brand would move into some Continent/Region and somebody want be re-sellers of the Domain in higher sum of Money.
* Usual price of a Domain could start from single one EUR'o, the Electricity prices and Administration cost increases it exponentialy.
* The Main Problem for Domains - does they belong to UTF-8 Charset or by default American Standard Code for Information Interchange one. The "xn--" solution are a "hack", which helps people live with the same tech for some longer time and more Internationalization. Opening "raštija.lt" it does not feel like it even looks like this: "https://xn--ratija-ckb.lt/" or in some gibberish serialized syntax.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/1876521/perspejami-gyventojai-veikia-piratine-spis-svetaines-kopija) information system of the Ministry has similar public copy, which operates in Internet and to which could be gain access by clicking phishing link.

```

```

##### R esults
Probable loss of contact and personal information of Individual and open doors to more security and privacy related issues.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Probable purchase of domain naime are not ed by simple List of Critical or not so Critical Information Systems, where there would be added limitations how similar are domain names, which already exists and new wish of domain from some new entity, i.e. l and 1 are similar in used encoding table, so it means, when You purchase, i.e. domain name of "love", the "1ove" would be added in the Basked too, just to overcome such phisching scam from someone, in this sample the Victim is who does not have what to offer.  

```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/1926863/banko-darbuotoja-prisistaciusi-moteris-is-vyriskio-isviliojo-beveik-8-5-tukst-euru) there exists case of situation, when person is robbed by somebody by Fraud and Money Laundering attack.  
```

```

##### R esults
Person got punished by criminal law for such event.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* The situation provided that "bank employee is calling by phone to the client" is not enough to get full picture of what happened. In this case would need to question how big case could exists when somebody leave specific flaws in the technological phone application, which would allow for the bank to communicate with their customers in more secure way. These flaws would affect not only one person and instead every user of such app — affected.
* By taking first point as main, then there already exists number of services who offers telecomunication payments. If person could purchase something with help of "SMS" message, then there could be dangers, does this technological peace of equipment — phone technology is really without the flaws of being abused in similar fashion (pretending for donor care).
* Questioning about Bank services: Does bank offer service over the phone - call center? In this case client would call to bank instead i.e. to ask for some changes in the contract between the bank and person. If specific peace of information is enough to get money transfer done, then how would be dangerious, if someone else would get exact same peace info and for what reason would be using that? 
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/1949588/sukciai-nesnaudzia-kone-tobulai-apsimesdami-vmi-bando-isvilioti-pinigus) business type of domain imposing as original site "vmi.lt".
```

```
##### R esults
By using imposing Sites there are extremely high chance to lose credentials and private information.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* The Website which are imposing as "vmi.lt" has ".net" domain. In contrast domains like ".net", ".gov", ".edu", ".mil" are in many times "stronger" stance as something as single ".lt" domain name.
* The Portal of common domain purchase in U.S.A. is [GoDaddy](https://www.godaddy.com/en-ie/tlds/net-domain?countryview=1&isc=e1domgon1&countryview=1&currencyType=EUR), which allows to do World-Wide purchases and promotes original Country names on which they have been decided by the Country himself, in instance the "Türkiye".
* Exists domain name forwarding, i.e. by going into "vmi.net" could be made Browser forwarding from Server side into a Site of "vmi.lt". In this case everything could end up better than described in the "R esults".
* Bi-polar situation in the LTU, when there exists Site's like [Data Agency of the Country](https://www.stat.gov.lt/), when ".gov" domain name in use just after ".lt". And in the end we own normal domain ".gov.lt" for the Government domain + LTU domain. Now let us take the situation of sample domain of Lithuanian institution [IVPK](https://ivpk.lrv.lt/), which produce ".lrv" domain + ".lt" domain. This is equal situation of Government domain + LTU domain. Which one could be Trusted? or does they both (.gov.lt) and (.lrv.lt) are Trusted domains? where first represent TopLevelDomain + CountryCodeTopLevelDomain and second represent some simple Domain + CountryCodeTopLevelDomain.
* If there would be poor Country with small amount of technical personnel and skills maybe would be greater to pass such situation into those who control ".net" TopLevelDomain and would handle it according their jurisdiction. Some Samples with SecondLevelDomains could be found in here [Wikipedia](https://en.wikipedia.org/wiki/Subdomain).
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/1956730/vyriausybe-is-esmes-pritaria-seimo-nariu-siulymui-atsisakyti-ribojimu-imoniu-pavadinimams) there is no incident yet. Article provide ideas about allowing various type of entity names Registration, which would include letters and numbers, which "could not be understood as words".
```

```
##### R esults
Assume someone want to register "ąpple.lt" domain name or some other site, which could have risk to be used as fake Site.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Let us take idea that Universities has better Knowledge in specific areas as in this Article [Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1257917/mokslininkai-kibernetinio-saugumo-terminu-zodyna-rengia-pasitelke-ir-neuroniniu-tinklu-technologijas).
* Let us take the idea that official public acts, which show specific programmes incl. here [e-seimas.lrs.lt](https://e-seimas.lrs.lt/portal/legalAct/lt/TAD/89b5405490cb11eb998483d0ae31615c/asr) Attachment|Appendix|Annex provides 3.1. point for "Supporting academical <...> Dictionaries <...> File Sets of those Terms and Definitions", which would include in seven Year period to spend in total 1 million 365 thousand EUR.
* For number of Years public instututions provide links to Trusted Sources like in this Site [vlkk.lt](https://vlkk.lt/nuorodos/zodynai). Data Sync and Update from various Databases are yet simple. Common people can't get access in one place by specific regular Search "Tree", i.e. first link to Knowledgebase of Cybersecurity Terms and Definitions. By ing this [terminai.vlkk.lt](http://terminai.vlkk.lt/paieska?search=Cyberbullying&zodzio_dalis=0&kalba=2&kaip0=on&sritys=&statusas=0&rykiavimas=0) out, non-NULL result given, simple Zero.
* Zhōngwén or similar languages could be selected by terminai.vlkk.lt in Advanced Search Settings by clicking box on the last option "All lang.". This option represents the same Ideas as the original Article. 
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/1971075/paspaudus-elektroniniu-pastu-gauta-nuoroda-moteris-neteko-daugiau-nei-8-tukst-euru) Citizen of the Republic of Lithuania is victim of CyberSecurity Incident. Citizen not only clicked the link, he even entered proper Credentials where it were requested.
```

```
##### R esults
Citizen lost (some) Money. 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* By clicking the link the Computer System probably has received request to sign in into the Computer System over common functionality of Computer System. This functionality often is used for letting fix some Computer Issues like Installation of AntiVirus Software. Citizen were not aware of pop-up Window and Clicked a Button, which let some Entity In the Computer System. This Entity probably even clearly seen what a Citizen is doing.
* Commonly approval of each Financial Transaction requires to enter challenge code, which Observer can't known. In this case: Does this even a Bank organisation? 
* CyberSecurity Law of Republic of Lithuania [e.seimas](https://e-seimas.lrs.lt/portal/legalAct/lt/TAD/f6958c2085dd11e495dc9901227533ee/asr) and [vlkk.lt](http://terminai.vlkk.lt/paieska?search=Cyber&zodzio_dalis=0&kalba=2&kaip0=on&sritys=&statusas=0&rykiavimas=0) does not help much in building the CyberSecurity term|definition Bank to name Crystal clear Situations in a CyberSpace. CTRL + F and type „sukčiavimas“.
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

According this Article [BNS](https://www.lrt.lt/naujienos/pasaulyje/6/1997501/jav-ir-microsoft-kinu-kibernetinis-veikejas-atakuoja-ypatingos-svarbos-infrastruktura) Name of the Link: one actor constantly attacks Critical Infrastructure over internet. In Articles's Content the plot shows that this actor left notification as his common informative approach.
```

```
##### R esults
No idea about a damage done.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Information related to Critical Infrastructure is secured via number of locks and security labels, so public information mostly does not ring a bell.
* Usual News Agency trick — to make hyperbolic title, when the content does not catch up. The Worker(s) of a News Agency probably has though time and live from bill to bill.
* Artificial Intelligence (AI) Feeds potentially are taking out the Bread from the News Agencies. The problem for the Consumer — Does there exists regulation and (or) even notification, that the Content is (are) generated from AI?
```

```
##### I ncident

According these Articles of [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2000374/del-techniniu-problemu-neveikia-seimo-interneto-svetaine) and [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/1991368/laikinai-buvo-sutrikusi-seimo-interneto-svetaines-veikla) exists technical glitch in the e.Seimas Portal and (or) technical Support.
```

```
##### R esults
E.Service does not Available for at least of 141 persons and their Support for some time.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* E.Citizen may lack need to use such e.Seimas Portal, because nowadays in this Modern era there are more debates in Social Media Networks.
* Technical glich is best as You could get as Public Report, because everything is hidden according the Law, which may be accessible from the same Site-Portal.
* Paper version of „Valstybės žinios“ are not Available for many Years, so there exists backup e.Service [InfoLex.lt](https://www.infolex.lt/) for Jurisdictional Information.
```

```
##### I ncident

According the Article [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2001164/lietuvos-imonems-smoge-ddos-atakos-buvo-sutrikusi-interneto-svetainiu-veikla) Private Sector companies are getting DDoS attack's.
```

```
##### R esults
e.Clients can't access their e.Services.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* According State Enterprise Centre of Registers the „Akcinė bendrovė“ "City Service" is unregistered. The entity [City Service, UAB](http://www.cityservice.eu) is not registered.
* National Cyber Security Center got honeypot Nets in place and keeps communication with entities, which are affected.
* Does there exists entity E.U. wide registration Form, which would be accepted in some way in the State Enterprise Centre of Registers?
* The lack of CyberSecurity Magazine for daily basis could be felt near Magazine Kiosk also, if they gets support by the Republic.
```

```
##### I ncident

According the Article [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2001263/avia-solutions-group-patiria-ilgalaike-kibernetine-ataka-is-rusijos) Cyber Attacks, which are conducted without any kind of coordination could be handled by any Professional entity.
```

```
##### R esults
Disruption of e.service.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* By having capability to close Nation Wide (well) known VPN public-private networks in the Foreign Country could be one step to more Secure Plan for handling these Cyber Attacks.
* Exists Private and Public Web Sites, which usualy at minimum and at least provide knowledge based service over internet.
* National Cyber Security Center got their hands on [National Firewall](https://www.nksc.lt/uzkarda.html), which could help in some way for small and medium Enterprises.
* From jurisdictional acts, which asking for people to input their Contacts online for everyone to surf, does this just pointing out that all of those contacts only helping out for them to conduct their Operations?
```

```
##### I ncident

In this Article [BNS,LRT.lt](https://www.lrt.lt/ru/novosti/17/2001245/predpriiatiia-i-uchrezhdeniia-litvy-podverglis-kiberatakam) shown Image from one of „хакерским“ toolset.
```

```
##### R esults
Promotion to use „хакерским“ toolset.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* This Sample just shows that a Certified Journalism promote and advertise to spread of dual-purpose Software toolsets.
* In normal lawful Countries these toolsets are banned, unless the User has proper competencies and is employed to use toolsets like shown in the Image.
* The event like this does not differ from storing and spreading unknown Software products in open repositories for catching (fishing) out "kiddies" to step on the Rake.    
```

```
##### I ncident

In this Article [ELTA](https://www.lrt.lt/naujienos/eismas/7/2014006/jonavoje-uzfiksuotas-rekordinis-pazeidejas-mieste-leke-173-km-val-greiciu) is displayed way to avoid security instrument.
```

```
##### R esults
No information about damage done.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*   12th section in the Ethical Rules of participation in Traffic reminds to [Lrs.lt](https://e-seimas.lrs.lt/portal/legalAct/lt/TAD/TAIS.203613/asr) waste Your accumulator Power from a beginning of Journey till an end.
```

```
##### I ncident

In these Articles [BNS](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2022644/sutriko-vyriausybes-elektroniniu-valdzios-vartu-tinklalapiu-veikla), [LRT.lt](https://www.lrt.lt/ru/novosti/17/2022652/proizoshel-massovyi-sboi-v-rabote-veb-saitov-pravitel-stva-i-elektronnykh-uslug) is provided Report that Certain Firewall Malfunction lead into several Services, which were not Available for e.Citizens.
```

```
##### R esults
Loss of Availablity to get e.Services.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*   There could be given Question for an Owners of their e.Service: What, if there is Requirement for e.Citizen to Access and View & Read & Sign some Very Important Document? and the Document has to be Available up to limited Amount of Time Only. I.e. Somebody could DDOS his opponents for Winning the Bet on the Auction...
*   Common Firmware or Software update could lead into Misconfiguration and Not Available e.Service. If there are Available Warm Site, which has spare Equipment to test out these Updates & Upgrades, then You are happy Administrator of a System.
*   Security Instruments could be affected and not working, i.e. Sending Data from Speed limit Cameras to an e.Citizen, if they not Rotated into wrong Side by a Third Party.
```

```
##### I ncident

In this Article [BNS](https://www.lrt.lt/naujienos/eismas/7/2023289/vilniuje-sutriko-m-ticket-ir-m-parking-programeliu-veikla) given explanation that Apps for the Public Transport in the Capital is not in Working Condition.
```

```
##### R esults
Payment for the Public Service is not Available from e.Service App.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*   Exists chance that not working e.Service App could be related with not working e.Service Devices within the same Public Transport.
*   Usual approach for creating another Module of the System or Subsystem is to keep remaining System Components intact and not affected by Failing Component.
*   Application Architecture from the beginning could have limited amount of possibilities and staying with only e.Service Solution like that could be costly in a long run, i.e. Free Ride with the Public Transport. 
```

```
##### I ncident

In this Article [BNS](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2025590/seimo-kanceliarija-aiskinasi-kodel-interneto-svetainese-matyti-asmens-duomenys) provide idea that finding non-public documents in public internet is Not related with CyberSecurity in any way. Information of Public Persons, like Home Address, Date of Birthday, Phone No. and more were indexed by common Search Engines. 
```

```
##### R esults
Loss of Authentication. Human-Error in public data leak.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*   Search Engine Hacks were known from the early days of Search Engine(s). Web Site Security could use ISO/IEC 27001 approach and to take Information Security, Cybersecurity, Privacy. Each of these Terms is at the same Level and important.
*   If Web Site has number of Authentication Levels (i.e. public Site, Authenticated Site) then Web Administrator could get proper organizational requests, that explains on which Level the Job has to be done.
*   If there were no extra Job, then the Audit Logs could answer to the Question: what happened? unless the Security incident happen which lead into loss of Integrity and Authenticity of Journaling Data Logs.  
*   General Data protection Reglament only works in Private Sector. For Public Sector it would need to look into the local Regulations and to Report the Issue.
*   Plausibility, that Common Automated Security tools can't tell, which information could be Public and which - Not. OpenAI Bot allow to Set Up Your Learning Data, then it could be good to find out the problem, which were given in the previous Sentence.
```

```
##### I ncident

In this Article [-](https://www.lrt.lt/naujienos/lietuvoje/2/2030905/pries-nato-susitikima-kibernetiniai-ispuoliai-radijuje-ir-prekybos-centre-skambejo-propagandines-zinutes) shown Cybersecurity breaches to IT System of the Shopping Center and Radio Broadcast Station. DDOS attacks against m.Ticket and govilnius.lt
```

```
##### R esults
Not clear enough.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  No comments. 
```

```
##### I ncident

In this Article [-](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2041252/ekspertai-ispeja-socialiniuose-tinkluose-zaibiskai-plinta-netikros-nuorodos-kuriose-tyko-programisiai) shown that People are getting links to forged Sites, which mean to steal Personal Information. 
```

```
##### R esults
Not clear enough.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*   If these Companies are going with Two-factor Authentication, then there are huge Risk, that they gonna keep more Personal Information about You, Me and everyone. Giving out more Personal Information (Factors) could mean that upon loss of this Data exists chance that somebody could pretend as You, Me or everyone to get some Goods and Services.
*   Going Two-Factor Authentication without Security Options per Factor-basis? Indifferent look to brute-force Logins for possible Account Breaches is pretty the same as no Authentication. It means that Site lacks for Security Option(s) which prohibit unlimited and non-successful Logins.
*   Sight from User Perspective, which are using some Service. If Service are permitting for the User to break the Service, then how good is the Security Stance of the Service. White Hats only working as Sample of this Site [vilnius.lt](https://vilnius.lt/lt/vilnius-2in/kibernetinis-saugumas/), which require Registration for the Privilege to do so. In regular and common Small and Medium Service there is not enough Documentation for the User what are prohibited and what are not. Read the Terms and Conditions, of course, if it even exists.
```

```
##### I ncident

In this Article [-](https://www.lrt.lt/mediateka/irasas/2000287767/saugumo-ekspertai-nato-virsuniu-susitikimas-lietuva-paverte-kibernetiniu-ataku-taikiniu) shown a number of Short Messaging which contain non-safe URL's. 
```

```
##### R esults
Not clear enough.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*   The Article provide Fact "Telecomunication Company has never SMS of their Users". If Telecomunication Company don't do that, then in addition they have to not give Access to anybody else? because an Assets of a Person(s) is Untouchable. Illegal Orders may be the Problem for some kind of Jurisdictions.
*   The Article provide Fact that Internet Service Providers gonna block URL's, which are in Forbidden List. In this Regard, if You install Modern Anti-Virus & Anti-MalWare Software in the Computer System, then You get something similar. Multiple Modern Anti-Virus & Anti-MalWare Software Installations could be a Latency for Comfortable Usability of Your Goodies.
```

```
##### I ncident

In this Article [-](https://www.lrt.lt/naujienos/verslas/4/2054761/gyventojus-toliau-persekioja-sukciu-zinutes-ragina-susimoketi-administracine-bauda-ir-taip-bando-isvilioti-pinigu) shown Threat from SMS and QR codes, which could hold non-safe URL. 
```

```
##### R esults
Not clear enough.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*   Obfuscated QR code could hold any kind of Information and Thanks for the Software, which before going to the URL give a chance to Identify an URL. Some Sites may hold a lot of Variables in their URL's, which could mean a problem for regular User during URL Identification from a Bad Patterns.  
```

```
##### I ncident

In this Article [-](https://www.lrt.lt/naujienos/verslas/4/2058247/lietuvoje-plinta-pavojingos-sukciavimo-schemos-vmi-imituojanciuose-laiskuose-net-teisingi-asmens-kodai) shown a problem that somebody pretend to be from a official VMI Team. More advanced phishing, which contain Personal Identification Information. 
```

```
##### R esults
Not clear enough.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*   By digesting the Article the previous Data Leaks could mean that Person may lose Safety of this type of Factor for the Eternity. More advanced loss, if there could be somebody with natural|unatural similar Biometrics Data. At least the Automobile Industry don't permit to start the Automobile with Dead Tissues & Skin.
```

```
##### I ncident

In these Articles [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2068851/isnaudojant-vieno-svetainiu-gamintojo-pazeidziamuma-buvo-isilauzta-i-mazdaug-10-lietuvos-interneto-svetainiu) and [-](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2068881/piktavaliai-isilauze-i-visuotine-lietuviu-enciklopedija) are known about breaching websites: poliklinika.lt, radviliskis.lt, ukmerge.lt, siauliai-airport.com, kalvarija.lt, sc.joniskis.lm.lt, jpm.lt. Provided Statement that all of those websites who has a flaw and are created by a single Company.
```

```
##### R esults
All Content were Deleted.
Included Defacement Site Code, which explain the Aim of the Breach.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*   There exist no proof that the Single Company created all of those websites (excluding kalvarija.lt and radviliskis.lt Sites, which probably are their Customers).
*   Providing a guess that the Single Company has created these Websites gives a Hint, that maybe Code of those Websites are the same and (or) has similarities. Knowledge of some Unknown Flaw and Vulnerability in the Code provide a Hint, that as more You Copy and Paste the same Tech to the Web Server, there will be more Site breaches, if someone would use this Flaw and Vulnerability in Practice. From First Sight It looks unlawful and without consent from those Owner(s) Perspective.
*   Term and Definition of the Defacement could be used as following "A Defacement is considered in all Countries an unauthorized Computer Access, a Denial of Service Action therefore a Crime under all Means. The Activity of defacing to Warn the Administrator of a buggy Server about Its Vulnerable Status is considered a Crime too and a questionable Ethical Conduct."
*   Defacement Message(s) does not include explanations about used Terms like usual.
```

```
##### I ncident

In this Article [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2101098/kaip-elgiasi-grasinamuosius-laiskus-gavusios-mokyklos-kvietesi-saugos-bendrove-policija-vaikus-vede-i-parkus-uzluzo-tamo) provided Information about Local DDOS of the Educational Web Site.
```

```
##### R esults
Local Infrastructure for the Education can't keep up and can't be used at the Moment.
Electronic Service Users can't get their Service.  
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*   IT Subjects with Technical Practice and Laboratory Works using Software and Hardware are Irregular (when the Education Web Site is not Available). IT Infrastructure of the Web Site lacks more Powerful Security Stack Servers.
```

```
##### I ncident

In this Article [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2103946/naujos-sukciu-pinkles-siuncia-nuorodas-su-neva-gautos-baudos-informacija) provided Situation of a Phishing Attack.
```

```
##### R esults
People could be fooled from the non-legal Entity.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  Fines in usual Way could be received only from Official Sites, i.e. [epolicija.lt](https://www.epolicija.lt/). Lack of Awareness Training and Knowledge about Official Sites for what Reason they are used for - one of the Main Problems.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2137256/vilnietis-pastebejo-internete-plitusia-netikra-lidl-parduotuve-siule-net-90-proc-siekusias-nuolaidas) exists Phishing Site. 
```

```
##### R esults
Original owners who were being phished have been Informed.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  Does big percentage exists that the Design of this Phishing Site could be the same and (or) similar to other non-Phishing Site(s)? The only distinction in this Situation could be and is a Logo & favicon. The Republic of Lithuania Site of [lrv.lt](https://vpb.lrv.lt/en/) could help to get Patent in the Trademark and (or) the Design at the Local Level.
*  If there is required registrations in the Higher Level, then the Republic of Lithuania Site [lrv.lt](https://vpb.lrv.lt/en/structure-and-contacts-1/links) could be taken in the Account.
*  In the early Web most of the Web Sites were incliding Logo(s) for compitability with HTML, XML Standards. And nowadays an Enterprises does not show the Lead into securely linking something as simple as Logo and favicon from secure Blockchain Database.
*  According Phishing Site(s) Database Phishing Site(s) also could be blocked thanks to Cybersecurity Tool(s).
```

```
##### I ncident

According these Articles [1](https://www.lrt.lt/naujienos/verslas/4/2146938/vilniaus-rajono-savivaldybeje-po-atakos-veluos-ismokos-uz-duomenis-paprasyta-ispirkos), [2](https://www.lrt.lt/naujienos/lietuvoje/2/2143973/vilniaus-rajono-savivaldybe-patyre-kibernetine-ataka-tiriama-ar-nenutekejo-asmens-duomenys), [3](https://www.lrt.lt/naujienos/lietuvoje/2/2145847/nksc-nusikalteliai-uzsifravo-vilniaus-rajono-savivaldybes-duomenis-atsargines-kopijas), [4](https://www.lrt.lt/naujienos/lietuvoje/2/2146784/po-kibernetines-atakos-ktu-kreipsis-i-policija), [5](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2153835/per-kibernetine-ataka-nutekinti-ktu-duomenys-pardavin%C4%97jami-tamsiame-internete) Information Systems and their Backups of the Vilnius Municipality of the Region has got an Ransomware attack. Data leak from the Higher Education School.
More sources:
* [BNS](https://m.kauno.diena.lt/naujienos/vilnius/miesto-pulsas/del-nutekintu-gyventoju-duomenu-9-tukst-euru-bauda-vilniaus-rajono-savivaldybei-1196526)
```

```
##### R esults
Interruption of Service(s) of the Vilnius Municipality of the Region.
Limited Access to still available Information System(s).
Moderate chance of the loss of a Digital Data.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  According 1st article the Vilnius Municipality of the Region got Notice to Pay for Encrypted Data. This is typical Ransomware attack. There is High chance that (1) these Entities not even done attack and are Scammers (2) According International Agreement Republic of Lithuania do not pay for any entities who commit crimes. The Hostage in this sample is a Data for which release none gonna pay.
*  According 16th paragraph of 1st Article Vilnius Municipality of the Region has not registered any of their Information Systems in the Register. In this Way none even know what kind of data they collect, keep & process. On the Table is a data at the beginning of commoners who may be exploited by these Cyber-criminals even further.
*  The Police (4) require advanced knowledge for successfully completing research of the incident & probable data leak. 
*  Giving a chance to remove and backup (Emploees) Data for the Employees could limit conequences of an Ransomware attack.
*  Having security Representative to teach Employees how to keep security Policies and Regulations in the Institution could boost efectiveness of an Incident Management in the Institution.
*  The (5) available information about a possible loss of: i. First name, ii. Last name, iii. Personal identification number, iv. Personal (household) address, v. phone no., vi. email address, vii. personal automobile license plate w/o VIN number.
*  The (5) available information hint that end-user(s) employee workspace could be the place where the data could be leaked.
*  An enumeration of all plausible data and backup data places could help to a Security Representative of the Company to conduct precise a risk assessment and afterwards - treatment process.
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2145656/ktu-skelbia-patyres-kibernetine-ataka) can't be accessed the Web Site, E-mail, University Services for One University in the Republic of Lithuania. 
```

```
##### R esults
Interruption of Services.
Clients can't access their Curriculum.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  Inter-communicating Computer Related Incidents is a initial move into Common Vulnerabilities and Exposures (abbr. CVE) System Type. It requires to meet Requirements and Competencies. Sample registration form for CVE.org Partners: [cve.org](https://www.cve.org/PartnerInformation/Partner).
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2149826/teismas-paliko-2-2-tukst-euru-bauda-portalui-musu-tv-uz-dezinformacijos-platinima) internet TV station „Mūsų TV“ spreading worse than misinformation data - disinformation.
```

```
##### R esults
(In the web) tv station has spreaded propaganda & disinformation.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  TV station „Mūsų TV“ provide public service. In example exist e.Service who is not a public service like Protonmail who has statement "private email service that uses end-to-end encryption and zero-access encryption to protect your communications". The difference between public and private service is that for the private service(s) are required to complete these procedures: Identification > Authentication > Authorization. Best example of similar private service(s) - Youtube "social media" platform. Of course exists Apps who uses their own Business Account to re-stream the service content.
*  According provided jurisdictional document the disinformation means that this misinformation information are speaded deliberately. This could mean that subject did that on the purpose. The Jurisdictional Act also provide a lot ties with the Lithuanian Republic and it's Independence & Sovereignty. 
*  Exists and could exists news aggregators who include similar misinformation and disinformation related content to their news with one exception. This exception is the rule to place correct label to it. This has a lot of similarities for smookers who get to purchase cigarettes with horrible labels and glued Truths to it. It seems that e-cigarette(s) does not include this requirement.
*  The news content is related with "full-scale invasion" [hrw.org](https://www.hrw.org/tag/russia-ukraine-war). Does media & news aggregators referencing this organization and use their content, i.e. contacts [hrw.org](https://www.hrw.org/about/get-local/paris)? 
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2150651/telia-pradejo-blokuoti-padirbtus-mobiliojo-rysio-numerius-kiti-operatoriai-ruosiasi) telecommunication companies are getting trouble with the fake phone numbers who could fool legit people. 
```

```
##### R esults
Without countermeasures people could be easily fooled.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  The scammers getting their hands on advanced technologies for making damage to the civilians and people. This approach could be similar sample as post'ing dangerious operating system's and smaller application's arount the web.
*  Does phone calls are not secure anymore? lack of technological improvement, creating services without security and secure design.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2150246/specialistai-ispeja-lietuvoje-plinta-antivirusine-sistema-apsimetanti-kibernetine-ataka) there are spreading not true & false antivirus system pop-ups about infection of the device. Provided chance to call for the (free) "helpdesk". 
```

```
##### R esults
The Web and plausibly non-web Phishing Messages.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  According this Article You have to not open pop-ups at all.
*  Anti-Security related code(s) are called as "malware".
```

```
##### I ncident

According this Article [valstietis.lt](https://www.valstietis.lt/salyje/paspaudus-nuoroda-prarado-tukstancius/130683) citizen got SMS message with a link. After clicking this link the citizen has lost money. 
```

```
##### R esults
One fraudlent SMS.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  Telecommunication companies provide (e)service registration with "public" shortcut letter(s) for activating e.service. They also provide cost limits per duration of date & time.
*  Smartphone could use Internet (e)service(s) who could be culprit of any type of phishing attack.
*  The Bank Companies offer Finance Applications to their clients. The Smartphone over this App could directly linked with client User private & personal Bank Account. Identification, Authentication and Authorization mechanism protect client, so that this client could use his Account securely and privately.   
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/ru/novosti/17/2151386/assotsiatsiia-bankov-litvy-preduprezhdaet-o-moshennikakh-v-telegram-zhiteliam-predlagaiut-bystro-razbogatet) scammers are sending messages in the Social Media.
```

```
##### R esults
Social Media Users get Phishing Messages (via Web and via App).
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  There could be found information about fraud-phishing type social engineering attacks [www.lb.lt](https://www.lb.lt/lt/sukciavimas).
*  In the Article there are no reference to non-licensed investment services or vica versa.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/eismas/7/2149778/netikru-regitros-tarpininku-viliones-ir-pazadai-uz-1-tukst-euru-mes-viska-sutvarkome-uz-jus-jums-niekur-dalyvauti-nereikia) scammers offer precise driver license(s) online.
```

```
##### R esults
Plausible loss of an private information.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  The person who use(s) service(s) like this can't be sure where the personal home address, phone number, personal picture of the face are going off.
*  Plausible service administration tax avoidance. Plausible chance that an Information system has issues with confirmation of a payment status(es).
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2160007/atskleista-placiai-paplitusios-sukciavimo-atakos-baltijos-salyse-maskuotes-schema-leidusi-nusikalteliams-isvengti-blokavimo) a social media clients get phishing link offers from other social media users. Those phishing link information are directly not related to a sender landing page(s).
```

```
##### R esults
Plausible to lose personal information, Tax avoidance, getting thrown into active Virus & Malware distribution point.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Usually internet service provider enforce DNS security what could help & reduce getting thrown into fake site.
* Usually hosting service provider create Site(s) for their Clients. For creating those Site(s) is required to register and provide personal information. Exists free Site service(s) who has in-build advertising functionality. A dinamic Banner and an ad's distributor(s) security could effect security of a client who use those Site(s).
* It's required to properly configure social media Account and to block unwanted audience and (or) per person-basis accounts. I.e. The Youtube allow to block influencer(s). Even service like this does not offer to block content per non-desired tags. How are sensitive a tag data per individual?
* Do You every time need to include new service to the social media account? limiting amount of services could limit spam and plausible security risks.
```

```
### 2024

##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2168751/plinta-naujas-sukciavimo-budas-siulo-uzsidirbti-ziurint-youtube-vaizdo-irasus) people are phished into work offer. Before getting the offer person has to pay registration bill. In the Fraud scheme could be included chat using "Telegram" social media. After Victims payment this person gonna be simply blocked, removed. 
```

```
##### R esults
Malicious work offer for only using Your electronic device could seduce, i.e. unemployed people. 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  When there are news about increasing unemployment rate the "fake work offers" could increase.
*  Lack of common sense and striving to get new job could be a factor to get Yourself on the fake "offer".
*  Look for official and registered entities in Your Country.
*  Social media Accounts could be used for fraudlent & malicious purposes.

##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2168843/pranesta-kad-is-aiva-sistemos-duomenu-bazes-nutekinti-260-tukst-klientu-duomenys-imone-tai-vadina-zmeiztu) there was database leak in an "Aiva Sistema"(-os).

```

```
##### R esults
Private data leak of the Service or Reputation attack to the Service owners.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* The r/n of the company by taking in the Account this Article - "120124533". From row of similar company name's there could be not clear for the client(s) whose they really are (was) registered for that exact company.
* Adequate relations between clients and service managers/owners could include mindfully correct way how to respond to an incident.
* There could be taken notice - does informing everyone are right way to do? When after at least one data leak the same data could be shared infinity time, including first name, last name, phone number, email address.
* Services could have first inbound data-number and different outbound data-number.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/eismas/7/2167681/zadejo-patoguma-o-gavo-baime-likti-nubausti-vilnieciai-piktinasi-neveikianciais-komposteriais-viesajame-transporte) electronic payment system is not working as expected.
```

```
##### R esults
Availability of the service to the citizens could be in question.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Distributed system could help to collect data even when the availability to the internet is scarse.
* Information exchanged between the electronic device and the service center needs to be protected with encryption and decryption, encoding and decoding, integrity s, stamps and signatures. When this mechanism has to be updated, then the service could be tested in a testing environment before an original update commense.
* The calculations in digits for the common user-citizen and cheapest option in a life-cycle is not taken in an account.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2170834/isilauzta-i-mamu-unijos-fondo-paskyra-socialiniame-tinkle) social media account of the charity and donation fund was overtaken by unknown entity(-ies).
```

```
##### R esults
Information in the social media account could not be trusted. 
Next phase of phishing attacks to the subscribers of this media account are plausible.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Read Terms of Use & Privacy Policy to understand what possibilities provide the social media account.
* Providing your personal identity card to foreign service are the same as bank person would request You for passwords to Your account. Recommendation to not do that.
* Other e.Services requests for Employee data, i.e. Linkedin. Employee card could be used in this place. Recommendation to not do that.
* The use of the qualified digital signature are not wide-spread. The digital signature by himself could include private information like personal identity code, home address & major of applications does not ask: what are required at minimum & what You are willing to share. Recommendation to not use for the social media accounts.
* Exists charity platforms who collect similar sponsorship & donation funds, so better use official & registered platforms instead. When the platform registered locally, then You could get better customer service.
* The social media shown in the Article use Content Security Policy, so it provide security & are prone to phishing Sites. When You use non-standard browser this could be not true.

```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2177858/vel-sutriko-smart-id-veikla..) there was interruptions for full half hour in a qualified electronic signature service "Smart-ID".
```

```
##### R esults
Customers could not use their internet services, i.e. online banking.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* When service does not support Smart-ID, then user could choose other method either electronically ID-card, either electronically Mobile-ID, biometric data, visiting in person with official identity document(s). 
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/kultura/12/2179034/uz-piratavima-internete-nubausti-dar-astuoni-zmones) several people shared copyright protected work(s).
```

```
##### R esults
Copyright protected work(s) distributed without paying a penny to an original authors.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* The Bank purchase services are not widely spread & people can't pay with their desired existing online banking method. e-ID payments could exist [ecb.europa.eu](https://www.ecb.europa.eu/paym/integration/retail/retail_payments_strategy/shared/pdf/20220329-European_Fintech_Payments_Dialogue_Summary_Note.en.pdf)
* The payments for copyrighted work can't be payed directly & easily to the author. Third party services are used for this Task.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2179103/kai-mesainio-kaina-per-gera-kad-butu-teisinga-mcdonald-s-perspeja-apie-internete-siauciancius-sukciu) with no relation to the official service scammer(s) suggest food and gift(s) as a service.
```

```
##### R esults
Plausible loss of money and loss of personal information.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Via Article Service provide remind an official & a trusted & an allowed way(s) how to pay for the good(s) and service(s). 
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2193161/bendrove-ignitis-patyre-programisiu-ataka) e.service (Software as a service) of the company "Ignitis" was breached by a successful cyberattack.
```

```
##### R esults
Twenty thousand client's data were lost. This include data as a First Name, a Last Name, an E-mail address, a RFID data, a license plate number of an electromobile.
After cyberattack electromobile charging was unavailable & clients could not use their e.service.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* In a situation when e.service's (i.e. Software as a service) could be a service, which operates from other jurisdiction there could be issues to local security staff to defend local Rights for example to get a Compensation for a Client's. When e.service exists in the same economic zone, then there could be enough of safeguards in place to solve case like this.
* Company representative suggested for the client's to change their password's of the e.service.
* In a situation of existance of unclonable RFID-tag's electromobile could be directly connected with a Tag. If this could be electromobile sharing service who depend by data in online database, then in a worst case of situation those electromobile's could be snached. There are nothing new by opening... the car with a Tag. Yet, mostly known that the mobile phone could be used instead of a Tag & this probably would be a different situation.
* How this service were breached are given no information in the Article. Using advanced Captcha technologies for authentication security could minimize Authentication related breaches.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2194650/programisiai-bande-isilauzti-i-lietuvos-kariuomenes-sistemas-pradetas-tyrimas) Lithuanian Army System were breached.
```

```
##### R esults
Clients can't get their services from three telecommunication servers.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Article provide statement "Data were not leaked...". Nowadays when people could purchase services online whose could be located in other jurisdiction the VPN service could fool anyone about their whereabouts. The Article already provide opinion who is cluprit when the complete results are Unknown.
* The Investigative Journalism - United Nations - Office on Drugs and Crime [unodc.org](https://www.unodc.org/documents/commissions/CCPCJ/CCPCJ_Sessions/CCPCJ_32/ISM_TD_Kyoto/Statements/UNODC_3_Spotlight_-_AC_and_journalism.pdf).
```

```
##### I ncident

According those Articles [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2198431/policija-siemet-fiksuoja-sukciavimo-buma-pradeta-per-500-ikiteisminiu-tyrimu) [J.B.](https://www.lrt.lt/naujienos/verslo-pozicija/692/2194372/justina-bagdanaviciute-atsidure-romantiniu-sukciu-spastuose-gyventojai-neteko-300-tukst-euru) inreased amount of (investing & romantic) (SMS & e-mail) scam attacks by 33 percent.
```

```
##### R esults
Loss of money 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* It's necessary to take in consideration that Advertisement are used by scammer(s) too. This is true for scammer(s) from this(ose) country(-ies) whose people admire and donate their savings.
* National Cyber Security Center (NCSC) own nice Tool [nksc.lt](https://www.nksc.lt/tikrinti.html). This IP er provide information about Computer Activity in TCP/IP Computer Network. I.e. this Computer IP Address not registered in "NKSC/CERT-LT" Database for full 30 day period. When Mobile phone(s) are important in daily social life, then why does the Police don't open possibility to test out Fixed & Mobile phone addresses for being in a "Database"? When Person really want to call it back, then at least he could  that phone number (not)exists in a common "Database" for number of cases.  
```

```
##### I ncident

According those Articles [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2207021/finansu-konsultantu-apsimetes-vyras-is-senjores-isviliojo-daugiau-nei-19-tukst-euru) and [Lrt.lt](https://www.lrt.lt/ru/novosti/17/2207098/moshennik-vymanil-u-pozhiloi-zhenshchiny-bolee-19-000-evro) single pensioneer lost 19.200 EU (Nineteen thousand two hundred Euros).
```

```
##### R esults
Person lost money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Digital competency are in decline. Even regular Article does not provide information how physically person could come to pensioneer and grab his money from Bank Account. (i) Does pensioneer provided full information, full access, password(s), identification documents? (ii) This more looks like grab of pension for which pensioneer does not have any decision.
* Second Article include knowledge of 19000 = 19200 EU. Digital competencies also related with knowledge of calculus.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2215264/sukciu-pinkles-internetineje-investavimo-platformoje-klaipedietis-prarado-daugiau-kaip-51-tukst-euru) in Cyberspace exists possibilities to lose Money and one of those Threats is a Investment Fraud. 
```

```
##### R esults
Person plausibly lost a huge sum of Money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Internet is meant for the Internet e.Payments. When Person want to stop participating in unknown gambling activities, then this Person has to take in an account plausibility that this(-ose) internet sites could deny his request for gambling, ref. [epaslaugos.lt](https://www.epaslaugos.lt/portal/service/74420/13221?searchId=dc364005-8bed-4487-b267-56e67ed3d504).
* When Person want to make Money Investment, then awareness of selecting right place are very important. Ref. [lb.lt](https://www.lb.lt/lt/investavimas-kaip-atpazinti-sukcius#ex-1-2).
* At the previous reference domain are plausible to locate illegal and forbbiden investment internet sites. DNSSEC widespread use could enforce protective means when this tool are in use [nksc.lt](https://www.nksc.lt/uzkarda.html) and protection - full automatic.
* Your computer - smartphone connection don't have DNSSEC support? Public and Private Key Cryptography Key Management usually are made by telecommunication companies and they provide list of DNS services, which Client could use. Registration for personal DNSSEC keys could help and improve the situation or usual approach - use Anti-Virus Software with this type of service. Anyway, common non-Browser Software Product could just not use this tech, then awareness of Software Product(s) plausibilities also are needed.   
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/eismas/7/2215274/vilniuje-pasisavintas-40-tukst-euru-vertes-automobilis-pasinaudojo-mobiliaja-programele-ir-kito-zmogaus-duomenimis) mobile program could provide fake data to the service and open + start the Car - Vehicle. 
```

```
##### R esults
Loss of Asset.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* In automobile sharing company [citybee.lt](https://citybee.lt/lt/transportas/) are plausible to rent the Car - Vehicle, which are described in the Article. Snaching the Car - Vehicle with other Person's data is not a common incident. This could lead into unknown & negative consequences for the business.
* Smart Home, Smart Automobile industry has measures that with mobile phone, smart card You could open Doors. Safety and Emission Recalls shown in here [bmwusa.com](https://www.bmwusa.com/safety-and-emission-recalls.html). This include Software and Hardware issues. Taking care of Your own Asset just could go as priority no. One. p.s. Site Search in [bmw.com](https://www.bmw.com/en/search.html#recall) for Recall provide only "Fictional" Results.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2215652/kaip-ir-kokie-tamo-duomenys-buvo-nutekinti-vogta-is-vartotoju-kompiuteriu-ispeja-del-galimo-pavojaus) TAMO e.service users are constantly attacked by malicious entities who want to get data from this Site & their Users. Statement: Probable data collection activity from a long long past. Service users are compromising e.service by themselves, so probably they need to refresh some Knowledge of Cybersecurity.
```

```
##### R esults
e.Service users compromising their own e.Service Accounts.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Malicious mirrored service could be a culprit of this incident for collecting credentials from e.service users.
* With TAMO related supply-chain site(s) could be used as malware distribution point(s). The NIS2 E.U. Directive should require to scan & handle own root directory of e.services like TAMO for any harmful computer viruses and malware. 3rd-party external components could be left unchecked.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2216193/klaipedoje-kito-zmogaus-vardu-prisistates-asmuo-paeme-18-3-tukst-euru-kredita) somebody could take credit and cash thanks to a stolen data. And (or) person could fake his wish to take the credit and cash.
```

```
##### R esults
Credit and cash was stolen or not.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Jurisdiction document for those credit's [infolex.lt](https://www.infolex.lt/ta/142009#).
* Licensor of credit and cash givers in here: [lb.lt](https://www.lb.lt/en/faq).
* Does mobile phone is enough to take this cash and credit? has person used qualified signature, mobile-ID...there is just no idea.
* Does person were delegated from original requestor? Some plausibility could be found in here for business and common entities [epaslaugos.lt](https://www.epaslaugos.lt/portal/).
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2220791/sostineje-sukciai-is-moters-isviliojo-beveik-10-tukst-euru) a Person has clicked on the email link and filled all e.banking data. After this action this Person lost personal belonging money. 
```

```
##### R esults
Person could get scammed by unknown entity(-ies).
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Minimum requirement to start doing actions in the online banking requires [barclaycard.co.uk](https://www.barclaycard.co.uk/content/dam/barclaycard/documents/business/help-and-support/Authentication-card.pdf) knowing PIN (what You known) and having PIN Sentry Card Device (what you have). From the Article there is no way to know what option(s) to authenticate itself to an e.banking institution this Person had & has.
* The problem could be related with non-legal investment. Person(s) could build awareness using following source from the Lithuanian Bank: [lb.lt](https://www.lb.lt/lt/sukciavimas).
* IP address to hostname conversion service could be at fault, fake Site could be build by the scammer who just look like a original Site. In this case Banking institution require to own e.banking site with good and proper defences, i.e.  [lb.lt](https://www.lb.lt) has Header Security Rules "frame-ancestors 'self' monetos.lb.lt coins.lb.lt *.cv.lt *.cvonline.lt;". This data clearly provide data to the modern Browser App(s) and answer the serious questions: what are allowed and what aren't allowed?
```

```
##### I ncident

By taking in Account this Article [BNS](https://www.lrt.lt/naujienos/verslas/4/2229489/krepsta-puse-kriptobendroviu-turi-fiktyviu-imoniu-pozymiu) in Lithuania has been registered no less than 580 with Cryptocurrency related Entities.
```

```
##### R esults
Huge chance of lack of transparency and money laundering issues.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* According Department of the Treasury (U.S.A.) to the digital currency is possible to add a "sovereign cryptocurrency" [treasury.gov](https://ofac.treasury.gov/faqs/topic/1626).
* According Department of the Treasury (U.S.A.) to the digital currency is possible to add a "virtual currency" or the currency which is neither issued nor guaranteed by any jurisdiction. [treasury.gov](https://ofac.treasury.gov/faqs/topic/1626).
* In Republic of Lithuania from previous view points there are huge shortage of experts who could solve legal issues of Cryptocurrency and to protect the public interest. Uncontrolled Cryptocurrency could mean only huge gap in financial literacy when regular "Paypal" Accounts are "monitored" [vmi.lt](https://www.vmi.lt/evmi/pagrindinis?p_p_id=com_liferay_portal_search_web_portlet_SearchPortlet&p_p_lifecycle=0&p_p_state=maximized&p_p_mode=view&_com_liferay_portal_search_web_portlet_SearchPortlet_mvcPath=%2Fview_content.jsp&_com_liferay_portal_search_web_portlet_SearchPortlet_redirect=https%3A%2F%2Fwww.vmi.lt%2Fevmi%2Fpagrindinis%3Fp_p_id%3Dcom_liferay_portal_search_web_portlet_SearchPortlet%26p_p_lifecycle%3D0%26p_p_state%3Dmaximized%26p_p_mode%3Dview%26_com_liferay_portal_search_web_portlet_SearchPortlet_redirect%3Dhttps%253A%252F%252Fwww.vmi.lt%252Fevmi%252Fpagrindinis%253Fp_p_id%253Dcom_liferay_portal_search_web_portlet_SearchPortlet%2526p_p_lifecycle%253D0%2526p_p_state%253Dnormal%2526p_p_mode%253Dview%26_com_liferay_portal_search_web_portlet_SearchPortlet_mvcPath%3D%252Fsearch.jsp%26_com_liferay_portal_search_web_portlet_SearchPortlet_keywords%3DPaypal%26_com_liferay_portal_search_web_portlet_SearchPortlet_formDate%3D1710941103070%26_com_liferay_portal_search_web_portlet_SearchPortlet_scope%3Dthis-site&_com_liferay_portal_search_web_portlet_SearchPortlet_assetEntryId=793543&_com_liferay_portal_search_web_portlet_SearchPortlet_type=content&inheritRedirect=true).
```

```
##### I ncident

By opening the link [lrv.lt](https://zum.lrv.lt/lt/naujienos/kailiniu-zvereliu-laikytojams-laikinoji-valstybes-pagalba-1/) response with error code. At this time the original Location of the link is here [lrv.lt](https://koronastop.lrv.lt/lt/naujienos?page=112).
By opening the link [lrv.lt](https://sam.lrv.lt/lt/naujienos/seimas-pritare-patobulintam-asmenines-apsaugos-priemoniu-rezervo-kaupimo-modeliui) response with error code. At this time the original Location of the link is here [lrv.lt](https://koronastop.lrv.lt/lt/naujienos?page=114).
By taking in Account whole Web Portal [lrv.lt](https://koronastop.lrv.lt/lt/) there is provided no information about responsible coordinated disclosure of the Web Site and their App(s).
```

```
##### R esults
People can't coordinate their responsible disclosure with current Site or official Site of [lrv.lt](https://lrv.lt/).
News Pages are providing in random fashion wrong (re-)directions. People can't get the el. service for what they are comming here. 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* In technological way second level domains does not communicate with each other when the whole Web Software for first level domain is with the same Framework. When one content admin make changes in his second level domain news page as the result an other content admin who used his link does not get any notification(s). The whole purpose of using second level domains with unified framework have to solve communication issues as described above. One contant admin feels at ease when he manage his own Site, no accountability of his to other content admin(s). Regular way to solve this issue — collecting all page modifications (history) at one place and providing unified button to open latest version of a page. This way there could be less problems with interlinking between different sites. Usualy content has limited time to exist and to solve this issue this(these) page(s) could provide information for how long the information are relevant. When using framework probably easies way would be to cache or scrap the content into own database, so content admin(s) could be at ease.
* This Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/1389617/beveik-30-tukst-euru-ir-nepasiteisinusi-pandemijos-suvaldymo-priemone-kas-nutiko-su-korona-stop-programele) give idea that exist(s) "Korona STOP" Software Application. This Article [Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1354688/uz-bdar-pazeidimus-programeleje-karantinas-bauda-nvsc-ir-jos-kurejams) give idea that exist(s) "Karantinas" Software Application. From personal experience — exists "Web Site(s)" for registration, so in general there exists number of solutions for the main purpose to make registration and grab the personal data. (a) Who's trusted and who's not? (b) What will be done with the data, which people has to enter into the software application(s) and web site(s)? (c) How the data will be handled? (d) Does all sites and software apps use one registrar and take data from that location? (e) Does all of those entities has legit privileges to do so?
* When the landscape of software are not in place, then ennumeration of faulty software not easy to grasp.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2230404/valstybiniu-instituciju-svetainiu-veikla-atstatyta-dar-neveikia-prezidenturos-tinklalapis) several public sector sites were not available. 
```

```
##### R esults
Citizens, officials, public servants could not access their e.service for 3 hours and 20 minutes.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Referencing information from [Copilot](https://copilot.microsoft.com/): Achieving high availability involves minimizing downtime. Here’s a glimpse of maximum allowed downtime based on availability percentage: 99% availability: Up to 3.65 days per year. 99.9% availability: Up to 8.77 hours per year. 99.99% availability: Up to 52.60 minutes per year. 99.999% availability: Up to 5.26 minutes per year. 99.9999% availability: Up to 31.56 seconds per year. 99.99999% availability: Up to 3.16 seconds per year. 99.999999% availability: Up to 315.58 milliseconds per year.
* When there exists no availability percentage in a contract, then hosting service is not accountable for incidents like this. Of course, there could be a whole book of responsibilities and consequences.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2230828/muitine-sutrikusi-e-sistema-buvo-pristabdziusi-vilkiku-eisma-pasienyje-su-kaliningradu) Customs of the Republic of Lithuania e.system were not Available.
```

```
##### R esults
Citizens, officials, public servants, Importers and Exporters could not access their e.service up to 11-12 hours.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* About one Region in the Article: Poland name the Region as "Karaliaučius" (lit. l.).
* There could be hard to grasp a difference between Electronic document system and Electronic web page.
* When electronic system does not work a regular paper based workflow are plausible.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2231207/sukciai-toliau-is-gyventoju-vilioja-pinigus-zala-siekia-beveik-65-tukst-euru) scammers grab money from institution bank account. Scam on investment to web site. 
```

```
##### R esults
Number of citizens lost their own and instutition's assets.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* When personal computer or institution server are at risk, they could be used to send internal malicious messages with intend to scam for valuables. Would You help to the "colleague" over electronic channel?
* Install Antivirus and Antimalware solution. Use application(s) who could be securely handled thanks to this Antivirus and Antimalware solution.
* Take responsibility for the assets when they belong to someone else, i.e. institution, other person. Don't be fooled that another person's knowledge and turf are Yours & better ask for salary increase.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2231348/stabtels-pajamu-deklaravimas-penktadieni-neveikia-vmi-sistemos) a lot of VMI managed systems are limited with access over electronical government gate system.
```

```
##### R esults
Electronical services, except electronic declaration system, has limitations until wider Access is unavailable.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Authentication over (Mobile) phone with direct call could mean that person is required to disclose out loud (his) personal and sensitive information. It's necessary to take precautions.
* Companies over internet are using VoiP phone(s), which in the Lithuania are not very wide yet.
```

```
##### I ncident

According this check [-](https://github.com/PolVilniusTech/public.incident.reporting.timeline.md/blob/main/Lithuania/Images/RRT%20not%20Available%202024-03-29.PNG) and provided Image: the GitHub Service RRT Site is not Available.
```

```
##### R esults
Information about digital resources is unavailable. 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* When there is need to learn more about emergency signals, this could help [pagd.lrv.lt](https://pagd.lrv.lt/lt/ugniagesiai-pataria/civilines-saugos-signalai-ir-informacija-gyventojams/).
* When citizens want better technologies, i.e. only 5G Network, and in contrast Private Sector and (or) Public Sector shut down older 2G, 3G.. Networks we get chance that Emergency Systems could be outdated and new devices can't get response's & notification's.
* Fire Protection and Rescue Department under the Ministry of the Interior are maintaining Site [lt72.lt](http://lt72.lt/) and every citizen could check [lt72.lt](https://lt72.lt/kategorija/pranesimai/) while his device are getting notifications or not.
* Statistics of Availability for each public Service could help to Incident Response in some how.
```

```
##### I ncident

According this [Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2241900/nutekinta-77-mln-slapuku-is-lietuvos-sukciams-atsirado-galimybe-prisijungti-prie-paskyru-be-patvirtinimo) happened World-wide Cookie tech leak.
```

```
##### R esults
Around 77 000 000 HTTP session cookies were leaked. 
Out of them only twenty four percent could be active and working.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* In these Cookies plausibly could be found information like personal information, i.e. email address, location, home address..., authentication information, i.e. session tokens, (hashed) password...
* According [Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2164607/google-ima-riboti-tam-tikrus-narsykleje-chrome-saugomus-slapukus) Google start limiting Cookie technology and moving out from this technology. A Company like Google has already reached it's Life-cycle when Company could drop the Cookie technology from their Products. At this time already exists number of technologies for HTTP Client Software who could be deployed for this case.
* Exists only bigger problem with many HTTP Server tools around the Web, who could be used by small-medium Companies and enthusiasts. When small-medium Company(-ies) could start working efficiently with some of those tech(s), then bigger one makes decision to innovate and stay.
```

```
##### I ncident

According the Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2243944/apgaule-is-parduotuviu-pasisavinta-prekiu-uz-53-tuks-euru) security flaw in company's payment system lead into loss of goods in shops.
```

```
##### R esults
Shop or more shops got scammed. 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* This article provide Situation with no leads into where is the problem: problem in company's physical shopping scheme and (or) electronical device and (or) internet payment system? By default this looks like a scam in a regular physical shop.
* Problem in an organisational ecosystem of a physical shop? Does this allow to request for goods and leave w/o payment?
* Problem in an electronical device for payments inside a shop? Does this electronical device is infected and show complete for employee and not complete for client? Client may not come for a second time and with gliched payment's this electronical device is not a convienent way to make purchase's.
* Problem in an internet payments? With wrong way of security checks exist a plausible situation that added products could be purchased w/o spending a penny, but this is not what were intended to do.
```

```
##### I ncident

According this [Judu.lt](https://judu.lt/vilniaus-viesojo-transporto-strategija-iki-2030-m/) citizens get chance to understand places where their money gonna be spended in the long turn. It's unfortunate that link checking are not common testing method in World-Wide-Web yet. This following [Judu.lt](https://judu.lt/wp-content/uploads/2021/06/VT-ambicija-2030.pdf) link return "404" for a long long time. Evidence according this check [-](https://github.com/PolVilniusTech/public.incident.reporting.timeline.md/blob/main/Lithuania/Images/JUDU%20Page%20404%202024-04-10.PNG) provide results of the HTTP response code 404.
```

```
##### R esults
Unavailable resources.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* HTTP response code of 404 means that while regular GET request in response got "NOT FOUND". This could mean that PDF file is not in a place where it has to be. Plausible situation is that after a new file upload the site were not updated.
* In a chance when there were more vulnerable information reporting for security researchers couldn't get so simple, i.e. [-](https://judu.lt/.well-known/security.txt) or [-](https://judu.lt/security.txt) return HTTP response code 404. GPG/PGP information for encrypting message(s) is unknown.
* In West exists a hyghiene for linking documents in table like fashion. This means that information when the document were uploaded could be shown in page. This type of "Meta" information is unknown.
* Even after getting some document in the Page, i.e. [judu.lt](https://judu.lt/wp-content/uploads/2021/06/VT-2020-ataskaita.pdf) in the beginning client will get response code of 200 and cache the document in the HTTP client Software. Afterwards gonna be 304 "NOT MODIFIED" response code's while this document does not change.
* These documents contain valuable information for understanding what are planned beforehand. Take a sample of [judu.lt](https://judu.lt/wp-content/uploads/2021/06/VT-2020-ataskaita.pdf) in p. 78 & table 24 provided information about old trolleys park. There is provided idea that they don't contain "USB charging ports". Does this is very huge flaw? According the Article [cnn.com](https://edition.cnn.com/2023/04/12/tech/fbi-public-charging-port-warning/index.html) provided idea for a "juice jacking" problem. Does this is linked with only energy? No. Corrupted charging USB port could allow for a malicious actor to lock a device or extract personal data (emails, text messages, photos, contacts) & do not forget for something as password too. Take a sample that there could even be left some bunch of "infected cables". In the question: what to do? She could say: use electrical outlet instead of unknown USB charging port & cables. At least use Your own charger and USB cord.   
```

```
##### I ncident

According this check [Ktu.lt](https://github.com/PolVilniusTech/public.incident.reporting.timeline.md/blob/main/Lithuania/Images/EBOOKS%20too%20long%20to%20respond%202024-04-15.PNG) the link does not respond. The existence of this Site were found from common Web Site [Lrt.lt](www.lrt.lt).
```

```
##### R esults
Unavailable resources for an targeted audience.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Plausible of situation when Web Site provide link(s) into other protected Web Space of a specific computer network.
* When employees or common journalists get access to actual content they may don't know their own security context, available resource context. Interlinking Web Sites are regular approach for the Web.
* Technologies like VPN could make false feeling that selected context are available for everyone, so providing links to protected space, i.e. organisational private network, could happen.
```

```
##### I ncident

According the Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2248995/sukciai-is-imones-vilniuje-apgaules-budu-isviliojo-beveik-305-tukst-euru) a company received malicious request over email, that request transfer of money using fabricated message(s).
```

```
##### R esults
Entity lost hefty sum of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Unsolicited messages and SPAM over e-mail tech are an common approach for phishing attacks in the Internet. Clients use email applications with in-build protective means, i.e. phishing filter, scam filter. Exists chance that security measure(s) gonna fail to block this message or those messages. For this reason general SPAM has to be less effective, but huge in numbers (more blocking necessary). Targeted phishing emails has bigger success rate and could impact into losing hefty sum of money.
* Not all entities aware that e-mail application(s) has or could have in-build security measures to defend from number of risks.
```

```
##### I ncident

According the Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2251290/lietuvos-radijo-ir-televizijos-komisija-skelbia-patyrusi-rusijos-kibernetine-ataka) there was interruptions for whole three hours.
```

```
##### R esults
Site was getting interruptions for whole three hours. Yet, no impact.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Security Researchers from United States of America argue that "SolarWinds" attack probably happened w/o the entity, which is provided in the Article as threat Actor. In this case when "SolarWinds" Software producer (U.S.A. own company) impacted with around of 70 percent faulty cases of their poor and vulnerable Software there exists huge need to solve problematic and vulnerable Software issues in Lithuania also. It is clear that present vulnerability(ies) could be missused by third party(ies) and he or she, or even they could be anybody. Database register with faulty Software incidents could provide negative impact to Software producers, i.e. like in this case of "Solarwinds" company of the United States of America.
```

```
##### I ncident

According the Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2256150/sveikas-pasauli-pagrindinis-vmi-puslapis-pirmadieni-klientus-pasitiko-kitaip) main Site of State Tax Inspectorate under the Ministry of Finance of the Republic of Lithuania was off-line. Instead of original Site there was available substituted & different electronical resource.
```

```
##### R esults
After no more than four hours this electronical service started working again.
Unavailable resources for limited amount of time.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* When Web Site [vmi.lt](https://www.vmi.lt/evmi/en/misija-vizija-ir-vertyb%C4%97s) provide foreign language menu is great. Yet, not all actual information is shown in this foreign language. Plausible another problem when these foreign people could mistake the approved site by somebody with an other artificial site. There is problematic to find out more information about "vmi.lt" and existence of STI (lt. VMI) in here [vmi.lt](https://www.vmi.lt/evmi/en/teisin%C4%97-informacija). There is something who could provide proof of VMI.lt being non-phishing site [lrs.lt](https://e-seimas.lrs.lt/portal/legalAct/lt/TAD/TAIS.226992/asr). Second place to look at if you knowing lithuanian [lrv.lt](https://lrv.lt/lt/ministerijos-ir-istaigos/).
* Take sample from other institution document [e-tar.lt](https://www.e-tar.lt/portal/lt/legalAct/ef108e70e9de11e6bf03a1097d29892a). This one does not provide actual information about internet site name. There is provided information about how this e-mail is to be made off. By knowing real email schema there are plausible to conduct a phishing attack.
```

```
##### I ncident

According Articles [Lrt.lt](https://www.lrt.lt/naujienos/pasaulyje/6/2194490/tyrejai-atakos-pries-navigacijos-sistemas-dazneja) and [Err.ee](https://news.err.ee/1609326360/second-finnair-flight-turns-back-from-tartu-due-to-gps-interference) GPS jamming is taking place since the end of 2022. GPS disturbances and GPS interference prohibit use of a Global Positioning System (GPS).
More information regarding GPS jamming:
* [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2462795/neraminantys-duomenys-gps-trikdziu-skaicius-yra-padidejes-6-kartus);
* [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2618008/birzeli-pilotu-pranesimu-apie-gps-trikdzius-rekordas-22-kartus-daugiau-nei-pries-metus);
* [BNS](https://www.lrt.lt/naujienos/pasaulyje/6/2664581/svedija-pranesa-jog-baltijos-juros-regione-staigiai-padidejo-aviacijos-gps-trukdziu);
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2690460/i-lietuva-skrides-ispanu-gynybos-ministres-lektuvas-prie-rusijos-patyre-gps-trukdziu).
```

```
##### R esults
In specific location(s) the Global Positioning System is unavailable.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* GPS, GALILEO & other systems like GLONASS or BDS jamming prohibit use of any satellite navigation tech.
* GNSS testing software [github.com](https://github.com/barbeau/gpstest). This software has Apache v. 2.0 license.
* From International perspective, e.g. exists [International Telecommunication Regulations](https://www.itu.int/en/wcit-12/pages/itrs.aspx), that are signed by 89 Countries. Assume this only for reference: The Article 1 define "authorized operating agencies", that should get mutual agreement on International telecommunication services. The Article 2 include definitions of Telecommunications, International telecommunication service, Government telecommunications and Service telecommunication and etc. The Fourth paragraph of Article 5 communicate out, that Member States should encourage authorized operating agencies to inform all users, including roaming users, in good time and free of charge... Government telecommunications during training could block specific frequency, but let's go back to the Article(s), - it does not give any hints about mutual agreement(s) or so so.
* Aliuminium foil in some cases provide enough shielding from the interference [LRT.lt](https://www.lrt.lt/mediateka/irasas/2000436120/padeda-apsaugines-folijos-dezutes-gps-trikdziai-vis-dazniau-trukdo-skrydziams-nidoje).
* Telecommunication towers could be used for location detection too. According of one Article the GPS signal jamming on the sea and ground were detected too.
```

```
##### I ncident

According the Article [lrytas.lt](https://www.lrytas.lt/lietuvosdiena/aktualijos/2024/04/25/news/rinkimu-repeticija-virto-skandalu-mokymu-metu-vrk-per-klaida-nutekino-tukstanciu-rinkeju-duomenis-31571467) one member of Central Electoral Commission (CEC) by accident through electronic mail service shared non-anonymized data of twenty thousand voters, that include: First Name, Last Name, Personal Identification Code, Home Address. 
```

```
##### R esults
Shared non-anonymized information of twenty thousand voters.
```

```
##### I ncident

According the Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2261495/450-euru-virto-24-eurais-teikdamas-pajamu-deklaracija-vilnietis-vos-nepermokejo) citizen got a inaccurate declaration from the State Tax Inspectorate (lt. VMI).
According this Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2262464/registru-centras-lietuvoje-per-50-tukst-zemes-sklypu-ribos-yra-netikslios) provided statistics in errors.
```

```
##### R esults
Human Error in regular workflow could lead into mistakes.
By not fixing errors could mean only problem(s).
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Regular Citizens does not require to provide declarations. Only when exist requirement to pay Tax this citizen has to get a notification in the VMI system, i.e. You sold old Car and got extra money, then Pay a Tax. Everyone who forget gonna receive notifications from VMI.
* In the situation when institution at fault and made error, then citizen is not responsible and payment could be a void. Currently technologies like [satellites.pro](https://satellites.pro/France_map) helps in solving some of these problems.
* Human Error could be a leading problem in any sector including Information Security, Cybersecurity and Privacy protection. Poor quality automatized and untested functionality could be missused by threat agent.
```

```
##### I ncident

According the Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2263568/siauliuose-vyras-blokavo-prie-darzelio-atvykusiu-tevu-masinu-uzrakinima-pavoge-pinigus) exists device who block locking mechanism of a vehicle.
```

```
##### R esults
Exists possibility to bypass security measures deployed by security company(-ies).
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Nowadays people could use smartphone to (un)lock vehicle. Smart Tags could be used for starting the engine. Vehicle usually provide evidence with blinking lamps of some pattern.
* When number of vehicles use the same type of device (w/o modifications) to open and lock it, then exist risk for not only interruption(s). Opening and closing vehicle's also could be plausible.
```

```
##### I ncident

According the Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2264301/marijampolieciui-gresia-bausme-leido-sukciams-naudotis-savo-elektroniniais-duomenimis) provided essay with a situation. Person shared financial institution account with another entity and this is not legal in Republic of Lithuania. Entity without authorization and privileges managed bank account of this person. 
```

```
##### R esults
Person required to open a new account, because he needs to pay taxes. Person require to know every account, that are linked with him.
Entity could misuse account of this person and breach one or more jurisdictional regulation(s), take in account what is allowed and what - not.
By traveling to other country issues are not terminated (what were done). 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Social Network offer accounts for common users and bussines users. The communication between those two circles has small or no-proof of legitimacy. Anyone could create account and of course in number of situations social network or adversary could ask for copy of identity card - document, other credentials. In this case privacy concerns could arise. Data owner of named social network in the Article is "Meta Platforms Ireland Limited" (Europe users). Number of information groups is collected and everything explained in [facebook.com](https://www.facebook.com/privacy/policy). Person(s) has higher risk(s) for oversharing of information. Social network should be used by everyone who is eighty years old or older.
* Bank institution could close bank account when they see evidence of plausible terrorist financing and money laundering.
```

```
##### I ncident

According the Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2266769/google-atstovais-apsimete-sukciai-is-dvieju-gyventoju-isviliojo-per-27-tukst-euru) citizen of Republic of Lithuania give their trust to random scammer(s) who imitate as being "Google" employee(s).
```

```
##### R esults
Few persons were scammed.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* According XML document [www.lb.lt](https://www.lb.lt/lt/finansu-rinku-dalyviai?ff=1&market=1&type%5B0%5D=3&page=17&export=xlsx) a company of "Google" can't provide any bank services for Lithuanian or even E.U. user(s).
* The problem is known here [www.lb.lt](https://www.lb.lt/lt/naujienos/beveik-puse-lietuviu-nezino-kaip-patikrinti-ar-investuoti-siulantys-asmenys-nera-sukciai).
```

```
##### I ncident

According the Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2268556/telefonu-paskambines-sukcius-is-vyro-isviliojo-23-4-tukst-euru) scammer in unknown way got money from a single person.
```

```
##### R esults
Person is scammed and lost money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Employment as itself could be a money loss also in a situation when employee does not bring money to the employer with his work. Artificial and fake employment is one of threats of modern world.
* Sample for a money loss with "unknown way" could be a situation when Social Network App (Mobile Phone) allows digital payments. Person with simple action could make investment to unknown entity and investment always contain risks. [lb.lt](https://www.lb.lt/lt/naujienos/lietuvos-bankas-kaip-neprarasti-pinigu) provide ideas how to keep money safe and sound.
* Does scammed person has some kind of insurance for investment(s)? Law enforcement require to know it all.
```

```
##### I ncident

According the Article [ELTA](https://www.lrt.lt/naujienos/verslas/4/2268608/uzsisakiusi-prekiu-is-tiekejo-moteris-prarado-3-8-tukst-euru-o-siuntos-taip-ir-negavo) person lost money and purchased goods. The culprit — a vendor.
```

```
##### R esults
A client got Money loss.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Exist posibility to use Web Firewall Service [nksc.lt](https://www.nksc.lt/uzkarda.html) to get additional protection from scamming, smishing, phishing, spear phishing, fraud over the Web. Plausible Browser configuration [nksc.lt](https://www.nksc.lt/doc/dns/pDNS_DoH_instrukcija_pakeisti_narsykles_nustatymus.pdf) for people with less technical background. 
```

```
##### I ncident

According the Article [-](https://www.lrt.lt/naujienos/lietuvoje/2/2272211/sostineje-banko-darbuotojais-prisistate-asmenys-is-senjoru-isviliojo-12-7-tukst-euru) pair of pensioners were scammed and lost money.
```

```
##### R esults
Money loss for two persons.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* As of technological aspect, an electric banking outlet (type of (reverse-)vending machine for money) could have bad construction. Bad in a sence, that outside of an outlet exists plausibility to place external device who could skim the bank card. Skimming include reading information from magnetic tape and making a clone of the card. Bank cards include PIN protection over Chip, then it means there could be other external devices who could grab information of this PIN (i.e. Web camera, external Keyboard). Completely skimmed card could be cloned and used to take out money from people who are using those electric banking outlets. Insecure electric banking outlets would be a problem. Security updates of operating system included in the outlet also has to be tamper-proof. Security sticker could show the situation when electric banking outlet were opened by third party. Only official privileged personel have to manage electric banking outlets and own right license card.
```

```
##### I ncident

In the Articles [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2273061/sukciai-isviliojo-tukstantines-sumas-alytuje-gyventojas-neteko-53-tukst-euru) and [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2275131/gyventojai-dalija-pinigus-sukciams-i-nusikalteliu-rankas-pateko-per-39-tukst-euru) are placed multiple situations with scam reports.
```

```
##### R esults
High chance of a scam attacks.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Bank provide information that person has to report scam as fast as possible. Around the globe exists solution as mobile bank on wheels who takes in account the last mile problem. This vehicle require to own special identification touch points who has to be communicated for clients. Each bank has commitment to report situations when arise unacceptible risk for their clients. Only bank employees, who has privilege, in defined places and functions has right to ask for the card of the bank they represent. Like the law enforcement forces has rights to ask for showing personal identification card of a citizen or a resident, or a foreigner.
* Couriers deliver goods in a fixed time frame. In a time apart of that, these Couriers can't work.
* Scammers deploy specific domain names for conducting of their operations, i.e. Article [lb.lt](https://www.lb.lt/en/news/fraud-alert-scam-emails-allegedly-sent-by-the-bank-of-lithuania) provide idea that EU domain could be used with any name and without proof of real banking institution from Available list. Usual domain registration is automated process and lacks of counter-measures to limit risks of scamming. 
* Web Site [lb.lt](https://www.lb.lt/) contains resources for getting awareness tips to investment scams.
```

```
##### I ncident

In the Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2276394/banko-darbuotojais-prisistate-asmenys-is-tauragiskes-isviliojo-32-1-tukst-euru) shown risk for being scammed while in a own house.
```

```
##### R esults
Money loss.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Licenses of entities could be found in here: a) [lb.lt](https://www.lb.lt/lt/frd-licencijos/view_license?id=479) and b) [lb.lt](https://www.lb.lt/lt/frd-licencijos/view_license?id=343). B entity has physical facilities [lb.lt](https://www.lb.lt/lt/finansu-rinku-dalyviai/luminor-bank-as-lietuvos-skyrius).
* In a situation of profits from investment willingly require for filling taxes declaration in here [vmi.lt](https://www.vmi.lt/evmi/). Usual approach of bank institution — in addition they make administration and prepare all documentation, so people would not lose a faith in plausible investment. In a situation when bank can't do it, then person has to do it for himself.
```

```
##### I ncident

According the Article [Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2277155/sukciai-apgaudineja-apsimesdami-populiaria-siuntu-platforma-kaip-apsisaugoti) scammers employ parcel delivery service scams to grab sensitive and personal data. 
```

```
##### R esults
Informational.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Electronic services over internet could be misused by implementing man-in-the-middle malicious service. This could be solved with Content Security Policy Meta Header security options for modern browser Software.
* Single and Modern Application like Web browser could be connecting with other browsers for synchronization. Malicious organizations could provide malicious services to grab sensitive and personal information also.
```

```
##### I ncident

According the Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2280026/vilniuje-is-vyro-sukciai-isviliojo-apie-5-tukst-euru) via (unknown type) phone person were scammed and lost money.  
```

```
##### R esults
Plausible loss of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* There may exists bug in telecommunication system when by answering phone You lose money. Telecommunication companies usually charge both situations for calling and for answering, or even dropping the call. In this accordance person need to not answer unknown phone calls.
* When phone has chance to re-direct calls then this phone plausibly could be used for malicious re-directions and person, who receives calls can't understand when this phone come from unknown foreign location.   
```

```
##### I ncident

According the Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2283742/smugis-narkotiku-prekybai-telegrame-garsus-kanalas-likviduotas-ikurejas-suimtas) Social Media Solution is used for not legal activity — selling Drugs (or Narcotics).
```

```
##### R esults
Take-down and capture of a Social Media Account.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* web.telegram.org/k/ require a) QR code scanning for using the service or b) providing existing phone number (require to own a phone device) . By default Chromium Browser (v.120.0.6099.244) has "Create QR Code for this page" functionality. The Chrome and Chromium Browsers does not have QR scanning by default. The Chromium Web Browser could use "Telegram Web" app and this would create new Pop-up Page (like another Browser Tab). Login without handing phone number to the app and without owning a phone device could be problematic. QR Code instructions also send requirements about "on your phone".
* Provided physical capture of Social Media Account(s).
* Telegram include Question and Answer section where Question: "There's illegal content on Telegram. How do I take it down?" provide answer: "All Telegram chats and group chats are private amongst their participants. We do not process any requests related to them. But sticker sets, channels, and bots on Telegram are publicly available. If you find sticker sets or bots on Telegram that you think are illegal, please ping us at abuse@telegram.org", "You can also use the 'report' buttons right inside our apps, see <...> https://t.me/isiswatch <...> for details.", "<...> If a scammer is pretending to be you, contact <...> https://t.me/notoscam <...>". In other answer plausible to find following information: "this does not apply to local restrictions on freedom of speech. For example, if criticizing the government is illegal in some country, Telegram won't be a part of such politically motivated censorship. <...> While we do block terrorist (e.g. ISIS-related) bots and channels, we will not block anybody who peacefully expresses alternative opinions".
* Other Sample of solving tough question(s) in Social Media Service [transparency.meta.com](https://transparency.meta.com/reports/government-data-requests/further-asked-questions) for answering to request(s) of a government officials: Facebook define term of "non-content" — information such as name, length of service, credit card information, email address(es), and a recent login or logout IP addresses and other transactional information <...>. This information when requested are shared with Law enforcement (i.e. the government officials). Guidelines for Law Enforcement [www.tiktok.com](https://www.tiktok.com/legal/page/global/law-enforcement/en).
* Usual Comment on issues could be subjected from "Drug, Tobacco and Alcohol Control Department" [ntakd.lrv.lt](https://ntakd.lrv.lt/en/prevention/) & [ntak.lrv.lt](https://ntakd.lrv.lt/en/national-strategies-on-drugs/).
```

```
##### I ncident

According the Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2290551/google-atstovais-apsimete-sukciai-is-moters-isviliojo-per-14-tukst-euru) happened scamming events: a) over smartphone call and b) over email message. In both cases persons lost their Identification, Authentication and Authorization mechanism privileges and other entity received account balance when there was no consent to this.
```

```
##### R esults
Money loss.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Request to include money transfer limits, so You will not be able to spend higher sum of money per week, per month.
* Request that You will call over official phone and not receive phone call from unknown source.
```

```
##### I ncident

According the Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2292612/patikejusi-sukciu-apgaule-vilniete-prarado-6-2-tukst-euru) money were scammed from bank account of a citizen.
```

```
##### R esults
Money loss.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Bank organisation(s) never allow to communicate in clear text messages, video and audio between Clients in their Information System to limit number of phishing attacks.
```

```
##### I ncident

According the Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2298613/phoenix-payments-nubausta-beveik-1-mln-euru-bauda) provided News about Issues of the Member of Financial Market (Company) [lb.lt](https://www.lb.lt/lt/finansu-rinku-dalyviai/uab-phoenix-payments).
```

```
##### R esults
Member of Financial Market does not meet all Requirements.
Company lacks of procedures in a Risk Management.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Oficial information of Issues for this Company found in [lb.lt](https://www.lb.lt/lt/poveikio-priemones-2?query=UAB%20%22PHOENIX%20PAYMENTS%22&ff=1).
* Weak Identity Authentication mechanism can't protect Assets of a Client and a Company. Incorrect use of Athentication mechanism could lead into downgraded security when this could be stoped. Authentication Guide's include requirements, note [pci-dss](https://docs-prv.pcisecuritystandards.org/Guidance%20Document/Authentication/Multi-Factor-Authentication-Guidance-v1-w-note.pdf).
* According Article Company require to collect Financial Data for ensuring that Clients Assets are acceptable & according known Regulation, and auditable. Provided example of Customer Case File with flaws in finding out origin of customer income & funds. While being in risk factor an information need to share with the [Financial Crime Investigation Service under The Ministry of the Interior of the Republic of Lithuania](https://fntt.lrv.lt/en/). According Article each transaction and money operation has to be traceable.
* Place for problems and complains regarding Law [commission.europa.eu](https://commission.europa.eu/about-european-commission/contact/problems-and-complaints_en) while protection of information disclosure has to go according this [e-seimas.lrs.lt](https://e-seimas.lrs.lt/portal/legalAct/lt/TAD/3832a702d8ea11e782d4fd2c44cc67af). Lithuanian Bank in here [lb.lt](https://www.lb.lt/lt/pranesimai-apie-finansu-rinka-reguliuojanciu-teises-aktu-pazeidimus) accepts with Lithuanian Market related Issues and provide chance to report violations of Law in a Financial sector.
* Alongside disclosure exist risk of inclusion of technical issues who is linked to intellectual property related information (take a note in [en.wikipedia.org](https://en.wikipedia.org/wiki/Copyright_and_Information_Society_Directive_2001)) and protection of personal data information (take a note in [en.wikipedia.org](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation)).
```

```
##### I ncident

According the Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2299296/is-garbaus-amziaus-vyro-sukciai-isviliojo-45-tukst-690-euru) elderly person got scammed into investment of a Crypto Currency.
```

```
##### R esults
Money loss.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Crypto Currency is not included as protected in fixed sum [eba.europa.eu](https://www.eba.europa.eu/sites/default/files/document_library/Publications/Warnings/2022/ESAs%20warning%20on%20crypto%20assets/Translations/1028362/ESA%202022%2015%20Joint%20ESAs%20warning%20on%20crypto-assets_LT.pdf).
* U.S. provide Sanction List by Individual level & in this case person is not trustworthy and (or) blocked for Financial Operations [treas.gov](https://sanctionslist.ofac.treas.gov/Home/ConsolidatedList).
* Energy consumption make Crypto Currency as not Sustainable [sciencedirect.com](https://www.sciencedirect.com/science/article/pii/S2542435120303317). For the Future of this technology there could exist Frame and Standart, i.e. [acea.auto](https://www.acea.auto/fact/euro-standards/).
```

```
##### I ncident

According the Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2299782/payseros-klientai-susidure-su-duomenu-saugumo-pazeidimais) there is plausibility that half of client card's digits of "Paysera LT, UAB" and contact information were exposed.
```

```
##### R esults
Plausible loss of client information.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Client card data could be exposed in-directly over 3rd parties.
* Company has to ensure that Access Control to a Database and Private Data are at optimal level and secured.
```

```
##### I ncident

According the Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2301209/marijampoles-apskrityje-sukciai-is-moters-isviliojo-daugiau-nei-94-tukstancius-euru) scammers over 10 days period illegaly extracted hefty sum of money from a bank account of a victim.
```

```
##### R esults
Plausible loss of Money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* This amount of Money is impossible to withdraw from electronic bank account without moving to bank facillity. (Article) There has to be enforced limits to withdraw units per Day, per Week & per Month.
* Article include Image of Block's of Money with included Banderole's [vlkk.lt](https://terminai.vlkk.lt/paieska?search=banderol%C4%97). (Far East style).
```

```
##### I ncident

According the Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2302220/sutriko-smart-id-veikla) Smart-ID electronic services are unavailable.

More [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2301403/sutriko-smart-id-veikla).
```

```
##### R esults
Electronic service is unavailable.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Alternative options could help and improve Availability of the required function in question.
* Alternative system, when needed, could provide subsidy of the electronic service.
```

```
##### I ncident

According the Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2303918/sukciu-skambutis-kalvarijos-gyventojui-baigesi-6-tukst-euru-nuostoliu) person answered to phone call and lost money from a scam. 
```

```
##### R esults
Plausible loss of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Article does not include information whether scammer and person know each other.
* Telecommunication companies include limits to the service. Person with regular phone answer has to not be able to lose more money that in this balance.
* Context in the Article has links with a Social Engineering. Usually Scammer reminds the person that he's poor and ask, if he want get Job and (or) Invest Money. Leaked Databases with sensitive personal data could be used to Scam those who don't have what to offer anyway.
```

```
##### I ncident

According the Article [LRT.lt](https://www.lrt.lt/naujienos/pasaulyje/6/2305087/rusija-skelbia-blokuojanti-tris-lietuvos-portalus-tarp-ju-lrt-lt) mirrage rules between Russian Federation and European Union. LRT.lt domain now is blocked from a part of Internet.
```

```
##### R esults
Unavailable service.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  According this [Article](https://media.voog.com/0000/0051/2796/files/Rusconf_22.pdf): While television remains the primary source of information for the majority of Russians, its importance has dropped from 90 percent to 62 percent since 2014 as the role of the internet and social media have grown (Levada Center, 2021b). According main Article European Union are jointly blocking "RIA Novosti", "Izvestija" "Rossijskaja gazeta". According [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2407233/lrtk-prasymu-is-google-play-store-pasalintos-7-programeles-rodancios-rusiskas-programas) LRT Commission were requesting the Company for removal of sanctioned Software Applications in a Software Package Manager of their Software Store. To Media Stations over Internet related Software Applications were removed by the Company because of the E.U. sanctions.
*  Currently the Site [ria.ru](https://ria.ru) is Available. It is necessary to take in Account that Media Outlets has number of domains and servers over the Continents.
*  Social Media Networks [x.com](https://x.com/v_of_europe) and [facebook.com](https://www.facebook.com/rianru) comply with the official Ban. Origin of those limited checks were completed thanks to original & official information, which could be found in here [europa.eu](https://www.consilium.europa.eu/en/policies/sanctions-against-russia/timeline-sanctions-against-russia/). Banning "ethical and accountable" Media does not solve issues or cause of problem(s).
*  Limited access to resouces mean — loss of Availability. In both cases, everything is done according decision of both sides who control a data flow of Television, News.
*  In this case provided LRT.lt as News Source is a weak Source. Take a Note. Open Wikipedia [ru.wikipedia.org](https://ru.wikipedia.org/wiki/%D0%9B%D0%B8%D1%82%D0%BE%D0%B2%D1%81%D0%BA%D0%BE%D0%B5_%D0%BD%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%B5_%D1%80%D0%B0%D0%B4%D0%B8%D0%BE_%D0%B8_%D1%82%D0%B5%D0%BB%D0%B5%D0%B2%D0%B8%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5) in Comments are using "Закон о Литовском национальном радио и телевидении" indirectly from 3rd party. Place for the European Union Law is found in [eur-lex.europa.eu](https://eur-lex.europa.eu/homepage.html).
```

```
##### I ncident

According this check [-](https://github.com/PolVilniusTech/public.incident.reporting.timeline.md/blob/main/Lithuania/Images/2024-06-26%20RRT.LT%20Unavailable.PNG) RRT [lt.wikipedia.org](https://lt.wikipedia.org/wiki/Ry%C5%A1i%C5%B3_reguliavimo_tarnyba) is not available.
```

```
##### R esults
Unavailable web resource of institution.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  A taking care of Problems with SSL validation is essential for web site to be usable. At this time Cyber Security tool [dnschecker.org](https://dnschecker.org/ssl-certificate-examination.php) provide idea that "Successfully validated certificate chain." with rrt.lt.
```

```
##### I ncident

According this check [-](https://github.com/PolVilniusTech/public.incident.reporting.timeline.md/blob/main/Lithuania/Images/2024-06-26%20Unavailable%20404%20Pair%20of%20KAM%20Documents%20not%20Found.PNG) Ministry of National Defence Republic of Lithuania page include unavailable Documents. 
```

```
##### R esults
Unavailable documentation.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  This check include results: English Page include one Presentation while Lithuanian — three. In return pair of Documents are Not Available while Resource over Social & Media Network could be used.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2305506/du-gyventojai-sukciams-atidave-daugiau-nei-28-tukst-euru) pair of elderly citizens in different date & time and place were scammed. In one situation were used physical Bank cards. In result unknown people withdrawn Money from Bank Account's of this pair.
```

```
##### R esults
Plausible loss of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  Elderly are delicious target for scammers. Elderly is trusting youngsters for too much. This is a Scammer Year [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2198431/policija-siemet-fiksuoja-sukciavimo-buma-pradeta-per-500-ikiteisminiu-tyrimu).
```

```
##### I ncident

According this check [-](https://github.com/PolVilniusTech/public.incident.reporting.timeline.md/blob/main/Lithuania/Images/2024-06-26%20NEB%C5%AAKBERY%C5%A0IO%20service%20return%20500%20(Internal%20Server%20Error).PNG) nebūkberyšio e.service fails to start.
```

```
##### R esults
Electronic service is unavailable.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  Electronic service could be as a Dashboard for getting Status or other information regarding a main task of this service. e.Service for Upkeep information of a Web Page should provide statistic over the weekly, the monthly, the yearly Availability Rating. For this reason there is important to collect Status'es over period of time in a personal or systematic concern.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2307204/pastaraja-para-sukciai-is-gyventoju-isviliojo-per-20-tukst-euru) pair of Citizens from different Cities were scammed without idea of precise time when that happened. 
```

```
##### R esults
Plausible loss of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  Citizens require for secure communication channel with their service provider of their official Bank Facilities. Regions has no to less Bank Facilities, so they got less Availability for their Service and more prone to these scams. Some financial services complete banking operations at specific time, so there has to be possible to contact those representatives who could stop these banking operations when possible.
*  Awareness training for the public with sample actors who could display how these scams are completed could decrease situations when people get fooled in handing their Wealth.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2308658/uzsidirbti-senjorei-pasiule-sukciai-is-jos-isviliojo-daugiau-nei-11-tukst-euru) granny got scammed after answering mobile phone from scammers.
```

```
##### R esults
Plausible loss of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  Don't anwer phone calls from Unknown numbers when You do not wait for a call.
*  Marketing services usually sell their goods over the phone line. This is a other way for selling goods and no direct contact with seller is required. POST MACHINES provide a chance to pay for those products upon taking these goods.
*  In the Article probably are included limited information from granny's Statements. Elderly are mostly vulnerable to scammers.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2309278/banko-darbuotoju-ir-policininku-apsimete-sukciai-is-moters-isviliojo-per-101-tukst-euru) huge sum of money were scammed by impersonators.
```

```
##### R esults
Plausible loss of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  Daily Scam related Articles requires from itself to create specific Feed in the Media Outlet.
*  Officer can't show his Badge over the Telecommunication Means, so this type of communication is least trusted, even so, take into account Smartphones and Risk of [www.britannica.com](https://www.britannica.com/technology/deepfake) deepfakes.
*  Use official & trusted communication Channels. Call back with known trusted Source over Phone No., Internet Addr., etc. (something what could be checked in process of something gonna happen)
```

```
##### I ncident

According these Articles:
*  [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2310863/nusikalteliai-toliau-siaucia-i-sukciautojos-saskaita-moteris-pervede-33-tukst-euru) scammers are phishing money from Clients of a Bank or different Banks.
*  [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2319316/sukciai-is-vyro-isviliojo-14-5-tukst-euru) scammers are phishing random people.
*  [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2329824/sukciai-pinigus-viliojo-apsimete-google-banko-ir-policijos-darbuotojais) scammers are using Google Personnel and common Police Forces background.
*  [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2333863/sukciai-pinigus-is-vilnietes-viliojo-metus-is-saskaitos-dingo-per-33-tukst-euru) Scams could go even for a Year.
*  [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2343863/google-banko-ir-policijos-atstovais-apsimete-sukciai-pasisavino-19-tukst-euru) scammers are using Google Ireland Limited, common Bank Personnel and common Police Forces background.
```

```
##### R esults
Money loss.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  Employee of a Bank has limited actions from a list and apart of that nothing more they can't do & no Authority to request something from a Client as shown in this Article.
*  When somebody calls You and suggests for a help with Your Account, then You have to hang up this Phone's handset and do a direct call to Your Bank.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2324126/pirmadieni-buvo-sutrikusi-seimo-svetaines-veikla) Lietuvos Respublikos Seimas website were not Available for a hour.
```

```
##### R esults
Online Resources is unavailable.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  Network Hardware could be at fault. Manufacturer of the Hardware is unknown.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2329399/uzimtumo-tarnyba-per-klaida-nutekino-beveik-30-tukst-klientu-duomenu) Employment Service leaked sensitive information of their Clients over common electronic mail service.
```

```
##### R esults
For around of 30 thousand Clients data: name, personal identification code, personal email address, personal phone address, home address, data related with Client detailed Curriculum Vitae were leaked.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
*  Plausible that personnel has to make their own backups and still are working w/o content management system and only use physical files with Client data.
*  Currently people could be encouraged to use something as [EUROPASS](https://www.europass.lt/) and get to work in any of E.U. place they prefer.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2344597/nukentejo-nuo-romantinio-sukcio-is-saskaitos-dingo-21-4-tukst-euru) scammer over Social Media phished Money.
```

```
##### R esults
Plausible loss of Money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Outcome of Scamming: Loss of Trust over communication(s).
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/verslas/4/2344667/google-atstovais-apsimete-sukciai-isviliojo-10-tukst-euru-ir-paeme-paskola) given three Stories: a) Scammers phished single bank card and withdrawn money, and took bank loan. b) Scammers phished person over email. c) Scammers phished person over email.
```

```
##### R esults
Plausible loss of Money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Do not keep password of bank card together as plain text.
* Malicious e.Shop Web Sites could be at fault when dealing with Scammers over emails.
```

```
##### I ncident

According these Articles [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2348311/tele2-klientai-laikinai-negalejo-susisiekti-su-lietuvos-policija) and [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2347711/daliai-tele2-klientu-neveike-mobilusis-internetas-paslauga-atnaujinta) for short period of time Lithuanian Police were Unavailable for TELE2 CLients. In previous day TELE2 Clients had issues with TELE2 Network.
```

```
##### R esults
Clients lost Availability to the Service.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Exists plausibility to purchase Phone with multiple SIM slots. In this case Client has a chance to select more than one Telecommunication company as provider of Telecommunication Services. 
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2350362/uz-nenaudojama-ekstremaliuju-situaciju-sistema-kone-60-tukst-euru-per-menesi) two million data of Lithuanian people could be at risk. 
```

```
##### R esults
Lack of experience for data management and governance. 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Public institutions w/o experienced specialists are at disadvantage in software governance when they don't know how to deal with technologies and manage a data in technological environment.
* Public governmental data center(s) already purchasing licenses and owning data, but specialists questions are left to each institution for themselves. Public sector tend to have bad reputation for programming specialists because of being outperformed by programming academias and private companies who want to take a share of the market.
* ENISA is a Common Vulnerabilities and Exposures Numbering Authority in European Union and risky software applications gonna be taken accordingly, when software has to be used for processing private, confidential, sensitive data.
```

```
##### I ncident

According this [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2353326/sukcius-itikino-vyra-susikurti-mobiluji-parasa-jo-vardu-paeme-per-11-tukst-euru-paskolu) scammer used digital signature of a victim and taken loans. People has risk to get into investment fraud, phone scams. Institutions are getting trouble from interception of email messages.
```

```
##### R esults
Loss of an Assets.
Loss of a Confidentiality.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Secrets like passwords and PIN codes have to be kept secret and not disclosed to anyone apart Yourself. Person should not carry those Secrets in clear text in Public environment.
* Investment Clients have to use official companies who are registred and have certificate & permission to do their business.
* Email Service could be configured without more secure protocols and data could be passed through insecure routes over a net. Interception of data while routing and transfer could lead into a data loss.   
```

```
##### I ncident

According this Article [Vakaro žinios](https://www.respublika.lt/lt/naujienos/sveikata/sveikata/stringanti-esveikatalt---pikti-pacientai-gaisinami-medikai/) esveikata.lt has number of issues: connection interruptions; e.visit(s) are shown as unavailable when searching a Form for a second time; registration leads into hang up of the System and disapproved e.visit(s) are processed w/o notice & feedback; plausible situation that searching for requested medical investigation information is impossible; huge latency; irregular period for receiving e-prescription(s).
```

```
##### R esults
The System has issues with clarity & usability.
Unclear maximum capacity of this System & actual statistics of active Users.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Article include functionality of the System when it works correctly. Management of Failed Attempts are unknown.
* Accountable disclosure of Error Data to the System owner is unknown.
* User Manual or simple Q.uestion & A.nswer place could be unavailable.
* System could include data caching for speeding the Site.
* When Client request the e-prescription could include actual notification to this Client when it's ready.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2356139/malinausko-tyrime-zinomu-salies-imoniu-nutekinti-duomenys) provided information about:
* Employee data of the "Maxima" employee check system were leaked. This includes identificator, first name, last name, department, results from sobriety tests.
* Client data of a electronic shop web site's "varle.lt" were leaked. 386 thousand user data, i.e. first name, last name, order no. (last data from 2024-09-03)
* Client data of the "Švaros broliai" company were leaked. This include reservation information from five facilities. Data include: client first name, client last name, client e-mail, automobile license plate, reservation date.  
* Data of the "Unipark" company were leaked. In addition were plausible unauthorized Gate Management.
* Data of the "Telia" company were leaked. This include automobile park related information, first name, last name, phone number.
* Data of the "Fastlink" company were leaked. This include "Santjana" related client data.
* Vytauto Didžiojo Universiteto information exposed. This include 3.8 thousand contacts and procurement information from a single personal computer. 
* Data of  the "Kardiolitos klinikos" company were leaked. This include unauthorized access to information system.
```

```
##### R esults
Number of incidents who result with a loss of Confidentiality, Integrity, Authenticity.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* More responsibility and security related requirements for 3rd party services are necessary.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2359337/is-dvieju-garbaus-amziaus-vilnieciu-sukciai-isviliojo-10-tukst-euru) pair of elderly persons were scammed over (smart) phone.
```

```
##### R esults
Loss of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Data leaks online help for scammers to find their victims. As result they could get to know a lot about relatives, etc. of an elderly person and elderly target himself. Using this information scammers try to build scenario and scam target & persuade for handing money with their scheme. Elderly require for tools to keep secure communication line with their relatives, etc. so they could confirm event(s) directly or indirectly. 
```

```
##### I ncident

According this Article [BNS](https://www.vz.lt/verslo-aplinka/2024/09/16/proit-nutraukia-beveik-igyvendinta-spis-atnaujinimo-sutarti-su-sadm) software company terminates their agreement for system modernization with Ministry of Social Security and Labour of Republic of Lithuania. Other concerns:
* Ministry does not cooperate to solve modernization problems of system.
* Ministry include software company into a list of Untrusted Suppliers.
* Not all main system users were instructed with a new system.
* Not all users cooperated for system integration with their systems.
* Real cost of system modernization could be unknown.
```

```
##### R esults
Agreement between customer and developer terminated.
System inter-connection with other systems could be unavailable.
Some system users could lack of functionality from what were ordered.
Plausible lack of personel, vacations while System is not submited to the client.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Building plan with all system users of a customer with exact dates and tasks could help in handling whole project.
* There could be number of problems between customer and developer who are related to confidentiality, integrity and availability issues.
* Being in the list of Untrusted Suppliers could terminate future sales and agreements in a designated segment.
* Plausible of communication issues for expressing clear idea of what is happening.
* Agreement between customer and developer could lack of penalties for each of customer and developer in situations when something are going wrong.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/eismas/7/2365193/internete-viliojama-pirkti-padirbta-vairuotojo-pazymejima-bausme-gresia-ir-pirkejui) in Facebook exists Users who state that they sell Driver Licenses. Those Users tend to scam other Users in a social Media.
```

```
##### R esults
Scammed persons undergo Disinformation and loss of Money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Each Information System Administrator could create their User registration Registry and make Report to other well-known system at the end of each Month. This could help to find facts and to find out situation: does there exists undisclosed and unauthenticated access to this original & main DataBase.
* According the Article exists 182 User Accounts who were used for scamming. Social Media Company should be able to report their Internet Protocol Addresses in case of responsible request from a EU Member.
* The Site [regitra.lt](https://regitra.lt/lt/paieska?query=suk%C4%8Diai) include with scammers related various situations. News and other Articles are sorted in a random Way. I.e. This [regitra.lt](https://regitra.lt/lt/naujienos/regitra-ir-lietuvos-policija-glaudziau-bendradarbiaus-sukciavimo-ir-korupcijos-prevencijos-srityse) increase amount of around 500 Users who used their Accounts for scamming in two Years period.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/eismas/7/2366918/dalis-vairuotoju-susidure-su-sunkumais-sutrukde-ant-automobiliu-numeriu-atsirades-vytis) Vehicle License Plate Scanners does not recognise new type of Vehicle License Plates. 
```

```
##### R esults
Customers can't get to their Services with a new type of Vehicle License Plate.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* About changes information provided here [LRT.lt](https://www.lrt.lt/naujienos/eismas/7/2088308/iprasti-transporto-priemoniu-numeriai-nuo-siol-atrodys-kitaip-regitra-pristate-nauja-dizaina-su-vyciu).
* For limiting physical access, i.e. in times of sanctions, a chance of prohibiting specific format Vehicle License Plates is a tool to enforce sanctions. But in this Sample the problem that there are no whitelist (or list of allowed Vehicle License Plate). Page (or Resource) with Whitelist could provide more understanding not only for companies who use those Design templates in their Software and Hardware Products, but also for Border Patrol reasons and so on.
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/eismas/7/2367164/kauno-autobusai-ispeja-del-netikru-bilietu-facebook-isisiautejo-sukciai) in Social Media exists Page with disinformation about Public Transportation posibilities. In this Page everyone are encouraged to fill out for personal data and private and non-public financial data. 
```

```
##### R esults
Plausible Phishing attack for those who are not accustomed with use of a Service. 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Transportation Organization has to make a request to a Social Media for closing down this disinformation Page with aim to use similar trademark name.
* Usual Phishing problem - use of lookalike Pages with request to grab sensitive information.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2370072/fiksuojami-elektroniniu-valdzios-vartu-veiklos-sutrikimai) epaslaugos.lt Portal is functioning with irregularities when connecting to desired information systems.
```

```
##### R esults
Broken Authentication mechanism.
Clients can't connect to requested resources.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* epaslaugos.lt Site include User Guide. Site could include information for their Clients with explanation what they have or not to do when they get unique Error Identification Number.
* One System or more Systems updates could result in Broken Authentication Mechanism. When they don't meet requirements of a Technical Specification something could get not working, i.e. inter-connectiveness. Information System maintenance has to be coordinated accordingly with responsibility to successful Auth tests. This could at least inform they Users with more user friendly notification.
```

```
##### I ncident

According these Articles [BNS](https://www.lrt.lt/naujienos/verslas/4/2370124/sutriko-swedbank-e-bankininkystes-veikla-bankas-trukumus-salina) and [BNS](https://www.lrt.lt/naujienos/verslas/4/2370124/atkurta-swedbank-interneto-banko-veikla) some sub-Services were unavailable for online Joint Stock Company Banking Clients of the Swedbank.
```

```
##### R esults
Unavailable sub-Services.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* When sub-services are unavailable specific alternatives for Clients of the actual service could be given.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/verslas/4/2371715/suimtas-sukciavimu-itariamas-brokeris-galejo-igyti-svetimo-turto-uz-1-2-mln-euru) Real Estate Sales Portal were used by scammer for selling facility, land. For all of these scammer had no privileges and legal rights.
```

```
##### R esults
Portal does not prevent content administration by scammers. 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* System has to ensure Authenticity of Offer Providers and their Customers. Customer require for tools to prove that Offer Provider has rights to their Offer.
* System has to detect when any of those Accounts could be breached by brute-force login attack.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/eismas/7/2371110/nesklandumai-vilniaus-viesajame-transporte-gali-nepavykti-aktyvuoti-bilietu) activation of a ticket provide errorious notice. Users are suggested to ignore this notice and to use Service as usual. This is temporary issue of System.
```

```
##### R esults
System can't pass Confirmation Message.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* User with the same plastic Card has possibility to open and activate more than single Ticket. Suggestion to use next plastic Card does not help into distinguishing correct plastic Card type who could be used in the System.
* Device has number of Sensors for activating required ticket, so alternatives are available.
```

```
##### I ncident

According these Articles [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2372066/marijampoleje-is-vyro-sukcius-prisistates-google-darbuotoju-isviliojo-19-5-tukst-euru) and [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2374946/google-atstovais-apsimete-sukciai-is-klaipedietes-isviliojo-23-tukst-euru) scammers scam victims with disguise of employee from "Google" company or in disguise as one from relatives.
```

```
##### R esults
Scammed Victims willingly (or unwillingly) lose Money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* No more than twenty people are employed from "Google" in Lithuania. Chances to get contacted with one from them without Your own direct request are bare minimum.
* Vehicle accident and afterwards a request for huge sum of Money has more questions than answers, because of plausible scam in that same place. Insurance Company responsible to be mediator between parties of an accident. Better suggestion would be to call for a Road Police and to handle an accident of a vehicle(s) in situation when Person is in a shock and does not know how to handle it. Direct call to a relative could provide more trust in words when their communication means, in eg. a mobile phone, is not stolen. 
```

```
##### I ncident

According this Article [ELTA](https://www.tv3.lt/naujiena/lietuva/sostineje-google-darbuotojais-prisistate-sukciai-isviliojo-6-6-tukst-euru-n1370494) scammers who self-represent themselves as "Google" employee & Policeman conducted a Scam.
```

```
##### R esults
Plausible money loss
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* From journalism perspective leading Photo of this Article adds even more confusion to the "Google" part.
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/verslas/4/2384783/sutriko-luminor-interneto-banko-ir-mobiliosios-programeles-veikla) banking internet page provided notification about ongoing maintenance in the Message of their Web Site. Web Site and Software Application are not working as usual.
```

```
##### R esults
Unavailable service.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Banking internet page also include Messages that their customers has number of risks from scammers. Not all customers know about whereabouts of those informative pages.    
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/kultura/12/2383640/paaiskejo-tikrieji-piratinio-turinio-naudojimo-lietuvoje-mastai) there was calculated country rating for using unlicensed and unauthorised Content.
```

```
##### R esults
Plausible places for introducing and spreading Malware & Virus Software. 
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* To the Article included Raport provide concern that users "lack of knowledge" how to distinguish between licensed & author rights preserving content and unlicensed & content without author rights.
* This Raport include that Google Search Engine is mostly used for searching and accessing unauthorised and unlicensed Content.
* This Raport include that usual technology for searching and accessing unauthorised and unlicensed Content are Browser's and Software Application's.
* This Raport include concern that Social Media Accounts are used for spreading Content and Content parts w/o original & real Author's Consent, i.e. some Border Template added to this Content...
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/verslas/4/2387241/inbank-nukentejo-nuo-sukciu-atskleisti-dalies-klientu-telefonu-numeriai) scam has revealed weak points of "Inbank" bank's service provider systems who plausibly disclosed information like phone number of a customer, first name of a customer, agreement number.
```

```
##### R esults
Loss of private customer and service data.
Loss of Confideniality.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Scammers use leaked information in conducting new phishing attacks.
* From the Article is not fully clear: how unknown person got access to service provider system with plausible functionality of Short Messaging Service (SMS)? if this incident is linked with Unauthorised Access to SMS Modem, then we have problem with in the Risk Management.
```

```
##### I ncident

According this Article [TV3](https://www.tv3.lt/naujiena/verslas/sutriko-swedbank-veikla-zmones-negali-atsiskaityti-n1371893) issues with e.bank and e.apps of "Swedbank" Bank Organization. Banking services unavailable or works with interruptions.
```

```
##### R esults
Loss of Availability.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Without digital assets Clients can't access their Goods and Services. Banking companies does not provide additional Card or App of their competitors for insurance when something like this happens. In other hand, technical issues also could happen in the place where Client would want to spend his(her) Money. Dependency issue as common and usual situation.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2389902/taurageje-policijos-pareigunu-prisistates-asmuo-kito-zmogaus-vardu-paeme-paskola) scammer took loan in behalf of other person. Another scam over the phone [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2389890/sostineje-ir-vilniaus-rajone-sukciai-is-zmoniu-isviliojo-apie-43-tukst-euru).
```

```
##### R esults
Plausible loss of Money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Lack of authentication measures mean that people could get bankrupt by scammers when they not intended to take a loan.
* Including people into list who does not agree to take any kind of loans could help to protect those people. The person have to know how to check, if he is the list through public protected & authenticated service.
```

```
##### I ncident

According this Article [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/kitos-lietuvos-zinios/perspejama-apie-sodros-vardu-siunciamus-sukciu-pranesimus-raginama-nespausti-juose-esanciu-nuorodu/) scammers send phishing links with aim to breach site of social security service "Sodra". 
```

```
##### R esults
Plausible loss of Confidentiality
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Social security service "Sodra" don't send any emails. Citizen get notifications directly in the Site of "Sodra".
```

```
##### I ncident

According this Article [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/nusikaltimai_ir_nelaimes/klaipedoje-advokato-padejeju-prisistates-asmuo-is-vyro-isviliojo-10-tukst-euru/) teen scammer who presented himself as lawyer's assistant has lured out money from a citizen. This is non-Technologies related incident.
```

```
##### R esults
Plausible loss of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* High chance that this is a Social Engineering Attack and plausible situation of sharing a lot of information, i.e. over a social media. This information also could be used by scammer(s) motives. 
```

```
##### I ncident

According this Article [TV3](https://www.tv3.lt/naujiena/lietuva/vairuotojams-perspejimas-galite-netekti-ne-tik-pazymejimo-bet-ir-sulaukti-grieztos-bausmes-n1370047) scammers suggests their services for purchasing and getting driver's license.
```

```
##### R esults
Plausible a man-in-the-middle scam.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Journalist communicate with scammers. Usual suggestion in e-mail world for security reasons: Don't reply to the email of a scammer. In many cases exist possibility to be a victim of a phishing attack.
* In case of driver license to be treated as personal identification document no unauthorized third parties have to be involved in planning, designing, creating, sending and receiving this document.
* Article include statement of a scammer, — it's all legal and official. There could be questions added, i.e.: Does this scammer for himself move through the mandatory Driver's Exam? with identity of somebody else? Sample of scammer's price is added in the Article. Scammers are creating and using their own advertisements.
* Organizational and Examination Rules could be lacking and (or) with issues, so the place in-between would not simply be taken by scammers. Available and suggestions for legal advertisements over communication means could boost trust for getting driver's license in normal way.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2391990/sutriko-vmi-sistemos-veikla) the State Tax Inspectorate (lt. VMI) System "Mano VMI" is Unavailable.
```

```
##### R esults
Clients can't access Mano VMI System.
System is Unavailable.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Authentication error could be linked with unable to access of User Data. According the Article issue is found and not disclosed to public.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2394257/vilniuje-sukciai-is-zmoniu-isviliojo-apie-24-tukst-euru) were described multiple cases when caller-scammer scamd a victim over telephone and in result from this victom his subordinate in person take out phished money.
```

```
##### R esults
Plausible loss of Money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Exists notifications in number of journals about people who scam, i.e. by pretending themselves as relatives of victims (or victims of those relatives) and in return want money. Article does not specify details about a situation. 
```

```
##### I ncident

According this Article [TV3](https://www.tv3.lt/naujiena/verslas/swedbank-vel-perspeja-klientus-del-trikdziu-n1373030) electronic banking service "Swedbank" functions with interruptions & irregularities, Customers could have problems using e.payments of this service. Bank Service include Timestamp for their planned Maintenance.
```

```
##### R esults
Planned unavailable service.
e.service issues.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Number of services report their maintenance plans through communication contacts that is confidential between client and e.service.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2396846/pasiule-investuoti-sukciai-is-garbaus-amziaus-vyro-isviliojo-110-tukst-euru) scammers use e.investment platforms, cryptocurrency and scam number of people who can't reject it.
```

```
##### R esults
Plausible loss of Money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Article include best actions in such situations.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2399965/investuoti-itikine-sukciai-is-vilniecio-pasisavino-87-8-tukst-euru) person were scammed in social media for investment over internet. Person lost his investment.
```

```
##### R esults
Plausible loss of Money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Other plausible situation that some controls not in place who provide adverstments scam over social media.
* Adverstment Company could be a target by scammers to share malicious code & viruses.
* Lithuanian Bank provide best practice how to avoid investment scams.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/verslas/4/2400657/seb-klientai-gali-patirti-trikdziu-jungdamiesi-prie-programeles) bank software application could have issues and interruptions, communication over phone is unavailable.
```

```
##### R esults
Loss of Availability of Service.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* According Article web portal is functioning as usual.
* Web portal and Software Application are pair of technologies who use Internet Infrastructure for connecting Clients with their Wallets and other banking services through web server or banking app inside of user device. Distributing those technologies into different projects helps to create an additional way to link customers with their services.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2401905/sukciai-vel-pasipelne-is-vilniaus-apskrities-gyventoju-isviliojo-per-32-tukst-euru) scammers could withdrawn money from bank account of their victim. Article includes plausible investment fraud too. More scams [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2402717/siauliuose-kedainiuose-panevezyje-ir-vilniuje-sukciai-isviliojo-apie-64-tukst-euru).
```

```
##### R esults
Loss of Confidentiality.
Plausible loss of Money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Description in the Article provide idea about breach of a banking system when plausibly person willingly or unwillingly shared credentials (personal secret access data that newer have to be shared with anyone else). Article provide idea that callers were using deception by hidding their real intend of a scam. Usually scammers are talking in foreign language and the Article does not provide any details about this situation.
* Investment as itself could look similar to gambling, at this time more attention gets a Bond [wikipedia.org](https://lt.wikipedia.org/wiki/Obligacija).
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2406107/gedimas-be-interneto-paliko-120-istaigu-rizikas-prognozavo-bet-plano-b-nebuvo) Litnet technical center in the Klaipėda for two consecutive days had problems in providing Internet services to the Public institutions.
```

```
##### R esults
Loss of Availability
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* According Article this incident is related with technical issues. Protection from Fire System was the culprit. Additional product(s) were needed to purchase and fix this issue.
* The Article include idea about existence of very Complex Cybersecurity Solution. When failing service is not related with the Internet service, a question: why this is linked with e.service, that are provided to a number of Customers?
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2407463/sukciai-apsimete-policininkais-ir-bankininkais-is-zmoniu-isviliojo-per-96-tukst-euru) number of people got scammed by people who deceived their victims.

```

```
##### R esults
Plausible loss of Money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Article define incident(s) that could be linked with a "Bank fraud", [Reference](https://en.wikipedia.org/wiki/Bank_fraud).
* Lithuanian Bank has not issued important terms and abbrevations for general public, evidence could be found in VLKK page ["Term bank"](https://terminai.vlkk.lt/paieska?search=Bank+fraud&zodzio_dalis=3&kalba=2&kaip0=on&sritys=&statusas=0&rykiavimas=0).
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2411202/itikine-investuoti-sukciai-is-klaipedietes-isviliojo-15-tukst-euru) person got scammed into investing using internet platform. In this way money of this person got phished out.
```

```
##### R esults
Money loss.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Lithuanian Bank provide guidance how to help for people who want to safely invest their money: [lb.lt](https://www.lb.lt/lt/naujienos/lietuvos-bankas-kaip-neprarasti-pinigu).
* Lithuanian Bank provide chance to stop for opening new credits [lb.lt](https://www.lb.lt/lt/naujienos/i-stop-vartojimo-kreditams-duomenu-baze-vartojimo-kredito-daveju-uzklausos). Chance to prohibit investmens could be taken in to the account.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2414680/telefoniniai-sukciai-is-dvieju-moteru-isviliojo-daugiau-kaip-37-tukst-euru) scam and fraud over the phone.
```

```
##### R esults
Plausible loss of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* From the Article is not clear while those entities were providing any evidence about whereabouts of their position. Do You trust any stranger (or not so big stranger) when the business goes about your richess? 
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2416897/laikinai-buvo-sutrikusi-vyriausybes-prezidenturos-interneto-svetainiu-veikla) datacenter got disruption of their website hosting service. This lasted for a hour until electricity power supply was re-established. Uninterrupted power supply security control were ineffective.
```

```
##### R esults
Loss of Availability
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Conducting periodical tests on Uninterrupted power supply security mechanism.
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2416564/jeglinskas-apie-nutrauktus-kabelius-baltijos-juroje-karyba-keiciasi-esame-taikinyje) "Telia" Telecommunication company has lost their capacity on internet bandwidth by one third. 
More: 
* [ELTA](https://www.lrt.lt/naujienos/verslas/4/2426470/telia-atkurtas-rysys-su-svedija-per-kabeli-baltijos-juroje).
```

```
##### R esults
Loss of Quality and Performance
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Slim protective layer of a product could lead into higher chance for unwanted breaking from environment and man-made Risks.
* According this Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2458233/arteja-lietuvos-atsijungimo-nuo-brell-laikas-politikai-ir-ekspertai-ispeja-del-diversiju) a Wire in the Sea could be not at a Seabed, but much more Higher than that. Even on the Ground Wire could be placed in Air & in some aspect could be left in dangerious condition. Inventorization and administration & maintenance of these Assets have to be in Place. Specialists require proper Education to deal with that.
* Number of Agencies are starting to monitor underwater Assets [lrt.lt](https://www.lrt.lt/naujienos/pasaulyje/6/2493837/svedija-tiria-itariama-kabelio-baltijos-juroje-apgadinima). Researchers provide proof, that this happens very often & don't need to link at fault a SCAPEGOAT.
```

```
##### I ncident

According this Article [Lrytas.lt](https://www.lrytas.lt/verslas/mano-pinigai/2024/11/20/news/-swedbank-klientams-pranesa-aktualia-informacija-del-galimu-trikdziu-nakti-nenustebkite-35259761) "Swedbank" will be inacessible for 4 hours and 30 minutes.
```

```
##### R esults
Loss of Availability
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Backups of databases are done in similar periods. During backups clients are redirected to informational page about Maintenance. Backups have to be kept safely out of a domain.
```

```
##### I ncident

According this Article [BNS](https://lnk.lt/straipsniai/kriminalai/policija-pranesa-kad-sukciai-is-sostines-gyventoju-isviliojo-89-tukst-euru/286845) scamming happens through Software Application, Mobile Phone.
```

```
##### R esults
Loss of Money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* In most cases scammer want to get access to a device of a victim. Device with Remote Desktop connectivity could be abused to make Remote Desktop Connections. In this way a victim could provide access to a scammer & would allow execution of scammers planned procedure.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2430037/perpardavejai-nemiega-uz-lietuviska-moneta-praso-3-5-tukst-euru) Web Site that belongs to Lithuanian Bank is unresponsive and can't service enough of Clients.
```

```
##### R esults
Loss of Availability
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Web Sites that are used for services, e.commerce have to be maintained and upgraded for providing services to expected maximum number of plausible active users. Server that can't handle this amount of users has risk to receive non-malicious attack of Distributed-Denial-of-Service. 
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/verslas/4/2428373/mazeikiuose-nuo-telefoniniu-sukciu-nukentejo-asociacija-prarado-16-tukst-euru) scammers pretended themselves as "Google", Police, Bank Employees & conducted a Fraud attack. Jurisdictional entity lost sixteen thousand euros.
```

```
##### R esults
Plausible loss of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Scammers may try to pretend themselves as legal subjects to create fraudlent income. They expect to steal money for consecutive times, as much as possible. 
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/verslas/4/2428373/mazeikiuose-nuo-telefoniniu-sukciu-nukentejo-asociacija-prarado-16-tukst-euru) scammers pretended themselves as "Google", Police, Bank Employees and conducted Fraud attack. Jurisdictional entity lost sixteen thousand euros.
```

```
##### R esults
Plausible loss of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Scammers may try to pretend themselves as legal subjects to create fraudlent income. They expect to steal money for consecutive times, as much as possible. 
```

```
##### I ncident

According this Article [BNS](https://www.tv3.lt/naujiena/lietuva/sutriko-kai-kuriu-valstybiniu-instituciju-tinklapiu-veikla-n1382710) web sites of the Lithuanian Government and some others were unavailable. Technical issue lead into this situation. Service was restored [ELTA](https://www.tv3.lt/naujiena/lietuva/valstybiniu-instituciju-interneto-svetainiu-veikla-atstatyta-n1382731).
```

```
##### R esults
Loss of Availability
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* With new technologies there are important to update and test out recovery procedures from incidents like shown in these Articles.  
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2431421/skaudus-praradimas-sukciai-is-vilnietes-isviliojo-net-apie-70-tukst-euru) scammers are scamming for money of people in a social media. Person handed his bank account and cards to a scammers.
```

```
##### R esults
Plausible loss of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Fake facilities could be created to make scams. Even people could be employed in those fake facilities to do illegal work. All of related entities who participate in scamming are at fault.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2432073/sukciai-skambina-gyventojams-sodros-vardu) scammers pretend themselves as employees of "Sodra". More:
* [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2434511/islikite-atsargus-telefoniniai-sukciai-toliau-apsimeta-sodros-darbuotojais)
```

```
##### R esults
Informational
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Customers of "Sodra" has their own Accounts that is used for communication or initiating communication.
* Plausible problem in Public and Private Sector that sensitive and private data are not defined depending it's sensitivity and plausible use cases are not standartized (widely), e.g. does ID could be used as identification through the phone? or does Informational System request for specific sensitive data to process Employee request, so creates pretext to require sensitive information for completing a (e)service. Scammers get a hold of these irregular requirements for their sake to make successful attack. Assume problem when one system request for one type of sensitive data and other system — for the same request take other type of sensitive data.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/verslas/4/2433234/savaitgali-vartotojams-nebus-pasiekiamos-vmi-sistemos) State tax Inspectorate (VMI) undergo Maintenance and two consecutive days gonna be unavailable.
```

```
##### R esults
Loss of Availability
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Take into an account, e.g. when G2B, B2B make agreement for available service: Full Year upkeep is a 100 percent; 2 days less than the full Year upkeep - 99.452 percent. Business does not want to get penalty for paying interest - financial charges when a problem is related to other party that does not provide their service in time. 
```

```
##### I ncident

According this Article [ELTA](https://lnk.lt/straipsniai/kriminalai/plinta-naujas-sukciavimo-budas-sukciai-sukure-i-esveikatalt-panasia-svetaine-ir-savinasi-pinigus/288179) provided idea of similar & look-a-like phishing site that is used for scamming. Access to scamming site and use case lead into money loss.
```

```
##### R esults
Loss of integrity
Loss of confidentiality
Loss of money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* When e.service own plausibility to pay for their services & has flaws, then this functionality could be abused. Article does not include statement about functionality like this.
* Similar and look-a-like site could be problem for clients who don't know the original. Even so, e.services usually does not communicate about their development of e.service and each periodical new update could make clients less resistant to existance of similar and look-a-like sites.
* Article provide idea about a SMART ID service. When some service does not use additional or different than usual security measure to make some other action than Authentication, then scammers could try to build look-a-like sites that could steal money. Stealing money from Bank Account is related to money transfer from one bank account to other bank account. International bank transfers need more time than local ones, so client who has noticed a problem need to contact his local bank to stop a transaction.
```

```
##### I ncident

According this Article [ELTA](https://lnk.lt/straipsniai/kriminalai/sukciai-susizere-beveik-50-tukst-euru-atsiunte-suklastota-nuoroda-paeme-kredita/288162) person got phishing link that lead into money loss. Link was received over software application "Messenger".
```

```
##### R esults
Plausible loss of money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Software (e)services provide more easy way to pay for goods and services. Clients have to open separate Account on their Bank, so they will not link their main Account with some e.service that could be a target of scammers. Transfering money to this separate Account could take some time, but even so, does this Client is not placed any restrictions to daily-weekly-monthly money transfers?
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2438164/silutes-rajone-sukciai-moters-vardu-paeme-greitaji-kredita-zalos-dydis-5-tukst-euru) person had Fraud attack by anonymous phone call.
```

```
##### R esults
Plausible loss of money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* When Office can't ensure, e.g. that man is really what he identifies himself, then this person could challenge the statement that he wanted to take money for real. There could be used data from some data breach. Before handing money to a person financial institution has to ensure that innocent client's assets would be not at risk. Highly risky money operations have to be stopped.
```

```
##### I ncident

According this Article [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/lietuvos_politika/is-sostines-gyventojos-sukciai-isviliojo-74-tukst-euru/) scammers has a way to steal money from a bank account. Elderly person is a victim of a scam.
```

```
##### R esults
Plausible loss of money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Bank institution needs to provide awareness trainings to an elderly.
```

```
##### I ncident

According this Article [Lrytas.lt](https://www.lrytas.lt/it/ismanyk/2024/12/16/news/sutriko-smart-id-veikimas-35675690) Smart-ID service is down for 46 minutes.
```

```
##### R esults
Loss of Availability
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Own solutions for some service like digital signing from multiple of entities. This way increases a chance of using service that does not does enough for it's security and privacy.
```

```
##### I ncident

According this Article [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/kitos-lietuvos-zinios/policija-gyventojams-siunciamos-melagingos-zinutes-apie-neva-neapmoketas-baudas-uz-greicio-virsijima/) citizens of Lithuania are getting Messages of Short Message Service that include phishing links.
```

```
##### R esults
Informational
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Modern Devices with Internet browsing capability are affected.
* Article & Reference [BNS](https://www.lrt.lt/naujienos/verslas/4/2441239/sukciams-toliau-siauciant-lietuvos-bankas-ragina-kova-su-jais-koordinuoti-valstybes-lygiu) provide official registered information about lost money from phishing: 2020 Year - 4.8 million EUR, 2021 Year - 10.2 million EUR, 2022 Year - 11.8 million EUR, 2023 Year - 12.3 million EUR, 2024 Year - 14 million EUR.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/verslas/4/2443999/sukciai-itariama-kesinosi-isvilioti-kone-250-tukst-euru-is-vilniaus-miesto-busto) scammers tried to scam for money from an Entity of "Vilniaus miesto būstas".
```

```
##### R esults
Plausible loss of Money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Employee who has privileges to do financial operations could be a coulprit of problem that could lead into loss of Money.
```

```
##### I ncident

According these Articles [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2445285/sukciai-nesnaudzia-pasitelkia-socialinius-tinklus-ikalbejo-paimti-paskolu) and [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/nusikaltimai_ir_nelaimes/kaune-is-moters-isviliota-18-tukst-euru/) scammers fake their role and could use any communication tech to reach their victims.
```

```
##### R esults
Plausible loss of Money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Scammer is interested in any kind of currency in a cash, money in an bank account, a loan, any other type of valuables and is not different from regular person who is a criminal thief. Accordingly some persons could go to get employed with aim to scam weakest and vulnerable people & to use their privileges against others & use availability of information that they could get at any time. Scammer could destroy reputation of an organisation & would make damage to it's trust & reliability. Organisation that does not care about their own reputation and image & by having scammers between themselve link it to an corrupted organisation. More about corruption prevention at [stt.lt](https://www.stt.lt/korupcijos-prevencija/apie-korupcijos-prevencija/7742).
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2445580/is-moters-banko-saskaitos-sukciai-pasisavino-70-tukst-euru) scammers over phone collected secrets of their targeted victim. Afterwhile Money were withdrawn from victim's electronic banking account.
```

```
##### R esults
Plausible loss of Money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Disabling less secure authentication options and enabling only secure ones could be a way to solve some of problems like this.
* Awareness training for Customers could make Service more resilient from scammer attacks.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2446269/kibernetinio-saugumo-specialistas-valinsko-svetaineje-pamate-isilauzima-ir-idiegta-virusa) "Binance" functionality were found in a valiustv web site.
```

```
##### R esults
Increased Availability of a questionable functionality
Plausible breach of a site.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Lithuanian Bank inform [lb.lt](https://www.lb.lt/lt/naujienos/perspejimas-vartotojams-del-binance-uab-ir-kitu-su-kripto-turtu-susijusiu-paslaugu-teikeju) that UA "Binance" virtual currency exchange operator provide services w/o license. Clients of this service are at risk, because of using of not regulated company.
* Cryptocurrency exchange operator could provide more than just a Cryptocurrency, they could provide a Virtual Currency too. Can't place equal sign between both of them. Cryptocurrency taken as not regulated tech.
* The Article provide statement that in a web site is included a "virus" code. Risk of plausible financial phishing and (or) scam could be taken into an account. 
```

```
##### I ncident

According these Articles [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2447049/banko-ir-policijos-darbuotojais-prisistate-sukciai-is-moters-isviliojo-10-tukst-euru) & [Lrytas.lt](https://www.lrytas.lt/lietuvosdiena/kriminalai/2024/12/28/news/sukciai-is-salcininku-gyventojo-isviliojo-kone-30-tukst-euru-35818763) scammers used social engineering & fooled person to hand in his money.
```

```
##### R esults
Plausible loss of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Call to official phone numbers only. Unknown phone calls is not trustworthy & trustless. When caller does not meet related service agreement hang up and call to the service helpdesk. 
```

```

### 2025


##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2451661/klaipedoje-banko-darbuotojais-prisistate-sukciai-is-moters-isviliojo-apie-17-5-tukst-euru) victim was scammed over a phone.
```

```
##### R esults
Plausible loss of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* People with idea of upcomming Investment should take in Account Lithuanian Bank's 5 Step Guide [lb.lt](https://www.lb.lt/uploads/documents/files/Pakliuvote%20sukciams%202023_6_su%20linkais.pdf). 
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2452252/buvo-sutrikusi-seb-banko-veikla) following services of SEB e.Banking system are unavailable: Web Portal, Mobile Software App, Consultation Center. Around three hours were needed to restore these services into functional state.
```

```
##### R esults
Loss of Availability.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* This could look into dependency on connectivity through a single Telecommunication Company. The Article does not explain any technical difficulties that took out services from operational state for approx. three hours period. 
```

```
##### I ncident

According these Articles [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2454330/uzteko-vieno-skambucio-sukciai-is-jaunos-moters-isviliojo-25-tukst-euru) and [ELTA](https://www.lrt.lt/naujienos/sveikata/682/2454516/sukciai-sukure-i-e-sveikata-labai-panasu-puslapi-du-gyventojai-neteko-simtu-euru) Victims were scammed by Scammers using phone, phishing links, phishing (web) sites, scamming (web) sites.
```

```
##### R esults
Loss of Money.
Loss of Confidentiality.
Loss of Integrity.
Loss of Authenticity.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* High chance that look-a-like sites are used for phishing. Phishing sites are illegal service, that should be at least blocked.
* E.commerce and payments are not working & has to not work with less secure "http" protocol.
```

```
##### I ncident

According this Article [LRt.lt](https://www.lrt.lt/naujienos/sveikata/682/2455154/sukciai-ir-toliau-vagia-gyventoju-besijungianciu-prie-netikro-e-sveikata-portalo-pinigus) the same problem of look-a-like to esveikata web site existence persist.
```

```
##### R esults
Loss of Confidentiality.
Loss of Integrity.
Loss of Authenticity.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* The Article include link to NCSC Raport Site. Everyone who could find wherebouts of fake site could give a note for banning of fake service.
* No information regarding DNS service attacks, the Search Engines, e.g. Google, Yandex.. could provide phishing links through their SEO service.
* Software Application could not require for DNS protocol, so it could be more secure when you own authentic Software App.
```

```
##### I ncident

According this Article [swedbank.lt](https://www.swedbank.lt/business/useful/more/newsandblog/news) e.banking service gonna be unavailable for 4:30 hours.
```

```
##### R esults
Loss of Availability
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Planning is necessary for fluent Maintenance. When information about Maintenance changes, then News Agreggators has to send a reminder.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2456193/savaitgali-neveiks-vmi-sistemos) State Tax Inspectorate (VMI) is planning for a 28 hour Maintenance.
```

```
##### R esults
Loss of Availability
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* News Agreggators don't need to know too detailed technical details, so they would not create too detailed Article.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2456316/gera-dovana-patyre-sukciu-ataka-nukopijuota-akropolio-dovanu-korteliu-informacija) Authentication Mechanism of some Name Portal were breached and some Digital Gift Cards were stolen.
```

```
##### R esults
Loss of Confidentiality.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Credentials Data are Confidential and in most cases a Private Information, w/o permit brute-forcing Authentication Mechanisms are forbidden by Law. Citizens have to beware of phishing attacks that could include those Digital Gift Cards. 
* Authentication Mechanism needs to include safety-measure(s) that block malicious attacks. Companies has not allow to use small and non-random passwords in Authentication Mechanism. Reminders to change passwords has to be welcomed. 
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2456942/policijos-banko-darbuotojais-prisistate-sukciai-is-zmoniu-isviliojo-apie-24-tukst-euru) were reported few cases of actions by scammers. Posted situations:
* from scammers received phishing message, that contained phone contacts for their scamming schemes;
* an authentication to the web portal lead into unauthorized financial operation from a banking account;
* some cases when scammers pretend themselves as legitimate employees from a bank, police, that want to collect for authentication related data.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Confidentiality.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* For unregulated Cryptocurrency Market Person is left for his own, it's illegal.
* When e.service take money without providing accepted by user terms of use & w/o notification, it's illegal.
* Personal Identification Code could be used for authorization of some actions, awareness after loss of this information could be lacking.
* Authentication information is Confidential data and by giving this data to other Person there have to be legitimate interest through giving permit to represent that person. Systems like that could be a target by scammers too.
```

```
##### I ncident

According this check [esveikata.lt](https://www.esveikata.lt/duomenuSauga) provided information lacks of more visibility from e.service owner of commitment to keep "Privacy Policy" intact. According this check [esveikata.lt](https://www.esveikata.lt/slapukai) provided a Sample of Required Cookies as of "to Pay for Services" & ESPBI Information System Regulations include an "Aim" to create effective Payment Control System. There have to be a concern that Pharmacy Information Systems provide information to ESPBI Information System and send additional information like Payment Type. The Question: Why You collect data, that are not meant to pursue those Aims of ESPBI System? The Check was conducted of ESPBI (2021) & IPR (2023). According this check [esveikata.lt](https://www.esveikata.lt/) there could be found a Security Measure of "Content Security Policy" and privileges for e.Services from Tech Giants Alphabet and Microsoft. The Question: Does Attack Vector are plausible that somebody would be able to misuse of their Services by phishing message with usage of their Payment System(s)?
```

```
##### R esults
Plausible lacking of Professional Risk Assessments over System Data Types.
Data minimisation has to be taken more seriously (General Data Protection Reglament).
Highly probable that Clients and Customers does not get relevant information about Payments, Payment Types and they could be more easily fooled.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Data minimisation means collecting the minimum amount of personal data that you need to deliver an individual element of your service. Data minimisation does not mean that You have to smash the Data into even Smaller Particles or so.
* [esveikata.lt](https://www.esveikata.lt/) has some Page for awareness of Risks from scammers. A link of [esveikata.lt](https://www.esveikata.lt/duomenuSauga) provide idea of "Data Security" and "Privacy Policy" inconsistency. The Privacy Policy require to use Informational Structure of Data & Data Types that are related with Clients and Customers. Only then possible to move into "Data Security" & commitment of Data Protection. Assume even Doctor could be a Client, but that does not mean, that this Available Privacy Policy has to be made Universal for Doctors & Employees and Clients & Customers.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2458424/sukciautoja-apgavo-82-metu-senole-ir-isviliojo-daugiau-nei-13-6-tukst-euru) Elderly are scammed over a Phone.
```

```
##### R esults
Probable loss of Money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* All Lithuanian Phone Numbers are registered and every Person who use specific Phone Number are known. Don't answer from a calls of unknown Phone Numbers.
* Specific Phone Numbers are used for Marketing, no awareness training of risks regarding those Phone Numbers yet.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2458871/naujas-sukciavimo-budas-raso-per-feisbuka-apsimesdami-mobiliojo-rysio-operatoriais) exists NEW TREND in increase of Scams from behalf of Telecomunication company. 
```

```
##### R esults
Informational
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Law Enforcement has specific use of Social Media Accounts, e.g. Facebook, through [faecbook.com](https://www.facebook.com/records/login/) portal. The Facebook aquired "WhatsApp" and currently their Brand is the company "META" Platform that control all their e.services. At the example of the Facebook other platforms could own similar Portals for Law Enforcement.
* Now take an example of the Article [kauno.diena.lt](https://m.kauno.diena.lt/naujienos/lietuva/salies-pulsas/narkotiku-prekeiviai-telegrame-iesko-vaiku-talkininku-1179658), that show the Sample of illegal activity through a "Telegram" Social Media. The Social Media of "Telegram" are known of being the fishy platform with part of Community that conduct illegal activity, just like some electronic services, e.g. Onion services, that can only be accessed over Tor BROWSER. Through those services could happen non-minor amount of illegal activities, e.g. phishing, scamming, hacking, bullying, etc. One of a TREND has to be an ILLEGAL EMPLOYMENT. Person from various range of Age could be a Victim of this illegal EMPLOYMENT. This are illegal activity too. The Regulation and awareness of fake EMPLOYMENT has a huge concern by Country Officials. In some example, neighboring Countries for each other could make plausible illegal impact, that without (or in some cases even with) diplomatic relations are hard to fix. 
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2460518/sukciai-apgavo-dvi-moteris-ir-vyra-pasisavino-daugiau-nei-55-tukstancius-euru) people are scammed over "Messenger" Software App, Phone, Account of a Banking Institution.
```

```
##### R esults
Loss of Privacy
Loss of Confidentiality
Loss of Money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Don't take friendships at serious through Cyber Space Software App's like META's "Messenger" Software App, ref. [google.com](https://play.google.com/store/apps/details?id=com.facebook.orca&hl=lt&pli=1). In this Incident List "Messanger" Software App is mentioned for a second time.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/verslas/4/2461240/sutriko-sodros-veikla-dalis-paslaugu-gali-buti-laikinai-neprieinamos) some of Sodra's Social security services are Unavailable.
```

```
##### R esults
Loss of Availability.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* The Article does not include any whereabouts of plausible problems.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2466079/sukciai-ivairiose-salies-vietose-is-zmoniu-isviliojo-apie-45-tukst-euru) reported few scams that happened on this month and one financial fraud situation which lasted for whole four years.
```

```
##### R esults
Probable loss of Privacy
Probable loss of Confidentiality
Probable loss of Money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Scammers try to get victims trust and pretend themselves as legitimate employee of some Financial Institution or employee from Law Enforcement. More reads [lb.lt](https://www.lb.lt/lt/kaip-atpazinti-sukcius).
* Scammers operate through the Phone, Email & Internet Service(s). Lithuanian Bank include awareness training in Financial Education, more interactive content [youtube.com](https://www.youtube.com/watch?v=1cEOS5AzKFc&ab_channel=Lietuvosbankas).
* Web domain(s) could be controled by scammer(s) & for this reason there are suggested to stop using unknown (or not trusted) web sites, search engines, and to try out using Bookmark (or Favourite) that could keep actual link to Your trusted www Pages. WWW Browser has capability to Sync data, so beware to deploy WWW Browser with Personal & Private Account to Enterprise & Private Environment, because Bookmarks and security credentials gonna be Synced. Example of Bookmarks in leading Browser Solution [google.com](https://support.google.com/chrome/answer/188842).
* Financial Institution in usual way provide a Personal Client Page. In this Page a Client could find all commitments between Financial Institution & Client. For this reason Client have to know all depts that are linked to Client's Digital Entity. Exists e.Services who allows to keep important e.document(s), that are just like a Vault, so You could keep Your commitments until they are still active & actual. 
```

```
##### I ncident

According these Articles [ELTA](https://www.lrt.lt/naujienos/sveikata/682/2467336/sukciai-nusitaike-ir-i-portala-epacientas-lt) & [ELTA](https://www.lrt.lt/naujienos/sveikata/682/2467336/sukciai-nusitaike-ir-i-portala-e-pacientas-lt) scammers attacked Clients of ePacientas & e-Pacientas Software.
```

```
##### R esults
Probable loss of Privacy
Probable loss of Confidentiality
Probable loss of Money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Google Play Software Storage allow to access "ePacientas" Software App. This App has old fashioned Registration Way and access through entering electronic mail address and personal password of ePacientas Software Account. Digital Patient Data are linked with some Clinics where Customers could arrange a date with a doctor. Patient could manage his official prescriptions from doctors by itemized receipt, that could allow to get (through purchase) a Product from linked Pharmacy Entities. This Software App allow to search desired Products. ePacientas include a News section, an active waiting list to the Doctor(s). Software Application could be used by public Sector and private Sector Clinic(s). Developers declare that there are no 3rd party data sharing, but ePacientas may collect Personal info (Name, Email Address, User IDs, Address, Phone Number, Sex), Health and fitness info, Crash logs and Diagnostics info, Device or other IDs, In-app Messages.
* According Article e-Paciantas.lt got attack that could be something as a Cross-Site-Scripting. The Web Site shall be tested from popular risks like Top 10 from [owasp.org](https://owasp.org/www-project-top-ten/).
```

```
##### I ncident

According these Articles [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2468696/sukciai-vilniuje-ir-jonavoje-apgavo-gyventojus-isviliojo-tukstancius-euru) & [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2472242/sukciai-toliau-siaucia-apgauta-moteris-vilniuje-atidave-26-tukstancius-euru) scammers via telephone device(s) get hefty sum of money. Scammers pretend being pretty much as anybody who has authority to command their victims.
```

```
##### R esults
Probable loss of Privacy
Probable loss of Confidentiality
Probable loss of Money
```

```
##### I ncident

According this Article [lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2473883/itariama-kad-vilniaus-mokykla-patyre-programisiu-ataka-toks-ivykis-galejo-buti-ne-vienas) from one TAMO Account is spreading Cyberbullying actions. Suspected breach of TAMO Account from an outside of TAMO Server's Node was not confirmed.
New Article [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2478204/is-mokytojos-tamo-paskyros-zinute-paslovinusi-rusija-i-mokykla-skubejo-policija).
```

```
##### R esults
Loss of Privacy
Loss of Confidentiality
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* A Teacher is a hardworking person. He could leave and (or) forget to Sign Out from his Edu Account, that could be accessed by other's. This other entity at that time could spread misrepresentation stuff.
* From look of an Information Theory [encyclopediaofmath](https://encyclopediaofmath.org/wiki/Information_theory) data transmission, preservation, extraction and classification of Information & quality could be researched on. But usually those researches just could drop something as a Protection and (or) a Security.
* In this case specific fields of researches could be taken into an account, e.g. distance learning methods [snv.ch](https://www.snv.ch/en/academy/e-learning.html) for learning how to operate Information Technologies & Information Systems. System Security Representative could not be Available, because of Small & Medium level of an Institution, because of Datacenters, who are taking a job of Information Technology & Information System Architect, Developer, Maintainer, Operator & Security Representative and Data Protection Officer.
* Reports regarding Cyberbullying and "information of paedophilic or pornographic character or information inciting racial and ethnic hatred on the web" could be done (completed) in [svarusinternetas.lt](https://www.svarusinternetas.lt/en/report-illegal-content/2).
* New Article give a hint that Keylogger Virus&Malware could be present in System Computers. From the Article it looks like, that there was a Clickbait technique in use. 
```

```
##### I ncident

According these Articles [BNS](https://www.lrt.lt/naujienos/pasaulyje/6/2470254/svedija-sulaike-laiva-itariama-latviu-optinio-kabelio-baltijos-juroje-sabotazu) and [VZ](https://www.vz.lt/inovacijos/2025/01/27/baltijos-juroje-pazeistu-kabeliu-naudojasi-bites-grupe-562834) a LVRTC e.Services was interrupted, telecommunication and media company service "BITĖ" and "Bitė Lietuva" was using this service.
```

```
##### R esults
Loss of Availability of LVRTC e.Services.
Plausible loss of Availability of Bitė e.Services.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* The Article attaches previous similar News, so in this scope exists a Trend, that links in the end of the Article repeats & introduce what already were said from other Incident(s). It's not suggested to provide News in such Fashion. Some specialist could find comparision to Adware.
* Nowadays telecommunication companies provide tele phone service, mobile phone service, smart phone service, cell phone service, Voice over IP service, internet service, sattelite internet service. These Articles could be not so Innovative with a small visibility of a problem. Tech companies try to inform their Clients using their competitor service when something goes wrong with an Availability. 
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2474327/vilniuje-sukciai-is-zmoniu-isviliojo-apie-23-2-tukst-euru) happened Scams over a phone tech. 
```

```
##### R esults
Plausible loss of Availability
Plausible loss of Confidentiality
Plausible loss of Money
Plausible loss of Privacy
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Customer need for awareness training in situation when there are necessary actions for blocking his personal bank account.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/sveikata/682/2474063/medikas-piktinasi-e-sveikatos-trikdziais-gydytojai-turejo-dirbti-dviguba-kruvi) doctor's hate when developer's make their System updates w/o known schedule.
```

```
##### R esults
Loss of Money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Doctor's paperwork nowadays are huge with signatures, stamps & Medical prescriptions.
* Provided Statements: How System could operate, when You complete administration work of something and afterwards all of this data vanishes. Does other information will vanish too? Who's responsible? What to do?
* System's Information are kept in a Database. When someone want to upgrade this System, he has to update from specific point, that has relationships with Database. New Update could affect relationships in Data, so there would be needed proffesionals Devs that could manage updates & database schema upgrades. When update are developed for very long period of time, then this problem could even increase. In ethical occasion normal System's has ticketing feedback to report errors in the System, plausible even to provide Questions and Answers. Everything depends by policies of a System. Security Representative have to not allow to start any administration without periodical  and later on occasional training for how to use the System. When there are no Security Representative for Educating System's Personel or even maybe he don't even understand the System's itself, then quality of a service could deteriorate & etc. etc. I don't think that You could get professional System Representative in Public Sector, because of many factors. In other words this Article would not be posted at all. There is a TREND, that Professional Teams of Developers from Private Sector take hands on System Development and provide adequate Service. Public Sector join knowledge & Personel into Teams to work with Datacenters, so they could afford optimal professionality and cost. 
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2471594/numeris-banko-balsas-sukciaus-kaip-neapsigauti) Telecommunication Standards allows to change a Phone Number of a Caller and (or) a Name of a Caller, that has to be seen while receiving those calls. At this time Scammers gonna fool even more victims.
```

```
##### R esults
Risk: High.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* From the Article is plausible to come up with an idea, that a Phonebook of a Phone could be not enough for securing Your Numerlists.
* By taking whole considerations from the Article there have to be suggested to stop using any type of Phone as Authentication measure (e.g. for dials & calls and Short Message Services) and this have to be recommended by higher-ups.
* The Article include strange point, that old Lithuanian telecommunication number system 8-600-00000 looks a-like to Chinese +86-<...> number system. From the statement plausible to comme up with an idea that the Lithuania is the China. Resources: Phone number system of a China [wikipedia](https://pl.wikipedia.org/wiki/Chi%C5%84ska_Republika_Ludowa) with a calling code of +86 (mainland). Lithuanian phone number system [rrt](https://www.rrt.lt/rrt-ragina-vartotojus-buti-budriais-ir-neperskambinti-itartinais-telefono-rysio-numeriais/?highlight=telefono%20numeracija). Well known situation when from March of 2024 Year from the start positioned number eight has to be changed into a zero [rrt.lt](https://www.rrt.lt/telefono-rysys-internetas-tv/telefono-rysio-numeriai/numeriu-skyrimas/).
* Lithuania does not deploy security measure for a scammer banning in a telecommunication level. While on the Internet Security [nksc.lt](https://www.nksc.lt/pranesti.html) National Cyber Security Center under the Ministry of Defence accepts phishing Reports of an URL. Single URL Report could stop phishing for whole population, if security related counter-measures are in it's place.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2477073/sukciai-apsimete-pareigunais-banko-darbuotojais-is-zmoniu-isviliojo-apie-60-tukst-euru) Scammers:
* phish their victims by cosplaying as someone else;
* phish with misinformation for Money Transfer & Financial Requests;
* phish using Social Media's functionality - adverstments;
* phish physical Objects from their victims.
```

```
##### R esults
Plausible loss of Confidentiality
Plausible loss of Money
Plausible loss of Privacy
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Before starting using some service and electronic service Clients have to read Terms of Use, Privacy Policy and get to know, if the lended Object belong to him and he has right to share it.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2480115/del-serveriu-perkelimo-savaitgali-nebus-pasiekiamos-vmi-sistemos) State Tax Inspectorate (VMI) is planning for a 36 hour Maintenance.
```

```
##### R esults
Loss of Availability
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2482383/sukciau-toliau-siaucia-vilniaus-apskrityje-pasisavino-beveik-35-tukst-euru) scammers use telecommunication means to scam people. Scammers pretend themselves as being one from law enforcement forces, banking & investment brokers.
```

```
##### R esults
Plausible loss of Money
Plausible loss of Confidentiality
Plausible loss of Privacy
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* It's strange that Law Enforcement Officer could scam for passwords of Banking e.service. Minimal requirement for banking e.services include the need for use of the 2FA. If there are no 2FA in banking e.service, then there are a scamming place.
* Password is not the same as Passphrase. Personal Identification Number (PIN) is not a Password either. The Article lacks of Terms and Abbrevations for an explanation.
* The Phone Number is needed in a situation to know the Name of Telecommunication Company & Entity Number, that provide Services to a Phone Owner by online tool [rrt.lt](https://numeracija.rrt.lt/savitarna/user/#/number).
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/verslas/4/2485698/paysera-patyre-kibernetine-ataka-sutriko-imones-paslaugos) e.services of banking company "Paysera" are under Distributed Denial of Service attacks. 

```

```
##### R esults
Limited Availability
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2485764/vmi-perspeja-laikinai-nebus-pasiekiama-elektroninio-deklaravimo-sistema) e.System of the State Tax Inspectorate (VMI) is under Maintenance.
```

```
##### R esults
Loss of Availability
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2486116/sukciai-apsimete-policijos-tele2-ir-banko-darbuotojais-isviliojo-37-8-tukst-euru) scammers over the telephone fooled victims to make actions when they don't even have any rights for it.
```

```
##### R esults
Plausible loss of Money
Plausible loss of Confidentiality
Plausible loss of Privacy
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* From these events plausible to note about issues in communications. Software Products could be constructed or changed on transfer in a way that could hold phishing capabilities, e.g. swapping device's camera's video & audio with something else, so persons who gets a telephone call could be more sloppy during conversation to trust their abusers. Phishing technological capabilities should not exists & in this way, developers and their "pay-for-what-you-want" technologies make a colossal damage.
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2487683/slaptu-jav-kariskiu-duomenu-skandalo-epicentre-mazai-zinoma-lietuviu-imone) Lithuanian Company Entity Code 300619315 leak Client's data.
```

```
##### R esults
Plausible loss of Confidentiality
Plausible loss of Privacy
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* In the Article Company's background are Digital Marketing Services. Other Sources provide idea about Internet services & offerings of Telecommunication, Communication Products. Does Company has got Cybersecurity Incident, that wasn't detected?
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2481728/valstybines-imones-painioja-el-svetaines-konfidenciali-informacija-keliauja-ne-ten) exist loophole into mistaking defined System Name with Web domain, that could even not belong to the System Owners.
```

```
##### R esults
Loss of Confidentiality
Loss of Privacy
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* System's usualy has Common Statements Document & in this document actual domain name has to be provided.
* How System's Administrator starts working with a System without training from a Security Representative of a System? Common questions, documentation & procedures could be provided through Distance Technologies too, e.g. Teams, Skype, Zoom... Software Products & When there exists Systems, that goes through Accreditation, e.g. [NKSC](https://www.nksc.lt/akreditacija.html), they could use their own Solutions or purchase Available ones, that meet all requirements. This could be something as a Black Chamber of [simonsingh.net](https://simonsingh.net/The_Black_Chamber/) and based on defined policy, e.g. [europa.eu](https://lithuania.representation.ec.europa.eu/europos-komisijos-vaizdo-stebejimo-politika_lt).
* People with the same First Name and Last Name could be mistaken, e.g. f.last_name@domain.com, first_name.last_name@domain.com. PGP/GPG Keys could be mistaken or even could go through evil middle-man.  
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2490772/vilniaus-ir-kauno-apskrityse-sukciai-is-zmoniu-isviliojo-18-5-tukst-euru) Scammers scams through telecommunication Technologies using (smart) Telephones.
```

```
##### R esults
Plausible loss of Confidentiality
Plausible loss of Privacy
Plausible loss of Money
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2490533/klaipedos-teismas-ispeja-apie-jo-vardu-prisistatancius-sukcius) phishing attacks possibly reach Lithuanian Court's Clients and (or) People who does not have anything in common. Phishing Messages contain links to look-a-like Sites of the Court's site.
```

```
##### R esults
Plausible loss of Confidentiality
Plausible loss of Privacy
Plausible loss of Money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Court portals of Republic of Lithuania uses unified domain "teismai.lt". In Exception (according References of the given Site in the Article): Court of Appeal of Lithuania (www.apeliacinis.lt), Supreme Administrative Court of Lithuania (www.lvat.lt), Supreme Court of Lithuania (www.lat.lt), Constitutional Court of the Republic of Lithuania (lrkt.lt). Section of References provide information about trusted Sites. 
* The Article provide idea, that Court does not ask for Confidential information like Passwords (OWASP attribute Passwords with Secrets).
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2492740/sukciai-is-zmoniu-vilniuje-utenoje-ir-rokiskyje-isviliojo-beveik-45-tukst-euru) Scammers scams through telecommunication Technologies using (smart) Telephones.
```

```
##### R esults
Plausible loss of Confidentiality
Plausible loss of Privacy
Plausible loss of Money
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/verslas/4/2494112/del-kibernetines-atakos-sutriko-payseros-veikla) Financial Institution PAYSERA are getting DDoS attacks.
More references:
* [@BNS](https://www.lrt.lt/naujienos/verslas/4/2494488/atstatyta-kibernetine-ataka-patyrusios-paysera-veikla).
```

```
##### R esults

Plausible loss of Availability.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* The Article include information, that DDoS were produced by sophisticated Computer Engineers. From Year of 2021, the NCSC has some information & competence how to deal with DDoS'es [nksc.lt](https://www.nksc.lt/doc/biuleteniai/2021-11-05_DDoS.pdf). 
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2493646/vilniete-ftb-agentu-prisistaciusiam-sukciui-per-pusmeti-atidave-30-tukst-euru) Lithuanian's are scammed by People who pretend as being an Officer from non-Lithuania. For that they use Software Applications, e.g. "WhatsApp".
```

```
##### R esults
Plausible loss of Confidentiality
Plausible loss of Privacy
Plausible loss of Money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Exists a Trend, that soon there will be not only Foreigner Officers, but somebody from Army & Military. When Media are getting bombarded by related Information, then self-Educated pretenders arise.
```

```
##### I ncident

According this Article [LRT|TV](https://www.lrt.lt/mediateka/irasas/2000393584/vilnieciai-viesajame-transporte-susiduria-su-beda-komposteris-netycia-nuskaito-pinigus) Computer Device for payments could process a Payment from longer distance when this usually are not needed.
```

```
##### R esults
Loss of Money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* There could be multiple Connectivity Technologies & one, that similarly were used in older Lithuanian COVID Software Application's.
* Products, e.g. [ebay.com](https://www.ebay.com/sch/i.html?_nkw=blocking+aluminum+alloy+wallet&_sacat=0&_from=R40) & [temu.com](https://www.temu.com/ul/kuiper/un2.html?_p_rfs=1&subj=un-search-web&_p_jump_id=960&_x_vst_scene=adg&search_key=card%20holders%20wallets) could be taken into Account when protecting Your Asset(s).
```

```
##### I ncident

According these Articles [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2497221/itin-skaudus-praradimas-vilniaus-rajone-sukcius-is-moters-isviliojo-100-tukst-euru) and [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2500141/sukciai-vilniuje-kaune-marijampoleje-ir-jurbarko-r-is-zmoniu-isviliojo-133-tukst-euru) Scammers scams through telecommunication Technologies, Internet-based Portals, Messaging Software using (smart) Telephones and other Computer Devices.
```

```
##### R esults
Plausible loss of Confidentiality
Plausible loss of Privacy
Plausible loss of Money
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2500527/nvsc-per-klaida-nutekinti-dalies-sirgusiuju-infekcinemis-ligomis-duomenys) the Instituion had published online File in their Web Site with Confidential & Private Data. Availability of following information: Personal Identification Number (Personal code), some Phone Numbers, Home Address, Work Address, Education Institution's Name, Diagnosis of found Disease, some data about person's criminal history. 
```

```
##### R esults
Plausible loss of Confidentiality
Plausible loss of Privacy
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* The Article provide a good sample of Cyber Incident. This could be a Sample of Broken Spreadsheet, when multiple people make changes & share of a single File.
* Making Web Sites as File Graveyards are a weak use of a Web Technology, but an available option.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2501158/sukciai-vilniuje-panevezyje-ir-klaipedoje-is-zmoniu-isviliojo-apie-52-tukst-euru) Scammers conduct Scams through Telecommunication Technologies & pretends themselves as Employees of known Company or Institution.
```

```
##### R esults
Plausible loss of Confidentiality
Plausible loss of Privacy
Plausible loss of Money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* The Article include statement, that Police has assigned following case as a Robbery.
* From Year of 2001 European Union made commitment in combating (computer) fraud and counterfeiting of non-cash means of payments [europa.eu](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32001F0413). Given samples of Payment Instruments, that has to be taken into Account: Credit Cards, EuroCheque Cards, other Cards issued by Financial Institutions, specific Cheques and Bills of Exchange. Cooperation between Member States are the Key for solving cases when scams are conducted by citizens from the European Union.
* The next Article [ojb.gov](https://www.ojp.gov/library/publications/learning-context-and-other-race-effect-strategies-improving-face-recognition) builds system for Eyewitnesses with the idea of improving Face Recognition Technology. Mug Shots, Photo Robots, Fingerprints could be taken into Account.
* Communication through Digital Products could have own Flaws. Products, that support scamming, e.g. to change Person's face directly, to include another layer with other Person's face or to hide it w/o notice, must be taken through awareness training & usability of these Products has to be discouraged. Manufacturers must ensure, that their Products could have less chance to be used by a scammer.
```

```
##### I ncident

According these Articles [ELTA](https://www.lrt.lt/naujienos/verslas/4/2502894/vilniaus-imone-sukciams-pervede-102-tukst-euru) & [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2505094/sukciu-grobis-is-gyventoju-ivairiose-lietuvos-vietose-isviliojo-apie-147-tukst-euru) & [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2504783/plinta-laiskai-del-tariamu-lrt-autoriniu-teisiu-pazeidimu) scammer request for payment was approved & completed by an accountant of Industrial Organization & in Phishing cases a unknown Malware Software were used to grab Confidential Information. 
```

```
##### R esults
Loss of Confidentiality
Loss of Money
Loss of Privacy
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* State Tax Inspectorate Site include (provide as a Service) required templates for Payments. This means, that both entities does not met all of those requirements.
```

```
##### I ncident

According these Articles [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2515354/sukciai-toliau-siaucia-is-triju-zmoniu-isviliojo-beveik-60-tukst-euru) and [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2517751/bites-salono-darbuotoju-apsimetes-sukcius-isviliojo-30-tukst-euru) people get scammed over Internet and (or) Telecommunications.
```

```
##### R esults
Plausible loss of Confidentiality
Plausible loss of Privacy
Plausible loss of Money
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* When Software Application has Vulnerabilities, they are disclosed like usually, e.g. [whatsapp.com](https://www.whatsapp.com/security/advisories/2023/) and [mitre.org](https://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=whatsapp).
* CryptoCurrency investments according Lithuanian Bank are risky.
* Every Citizen has to own Bank Account and keep & get their Salary to it. Pretty much no other ways. Scams by pretending as some kind of an officer from Police, an employee of Bank Institution has to be rare situation.
* Lack of Digital literacy is more common problem in 3rd Grade Countries.
* Client's Knowledge of Goods and Services could prevent plausible scams, e.g. Does Solar Power Plant gonna be sold by Telecommunication Company? 
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2517407/aptiko-saugumo-spraga-pildyk-vartotojai-kortelemis-galejo-naudotis-ju-neuzregistrave) Telecommunication company had problems in their Network's Configuration.
```

```
##### R esults
Misconfiguration.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2518544/nauji-sukciavimo-atvejai-is-gyventoju-isviliojo-daugiau-nei-30-tukst-euru) Scammers attack Clients of Investment platforms on the Internet.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
```

```
##### I ncident

According this Article's [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2518620/pagd-pasiruosimo-ekstremalioms-situacijoms-svetaineje-kibernetinis-incidentas) first paragraph — some vulnerable Link was detected & removed from LT72.lt Site.
```

```
##### R esults
Probable Defacement of the Site.
Loss of Access Countrol.
```

```
##### I ncident

According these Articles [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2522460/vilniaus-birzu-ir-anyksciu-apylinkese-sukciai-isviliojo-apie-220-tukst-euru) and [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2523594/visagine-sukciai-is-moters-isviliojo-126-tukst-euru) Scammers attack Clients of Investment platforms on the Internet. Scammers know how to use Telecommunications for fooling their victims. Anti-scammers operations to build more centralized & non-slow Network for National Security Protection.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
```

```
##### I ncident

According this Article [ELTA&LRT.lt](https://www.lrt.lt/naujienos/sveikata/682/2526510/sutriko-e-sveikatos-sistemos-veikla) System of e.Sveikata is not Available for Clients & for Privileged Users of this System. 
```

```
##### R esults
Loss of Availability
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* System could be designed in a way, that typical data could be available in the offline mode. In a situation in return of connectivity data could be synced for new updates. Short term changes in the System are impossible.
```

```
##### I ncident

According this Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2526792/vilniuje-sukciai-is-gyventoju-isviliojo-bene-30-tukst-euru) scammers attack their victims using telecommunicaition means and by pretending themselves as Officials.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
```

```
##### I ncident

According following check [-](https://github.com/PolVilniusTech/public.incident.reporting.timeline.md/blob/main/Lithuania/Images/2025-04-05%20TRAFI.LT%20Gateway%20Timeout.PNG) the attempt failed for accessing the Web Service Trafi.lt.
```

```
##### R esults
Loss of Availability
```

```
##### I ncident

According following Articles in down-bellow happened high amount of scamming cases. Impersonation & Unauthorized retrieval of Credentials. Investment Fraud. Phishing. Fake official site or official site with malware. Fake e.shop's basket. Skimming & unprivileged access to information system. SMART-ID scam. "Messenger" scams:
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2528705/sukciai-vilnieti-ikalbejo-parduoti-buta-is-kauniecio-isviliojo-beveik-40-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2527818/sukciu-siautejimas-vilniete-neteko-163-tukst-euru-paneveziete-itikinta-parduoti-buta);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2529679/sukciai-ivairiais-budais-is-zmoniu-isviliojo-apie-60-5-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2529983/laimetas-konkursas-virto-nuostoliais-sukciai-is-vilnietes-isviliojo-23-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2534570/sukciai-is-zmoniu-apgaule-isviliojo-apie-55-6-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2535680/sukciai-is-vyro-vilniaus-rajone-isviliojo-13-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2540024/sukciai-nesnaudzia-siauliu-ir-kedainiu-gyventojai-prarado-beveik-27-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2544959/sukciai-nemiega-apsimesdami-prokuroru-ir-giminaite-is-senjoru-isviliojo-52-5-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2546039/sukciai-vel-pasidarbavo-gyventojai-neteko-beveik-95-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2550076/sukciai-is-vilniaus-ir-siauliu-rajono-gyventoju-isviliojo-35-tukst-euru).
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
```

```
##### I ncident

According this Article [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2550561/testuojant-gyventoju-perspejimo-sistema-trumpam-sutriko-lrt-lt-veikla) for short duration of time legitimate users could not access the Website of lrt.lt. 
```

```
##### R esults
Limited loss of Availability
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2548068/i-lietuva-patekti-norinciu-uzsienieciu-mulkinimas-pavogtas-zinomas-vardas-ir-nuotraukos) Company, that is registred in Republic of Lithuania [registrucentras.lt](https://www.registrucentras.lt/jar/p/index.php?kod=305854580&a=4570&p=1) are fooling foreigners by providing e.service, that should help make easier imigration to the Country. Registered domain name of this Company is different from official registered Company Name. Registered domain name of this Company is mimicking other name of known Organisation. Company's website include company & employee artificialy generated & False information. Employees Section of this website include random people from Web, that has no official relation to this Company & include False information. An email address of this Site does not respond to requests.  
```

```
##### R esults
A web source for impersonation and phishing attacks.
```

```
##### I ncident

Following Articles are related to a Scam:
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2555680/sukciai-is-vilnietes-is-vilnietes-isviliojo-beveik-30-tukst-euru) scammers are using telecommunicaition means to fool their victim;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2557765/sukciai-per-kelias-dienas-is-lietuvos-gyventoju-saskaitu-susizere-per-100-tukst-euru) scammers are using telecommunicaition means, impersonation & conduct retrieval of confidential data, flawed investment platform;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2558722/sukciai-vel-padare-dideliu-nuostoliu-gyventojams-isviliojo-per-96-tukst-euru) scammers are using dating software apps, telecommunicaition means, impersonation & conduct retrieval of confidential data, phishing over e-mail, impersonation & connecting to computer through distance administration software apps, fraud attacks & plausible a fake website for phishing. 
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
```

```
##### I ncident
According the Article [ELTA](https://www.lrt.lt/naujienos/svietimas/45/2560873/plagiato-tikrinimo-sistema-naudojusiu-studentu-duomenys-galimai-atsidure-jav-serveriuose) exists risks for data leakage, incl. privacy data, from widely used Plagiarism checker.
```

```
##### R esults
Plausible loss of Privacy.
Plausible loss of Confidentiality.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Plagiarism checkers, e.g. [Grammarly](https://www.grammarly.com/plagiarism-checker), [Plag](https://www.plag.lt/), [TurnitIn](https://www.turnitin.com/) provide service for comparing uploaded document with already existing document in their Database. Improperly secured legal environment could mean a plausible loss of Content, that are available in these documents, e.g. Business Information, Personal Information like Plain Passwords to some test environment(s), etc. With a costless or payless Service this data could have more uncertainty future. Willingly given data could be used as Service Owner would see fit of that.
* Simple rule: Does there are trustworthy system to check Your password security? What, if upon a try, this password gonna be retrieved & used by third parties. 
```

```
##### I ncident

According the Article [BNS](https://www.lrt.lt/naujienos/verslas/4/2560855/sutriko-registru-centro-veikla-istaiga-negali-aptarnauti-klientu) legal entity [registrucentras.lt](https://www.registrucentras.lt/) and it's e.services are unavailable.
```

```
##### R esults
Loss of Availability
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Article does not point out, that all services, that depend by [registrucentras.lt](https://www.registrucentras.lt/) system could be an unavailable.
```

```
##### I ncident

According Articles [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2564465/salcininku-rajone-ir-klaipedoje-sukciai-is-zmoniu-isviliojo-apie-48-5-tukst-euru), [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2564465/sukciai-is-zmoniu-ivairiais-budais-isviliojo-apie-65-8-tukst-euru), [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2565336/sukciai-is-gyventoju-isviliojo-per-70-tukst-euru) & [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2569154/sukciai-vilniuje-is-senjoriu-isviliojo-apie-9-tukst-euru) scammers are using telecommunicaition means, impersonation, investment fraud, phishing & look-a-like sites, e-mail service to fool their victims.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Driver's accident tricks of scammers could be prevented: call for (Road) Police to fill accident documents.
* There could exists other Privacy related issues when Drivers are mounting webcams on their Vehicles & don't use anonymization tools while disclosing information in their Social Media, other public Cyber Space. Scammers could use this information for searching of their Targets.
* Site [vmi.lt](https://www.vmi.lt/evmi/?lang=en) has machine translated content for foreign languages. It expects, that all translations are perfect.
```

```
##### I ncident
According the Article [LRT.lt](https://www.lrt.lt/naujienos/sveikata/682/2564771/buvusi-birzu-chirurga-papiktino-ligonineje-irengtos-vaizdo-kameros-sios-net-operacineje) the Hospital w/o consent does technological video surveillance.
```

```
##### R esults
Loss of Privacy
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Employess & Clients should be informed regarding video surveillance. Does exists possibility to reject consent of this type of surveillance?
```

```
##### I ncident

According following Articles scammers are using telecommunicaition means, Social Engineering, impersonation, investment fraud, agreement fraud, phishing & (crypto) investment platforms, internet platforms, social media & services to fool their victims:
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2570620/sukciai-ivairiais-budais-is-zmoniu-apgaule-isviliojo-apie-190-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2571681/sukciai-is-triju-moteru-isviliojo-apie-23-3-tukst-euru);
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2573024/praejusia-para-virtine-nusikaltimu-sukciai-is-gyventoju-isviliojo-tukstancius-euru);
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2575020/sukciai-is-keturiu-gyventoju-isviliojo-per-120-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2577593/sukciai-nesnaudzia-per-treciadieni-is-zmoniu-isviliojo-apie-106-8-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2578099/sukciai-auku-ieskojo-pokalbiu-programeleje-telegram-ir-apsimete-policininkais);
* [ELTA&BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2578964/keturi-zmones-policijai-pranese-apgaule-prarade-per-247-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2580647/sukciai-toliau-siaucia-is-zmoniu-isviliojo-beveik-110-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2581568/klaipedoje-ir-vilniuje-sukciai-isviliojo-55-4-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2583599/vilniuje-sulaikytas-telefoninis-sukcius-bandes-isvilioti-14-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2586037/grigiskese-is-moters-isvilioti-10-tukst-euru);
* [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/nusikaltimai_ir_nelaimes/sukciai-is-zmoniu-apgaule-isviliojo-apie-1025-tukst);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2588650/sukciai-apgavo-salcininku-ir-kedainiu-gyventojus-pasisavino-23-5-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2589546/sukciai-pinigus-viliojo-apsimesdami-policininkais-prokurorais-elektros-tinklu-atstovais);
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2592126/per-para-lietuvoje-astuoni-stambesni-sukciavimo-atvejai);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2594414/sukciai-prisistate-advokatais-banko-darbuotojais-isviliojo-apie-64-7-tukst-euru) <a name="2025-2594414-1"></a>;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2594414/sukciai-prisistate-advokatais-banko-darbuotojais-is-zmoniu-isviliojo-75-7-tukst-euru) <a name="2025-2594414-2"></a>;
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2594905/is-keturiu-gyventoju-sukciai-isviliojo-beveik-24-tukst-euru).
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* When scamming are profitable, then exists trend for (World-wide) teaching facilities to make more scamming schemes. The Scamming is a Business. [LRT](https://www.lrt.lt/naujienos/lietuvoje/2/2560803/sukciavimo-epidemija-lietuvoje-aferistai-ruosiami-specialiuose-mokymo-centruose-uzsienyje). This is very similar as Phishing Campaigns through Web Systems.
* Persons are needed for possibility to link correct (or good) e.shops with their e.Portals. There could be expectations from [registrucentras.lt](https://www.registrucentras.lt/), because they offer public information about legal persons & entities. If Scam could happen easily and Clients does not get legal protection as they shall get that, then as result could be included: loss of trust.
* By taking into Account this Article [LRT.lt](https://www.lrt.lt/naujienos/pasaulyje/6/2579108/japonijos-kova-su-sukciais-dirbtinis-intelektas-pokalbiu-analize-ir-itartini-numeriai) there could be suggested: to find locations where money are scammed at most cases and to conduct an information campaign; to build mobile phones with simple call recording capabilities (a.k.a. how often distance applications are used for recording Internet Conferences? Data Security over this?); Software Application, that checks Mobile Phone Number in Database of known Scammers; More International Cooperation in dealing with Scammers; Analysis of a call with Automated Mechanisms & Machine Learning Stuff (usually most of operating systems include some level of "virtual assistant" capability, but their functionality in legal situation kind a limited and (or) narrow as chat-bot, subscribing, purchase-of-tickets..., so there would be needed for more to security & data protection related functionality).
* The awareness material, e.g. [EUROPOL](https://www.europol.europa.eu/sites/default/files/documents/lt_0.pdf), how effective they are? 4th Page of previous PDF Sample (EUROPOL) has idea of "Saugokitės reklamų, siūlančių neįtikimas kainas ar stebuklingus gaminius. Jei pasiūlymas skamba per daug gerai, kad būtų tiesa, greičiausiai taip ir yra!". In some regard an usual Innovation Company produce a lil better Product (Software & Hardware incl. Firmware). What, if You will not get a security updates anymore or system can't upgrade? so everyone has to update & upgrade to latest Products even when they don't need a new glitter. When previous Product and new one are not compatible, then require replacement & that's the cost of Innovations. If these Products does not require rare Materials?
* Telecommunication companies, that Communication Technologies are used for Scams, tend to make free of charge contribution and assistance with awareness training for most vulnerable persons.
* According pair of links [ELTA](#2025-2594414-2) and [ELTA](#2025-2594414-1) it's possible to notice, that Media's Framework leave past Articles (not updated), so there a lot of similar Content of the same Situation(s). For Integrity reasons it's OK. But, that leaves risk of Misinformation, data duplication occurrences are for much greater extend, then Web Storage are wasted. Some Medias include CO2 emission calculator(s), that suggest to make responsible Searches. In Concludion: most Impactful e.Scamming could be linked with eco-Terror.
```

```
##### I ncident

According the Article [ELTA](https://www.lrt.lt/naujienos/verslas/4/2597895/sukciai-is-imones-pasisavino-daugiau-nei-68-tukst-euru) a fake site was used for grabbing Confidential, Private Information and unintended Money loss.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Modern Bank Sites already are using "content-security-policy" to provide list of trusted sites & everything else by Browsers should be treated as not similarly trusted. Without automation exists high chance of manual intervention for grabbing Confidential Codes and using them as fast as possible. For this reason, there could be noticeable a strange delay between of operations, but the article does not include any details. Automation by linking actions from a Server to the Browser are not a hard task & a lot of Companies & Businesses use that.
* Financial Institutions does not change their Visual Design very often & when they do that, then exists high chance for them to change their own Name of Company, so Clients could easily adapt to a new Style and everything what goes together. A Regular Design change could be misused by Scammers too, so exists need for stopping & evading registration of look-a-like domain, that are very similar to a name of Financial Institution. Extending Browser with possibility of knowing Country and (or) Member State position of Site could help to be more aware to whom Server a victim is connecting. The Article does not explain similarity of phishing domain.
* Fake Software Application could be created for the same consequences, but in this way a malware Software would be present in victims device. Analysis of Software Application should be Available.
```

```
##### I ncident

According the Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2598382/sukciai-ivairiais-budais-apgaule-is-zmoniu-isviliojo-apie-73-8-tukst-euru) scammers are using investment of Cryptocurrency, impersonation, telecommunication means, fake web site with mobile signature authentication.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* In usual way various telecommunication calls using mobile phone already has direct cost to the user who is calling. Telecommunication calls to specific numbers could be more costly, but in this case, a common service, that is operating such number shall inform caller about used higher cost of a call, than usual one.
* First big paragraph of the Article is not informative enough. By description, a Person did investment into Cryptocurrencies, but there are provided no following information how those scammers fooled him. By investing into Cryptocurrency, that Person accepted all risks for described investment, where are scamming?
* Second bigger paragraph provide idea, that Person were scammed by something as a Team of debt collectors. There are no public awareness training regarding such situation.
* Last bigger paragraph provide idea, that technology of Mobile Signature is targeted by scammers. The Article provide no information about possibilities, that mobile signature tech are vulnerable. When YES, then who affected (entity or whole infrastructure)?
```

```
##### I ncident

According the Article [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2598890/is-klaipediecio-sukciai-isviliojo-30-tukst-euru-is-dar-dvieju-gyventoju-po-9-tukst) person was fooled for completing investment through the Internet.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Exists a trend, that Scammers by getting Personal Information could use it for sending Parcels through self-parcel Service. In this occasion the Person gonna be trapped into countering fake or even dangerious Presents & some of them require for Pay first and Goods as second. Term of Investment must be more clear.
* Second problem for electronic Space, that People just can't handle their Passwords, Passcodes, PINs or whatever, that should be 100% Confidential, e.g. [ve.lt](https://ve.lt/kriminalai/suzinojo-elementariausio-neatsargumo-kaina-piktavaliams-pin-kodo-spelioti-nereikejo).
* Something as simple as "Prohibiting instant removal of email messages from email box" (Electronic Mail Service) at some point could prevent unnoticed Phishing campaigns over hacked Accounts. Complete take over of Service could be still vulnerable, but by giving at least three day period to review previous discarded email messages could make the Internet more trusted space around.
```

```
##### I ncident

According the Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2600184/is-neringos-imones-sukciai-pasisavino-pinigus) exists illegal way of Company's Money transfer from one Bank account to another one w/o CFO & CEO approval. Scammers conduct Money stealing campaigns with help of Telecommunication & Internet Tech.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
```

```
##### I ncident

According the Article [15min](https://www.15min.lt/verslas/naujiena/mokslas-it/nepatogumai-swedbank-vartotojams-prie-elektroniniu-valdzios-vartu-neprisijungsite-1290-2481256) for 2 hours and 5 minutes Authentication to External Services mechanism of Bank Swedbank was unavailable.
```

```
##### R esults
Loss of Availability
```

```
##### I ncident

According the Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2601240/sauliu-vadas-siulo-drausti-tiktok-ir-telegram-pralaimime-informacine-kova-su-rusija) Lithuanian Media has Comment Section(s), that constantly are used by automated Phishing campaigns with so called "Bots".
```

```
##### R esults
Loss of Integrity
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* At some point, from initial start of this Incident Report Blog, no media aggregator made a statement about Bot(s), who attack Media's Infrastructure with generative bias content.
* Exists security countermeasure, that is constructed as mathematical puzzle to counter automation of Bot(s). Pretty decent one has the Search Engine of Baidu Search & not bad one - Google's re-Captcha.
* The Article include the Term "Cyber partisan", that is attributed to the Military Field.

```

```
##### I ncident

According following Articles scammers use telecommunication means, impersonation, phishing attacks, fake site(s) (incl. who accept private citizen's authentication measures), investment platform site(s), site banners to fool their victims:
* [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/nusikaltimai_ir_nelaimes/sukciai-siauliuose-taurages-klaipedos-ir-panevezio-apskrityje-is-zmoniu-isviliojo-apie-275-tukst-euru/);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2604629/is-dvieju-moteru-sukciai-isviliojo-beveik-69-tukst-euru)
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2605093/vilnietis-sukciams-atidave-19-5-tukst-euru-klaipedietis-16-tukst);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2605576/alytuje-sukciai-is-moters-isviliojo-apie-38-3-tukst-euru);
* [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2605654/nkvc-170-facebook-reklamu-skirtu-lietuvos-vartotojams-naudojamos-sukciavimo-schemose).

```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
Plausible loss of Integrity.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* In Lithuania no caller are usually talking in english language, so either there are no trust should be given for foreign language - russian language.
* Article of the LRT.lt provide triple purpose meaning by representing hundred seventy banners, e.g. 1) "unknown origin", 2) "manipulation over sensitive topics", 3) "using Lithuanian public" figures who are "deepfaked". The Article contain wibe of manipulation over sensitive topic too & the results does not provide enough evidence of scams. The unknown origin from itself by default does not contain a negative meaning, unless you tend to use approach: block everything for everyone and allow only according of somebody decision, that shall be well-known. Adverstments are usualy dealt by Cybersecurity tools & bias to attach it into malicious-negative perspective are left by entities themselves. Article does not question how to know, if some public person are "deepfaked", that when some person does not use inappropriate service for doing what he is doing, e.g. to Tag Content as Deepfake & w/o doing so, that public person could own all rights to shut down that content. When scammer reports are accepted by virtual patrol of Police, then analysis could be provided by him too.
* Deepfakes regarding media shall be plausible to report using contacts at the bottom of this site [zeit.lt](https://zeit.lt/en/legal-information/259).
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
##### I ncident

According following Articles scammers use telecommunication means, an investment platforms, cryptocurrency, impersonation techniques and direct access requests, romantic scam, phishing offers through purchased site accounts, phishing sites, published content online,  a dating site, a social engineering, a lottery scam with a fake phishing site to fool their victims:
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2605981/sirvintose-sukciai-is-moters-isviliojo-daugiau-nei-25-tukst-euru);
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2606392/sukciai-is-gyventoju-isviliojo-beveik-145-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2612079/kelmes-rajone-ir-klaipedos-apskrityje-sukciai-is-zmoniu-isviliojo-apie-6-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2624023/sukciai-is-vyro-isviliojo-45-tukst-euru-itikino-investuoti-i-internetine-platforma);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2627078/pajuryje-policija-sulaike-pinigu-paimti-atejusi-sukciu-sake-kad-dukte-pateko-i-avarija);
* [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2627412/venipak-ispeja-apie-suaktyvejusius-sukcius-nespauskite-nuorodu);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2630110/sukciai-sostineje-ir-klaipedos-savivaldybeje-is-zmoniu-isviliojo-22-4-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/verslas/4/2630126/sukciu-grupe-kaltinama-del-net-215-nusikaltimu-skelbdavo-apie-neva-parduodamas-prekes);
* [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/nusikaltimai_ir_nelaimes/rusiskai-kalbejes-sukcius-is-nemencines-gyventojos-isviliojo-pinigus/);
* [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/nusikaltimai_ir_nelaimes/sukciai-is-klaipedietes-isviliojo-banko-kortele-su-pin-kodu-ir-pasisavino-pinigus/);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2635069/senjore-tapo-romantiniu-sukciu-auka-susipazinusi-per-programele-neteko-10-tukst-euru);
* [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/nusikaltimai_ir_nelaimes/visagine-sukciai-is-moters-isviliojo-15-tukst-euru/);
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2638041/sukciai-is-vyro-vilniuje-isviliojo-per-49-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2639041/vilniuje-sukciai-is-moters-isviliojo-beveik-60-tukst-euru).
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
Plausible loss of Integrity.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2606521/i-sukciu-tinklus-ikliuna-vis-daugiau-zmoniu-siulo-bankams-priskirti-daugiau-atsakomybes) provide idea of liability according financial institution's responsibilities for a compensation to the victims.
* 2011 Year Statistics [gov.lt](https://osp.stat.gov.lt/statistikos-leidiniu-katalogas?publication=22) show, that Russians consist only about 5-6 percent of full Demography of Lithuania. Scams demoralize small minority of people of the Lithuania when Articles explicitly extract scam situations of used the russian language only. In number of Years telecommunication services are slacking and skipping Anti-scam counter-measures, e.g. informing origin country and region of a dealer's call.
* Companies need to provide Hostnames from where Clients must wait for legit messages and communication ways.
```

```
##### I ncident

According the following Article [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2640193/sutriko-tele2-veikla-priezastys-aiskinamos) telecommunication company TELE2 has interruptions of their service(s).
```

```
##### R esults
Loss of Availability
```

```
##### I ncident

According the following Article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2643055/sukciai-is-keturiu-salies-gyventoju-isviliojo-apie-65-4-tukst-euru) person made his investment into unknown investment accounts, scammers made impersonations to victims and succeeded in their scams.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
Plausible loss of Integrity.
```

```
##### I ncident

According the following Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2643558/buvo-sutrikusi-sistemos-enotaras-veikla-gyventojai-negalejo-gauti-paslaugu-nuotoliu) Notary Services System "eNotaras" can't be reached. Notary Services System undergo change of Internet Service Provider.
```

```
##### R esults
Loss of Availability
```

```
##### I ncident

According the following Article [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2635297/ispejama-apie-sukcius-kurie-dengiasi-zinomais-lrt-vardais) in social media were found video & audio clips, that are made by scammers and who are impersonating as LRT News service (Press). 
```

```
##### R esults
Loss of Money.
Loss of Privacy.
Loss of Integrity.
```

```
##### I ncident

According the following Article [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2649063/sukciai-is-gyventoju-isviliojo-beveik-50-tukst-euru) russian speaking scammers are using "Whats App" Software App and could make successful scams, russian speaking scammers are impersonating as employees of a telecommunication company, police forces, a bank organisation and make successful scams.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
Plausible loss of Integrity.
```

```
##### I ncident

According the following Article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2650467/buvo-sutrikusi-swedbank-programeles-ir-interneto-banko-veikla) Software App and Internet Bank of "Swedbank" Bank lost communications for full period of 10 minutes.
```

```
##### R esults
Loss of Availability
```

```
##### I ncident

According following Articles scammers use impersonation of Automobile parking service & conduct phishing attacks, sending short messages with malicious job offers, make requests to take multiple malicious loans, use distance computer control software to make malicious investment, make impersonation as telecommunication and bank and police employees & in some cases speak in russian language, requests to make crypto-investments or other type of investments, request by need of getting back invested money to make 2nd-hand investment, make a breach to a bank account and successfuly transfer money & fool their victims, conduct disinformation initiative over impersonated account:
* [BNS](https://www.lrt.lt/naujienos/verslas/4/2651838/unipark-ispeja-vairuotojus-apie-sukciu-siunciamas-melagingas-zinutes-imones-vardu);
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2653066/kaune-sukciai-is-jauno-vyro-isviliojo-30-tukstanciu-euru);
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2655078/sukciai-is-vilniecio-isviliojo-235-tukst-euru);
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2656073/sukciai-is-gyventoju-isviliojo-62-5-tukst-euru);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2658174/sukciai-is-gyventoju-pasisavino-beveik-75-tukst-euru);
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2659034/grigiskese-ir-panevezyje-sukciai-is-dvieju-moteru-isviliojo-23-tukst-euru);
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2660061/sukciai-is-triju-zmoniu-isviliojo-beveik-12-tukst-euru);
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2661561/patarejas-apie-adamkaus-mirti-skelbianti-ruginienes-x-paskyra-suklastota).
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
Plausible loss of Integrity.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* the Lithuania does not have more than one type of citizenship, so only Lithuanian citizenship justice are legal.
* Russian speaking people are minority in the Lithuania & E.U. does not have any Country, that make russian language one of E.U. language.
* Software Applications, that allow distance control of Device are increasing. There could be need of secure default settings and better computer proficiency & knowledge in using that in correct way.
* Lithuanian Constitution give enough rights for private life, so not all people just know their rights and defend them. The top management could be skipping these Rights as in business centric countries. Labor union(s) could be lacking, so employees rights could be damaged already.
* The first ELTA Article from top provide idea, that Lithuania Cybersecurity Regulation accept Banking operations with something as simple as a Password. This just can't be called a Bank & bellow of that as a Savings Institution? Big Tech has a trend, that provide Authentication with not only requirement of a single & simple password. The used option of second e-mail address can't reach level of 2nd Factor Authentication.
```

```
##### I ncident

According the following Article [LRT.lt,BNS](https://www.lrt.lt/naujienos/verslas/4/2663803/sutriko-atsiskaitymai-kortelemis-su-problemomis-susiduria-keliu-banku-klientai) pair of financial organisations has irregular and faulty card payment services. Hardware who are issued by those banking companies could be inaccessible.
```

```
##### R esults
Loss of Availability
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Each entity, that gets banking services from financial organisation could need to update their specific & unique firmware. At situations like this each entity require to update their Hardware for service to be functional.
```

```
##### I ncident

Following articles are related to scammers:
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2666074/sukciai-is-gyventoju-isviliojo-77-tukst-euru-apsimete-policijos-banko-darbuotojais) - social engineering (impersonation) using mobile phone and stealing victim's financial asset, credentials to an Internet banking account;
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2667031/lietuvoje-per-para-is-gyventoju-isvilioti-40-tukst-euru) - social engineering (impersonation) using mobile phone and stealing victim's financial assets, credentials to an Internet banking account;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2669166/zarasu-rajone-is-moters-sukciai-isviliojo-27-7-tukst-euru) - investment scam (cryptocurrency);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2670115/is-vyro-banko-saskaitos-pasisavinta-daugiau-negu-27-tukst-euru) - loss of money by use of victim's financial asset (last year). Successful hacking into Internet banking account through financial phishing attack & stealing victim's financial assets;
* [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2675725/maxima-perspeja-apie-netikrus-imones-vardu-rengiamus-konkursus) - scammers using social media impersonate popular brand, conduct phishing attacks and try to steal private information from their victims;
* [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2676042/sukciai-kone-masiskai-atakavo-gyventojus-po-skambuciu-tukstanciai-prarastu-euru) - social engineering (impersonation) using mobile phone and stealing victims' financial assets, credentials to an e.Banking account;
* [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/nusikaltimai_ir_nelaimes/naujojoje-akmeneje-sukcius-is-senjoro-isviliojo-beveik-35-tukst-euru/) - scammers & social engineering (impersonation) using mobile phone;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2679355/alytuje-vilniuje-ir-kaune-sukciai-is-zmoniu-isviliojo-apie-24-1-tukst-euru) - scammers use targeted phishing for catching their victim into making one-way investment through investment e.platform. Phishing using short text message through telecommunication means, that re-directs into scamming site. Through mobile phone scammer made an impersonation, that lead into losing financial assets for a victim;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2686094/sukciai-is-triju-sostines-gyventoju-apgaule-isviliojo-apie-107-tukst-euru) - scammers pretend themselves as real estate agents, fund investment agents using internet platform, that accept money in cash, social engineering (impersonation) using mobile phone;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2690196/rusiskai-ir-angliskai-kalbeje-sukciai-is-triju-moteru-isviliojo-apie-85-5-tukst-euru) - scammers use non-national tongue, does impersonation and social engineering & racketeering, steals victim's account's e.credentials of financial e.site;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2691150/rusiskai-ir-lietuviskai-kalbeje-sukciai-is-vilnietes-isviliojo-21-5-tukst-euru) - multiple of scammers complete impersonation and social engineering through unknown software and hardware (mobile phone);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2693106/rusiskai-su-klaipedieciu-bendrave-sukciai-isviliojo-kortele-ir-isgrynino-15-2-tukst-euru) - scammers use, does impersonation and social engineering through telecommunication means, exists chance, that they could hold some knowledge as how to hack A.T.M.s;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2695026/vilniuje-sukciai-is-senjores-isviliojo-17-5-tukst-euru) - scammers using telecommunication means brainwashed their victim into handing money, during communication non-national tongue was used;
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2697075/sukciai-is-sostines-gyventoju-isviliojo-daugiau-nei-55-tukst-euru) - scammers deploy vishing attack, foreign tongue, impersonation and social engineering, investment platform as their toolset for stealing financial assest(s);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2699058/visagino-gyventojas-sukciams-pervede-beveik-40-tukst-euru) - scammers use telecommunication means;
* [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2701062/nesutramdomas-sukciu-siautejimas-vos-per-para-gyventojai-jiems-atidave-118-tukst-euru) scammers use telecommunication means, impersonation, deploy vishing attacks, foreign tongue, offers job per website, their activity are increased from usual level;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2704063/sukciai-is-visagino-gyventojos-isviliojo-32-tukst-euru) scammers deploy vishing attacks, foreign tongue through impersonation & telecommunication means;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2705102/sukciai-apgavo-pora-klaipedoje-ir-pasisavino-85-tukst-euru) scammers deploy vishing attacks, foreign tongue through impersonation & telecommunication means;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2707092/rusiskai-kalbeje-sukciai-is-vilniecio-isviliojo-31-tukst-euru) scammers deploy vishing attacks, foreign tongue through impersonation & telecommunication means, phishing links & social engineering to initiate unknown payment, loans through unknown e.site, financial institution(s);
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2709138/sostineje-vilniaus-rajone-ir-kupiskyje-sukciai-is-zmoniu-isviliojo-apie-22-8-tukst-euru) scammers use impersonation & telecommunication means, deploy vishing attacks, foreign tongue, (manually and (or) automatically) sends phishing links through Ad Portal.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
Plausible loss of Integrity.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Idea, that russian speaking telecommunication and police & bank employees could racket out money from people could only link to corrupted employees. In this case scenario it's strange, that everyone turning a blind eye, that something like that are allowed in the country. Understanding a foreign language is not a feat at all & not many moved persons to the Lithuania try to learn a new language.
* For corrupted scammers who works or pretend as working in legal entity could be placed sanctions, that forbid their working career, e.g. computer hacker who made a huge cybersecurity incident has got forbidden to use an Internet.
* Exists financial [ombudsman](https://www.britannica.com/topic/ombudsman) who are investigating citizens’ complaints of bureaucratic abuse, so those impersonators could be checked more in detail.
* Exists new trend of refunding scammed money, so financial institutions could implement more strict countermeasures for protecting financial asset(s).
* Risk Management could provide ideas, that scammers could use pretext by stealing money from bank accounts of their victims & in most cases of given roles are not related to official privilege of a "debt collector".
* The Phishing attack in some percentage could be stopped by NCSC DNS Firewall [nksc.lt](https://www.nksc.lt/irankiai.html). E.g. Web users must learn how to make secure configuration of their Web Broswer [nksc.lt](https://www.nksc.lt/uzkarda.html). Moodle type e.learning platform, that does not request for e.payment(s), could add awareness training against scamming, that could be found in the same Site [nksc.lt](https://www.nksc.lt/mokymai/).
* Law Enforcement could need for a better legislation especially for electronic stuff (incl. Software & Hardware), that include not only Networks & Systems, use of Cyberspace, but of course, the Hardware too.
* Tiny bit of suggestions could be found in here [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2619051/specialistas-patare-kaip-elgtis-jeigu-tapote-sukciu-auka).
```

```
##### I ncident

Following article [Lrytas.lt](https://www.lrytas.lt/it/ismanyk/2025/10/13/news/vienu-metu-sutriko-bent-dvieju-lietuvos-aukstuju-mokyklu-interneto-svetaines-39899923) describe, that Web Services of two Higher Education Schools are unavailable.
```

```
##### R esults
Loss of Availability.
```

```
##### I ncident

According following Article [ELTA](https://www.lrt.lt/naujienos/verslas/4/2715453/unipark-ispeja-apie-sukciu-siunciamas-sms-zinutes) exists Unipark's "suspected" & "in question" web site, that pretends as being Unipark's asset. Plausibly the asset is used in SMS Scam.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Integrity.
Plausible loss of Authenticity.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Unipark's Web portal got data leak in 2024. The data could be used in phishing attacks.
* Registration of Domain Name requires for Personal Data & dealing with created phishing site has to be taken care of by e.police.
```

```
##### I ncident

Following articles are related to scammers:
* [ELTA](https://lnk.lt/straipsniai/kriminalai/sukciai-is-zmoniu-isviliojo-50-tukst-euru/340118) scammers use targeted phishing links, financial phishing site and (or) vulnerable financial web site, conduct vishing attacks, foreign tongue, impersonation using telecommunication means;
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2716094/is-triju-vilnieciu-sukciai-isviliojo-per-42-tukst-euru) scammers use, probably, financial phishing site, conduct vishing attacks, foreign tongue, impersonation using telecommunication means, physically go to their victim private property;
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2717033/is-kaunietes-sukciai-isviliojo-per-30-tukst-euru) scammers deploy vishing attacks, foreign tongue through impersonation & telecommunication means.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
Plausible loss of Integrity.
```

```
##### I ncident

According this [-](https://www.lrt.lt/naujienos/verslas/4/2719124/kas-perka-jusu-skaitmenine-praeiti-lietuvos-startuolis-tiriamas-del-duomenu-prekybos) Lithuanian Startup has started to personalize personal (private) data out of Internet through public access only. Startup has issues with the Privacy compliance when person's can't decide of opt-out.
```

```
##### R esults
Loss of Compliance.
Loss of Privacy.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Number of services like this does not collect anything by default. Start-up yet could be on research and test phase.
* Usually after properly completed identification & authentication person's could request to search for their data around the Web. Residual risk are related to illegal indexing of private information by fake identification & authentication..
```

```
##### I ncident

According following articles scammers are mentioned: 
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2721119/sukciautoja-itikino-kauniete-paimti-beveik-23-tukst-euru-paskolu) scammer use telecommunication means, deploy vishing attack, foreign tongue, victim by himself use e.platforms for taking out loans for unknown purposes.
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2723080/vilniuje-ir-taurageje-sukciai-is-dvieju-zmoniu-isviliojo-17-6-tukst-euru) unwanted investment through unknown e.investment platform.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
Plausible loss of Integrity.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Scamming are one of main reasons of crime in 2024 [ELTA](https://www.elta.lt/lt/pranesimai-spaudai/europos-reikalu-komitete-pristatytos-eurojusto-ir-europolo-2024-m-veiklos-ataskaitos-258806), when scammers join in organized crime groups, that are looking for ways to entangle their victims into doing actions, that result in an undesirable consequences. One of highest problematic groups are those, that known too well whole legislational and jurisdictional kitchen.
* Public News of scamming are not fully open for public in the web-site of www.elta.lt.
```

```
##### I ncident

According Article [BNS](https://www.lrt.lt/naujienos/verslas/4/2723415/reddit-duomenu-rinkimo-ieskinys-ir-lietuviu-imonei-oxylabs) company Oxylabs automatically collected information from the Social Media "Reddit" w/o taking in consideration terms of use/terms of service.
```

```
##### R esults
Loss of Confidentiality.
Loss of Privacy.
```

```
##### I ncident

According following article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2725048/sukciai-is-vilniaus-klaipedos-ir-panevezio-gyventoju-isviliojo-virs-50-tukst-euru) scammers use telecommunication means and (or) fake e.mail address, deploy vishing attack, phishing attack, impersonation, foreign tongue, victim by himself personally hand his own assets.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
Plausible loss of Integrity.
```

```
##### I ncident

According following article [ELTA](https://www.lrt.lt/naujienos/verslas/4/2727284/buvo-sutrikusios-luminor-banko-elektronines-paslaugos) financial institution "Luminor" got limited access to an internet bank and a software application & a call center was unavailable. 
```

```
##### R esults
Loss of Availability.
```

```
##### I ncident

According following article [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2727142/vilniuje-buvo-sutrikes-elektros-tiekimas-su-trikdziais-susidure-21-tukst-vilnieciu) numerous quantity of citizen had no electricity, ten traffic light signals was out of order. Status of electricity in the Lithuania could be looked at the online source [eso.lt](https://www.eso.lt/atjungimai-planiniai-neplaniniai).
```

```
##### R esults
Loss of Availability.
```

```
##### I ncident

According following articles:
* [LRT.lt](https://www.lrt.lt/naujienos/verslas/4/2727116/neuzkibkite-ant-sukciu-kabliuko-prisidenge-draudiko-vardu-siulo-pelninga-darba) social media are used by scammers to offer Advertisements for online only activity in behalf of Lithuanian company "Lietuvos draudimas";
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2728045/sukciai-is-zmoniu-isviliojo-apie-47-tukst-euru) scammers deploy vishing attacks, foreign tongue through impersonation & telecommunication means; fraud attack using physical financial asset; robbing attack with unknown circumstances from electronic Bank Account;
* [ELTA](https://www.lrt.lt/naujienos/verslas/4/2728159/lietuvos-pastas-ispeja-gyventojus-jo-vardu-siunciamos-apgaulingos-sms-zinutes) telecommunications are used by scammers to send Short Message Service with text, that deploy imitation of "AB Lietuvos paštas". Completion of malicious request could result in loss of unique personal identity code, financial asset's information... Scammers know-how how to display text instead of telephone number;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2729127/sukciai-is-zmoniu-ir-imones-isviliojo-apie-80-tukst-euru) scammers deploy look alike pharming sites, that allow electronic payments; get unauthorized access to financial bank account; deploy vishing attacks, foreign tongue through impersonation & telecommunication means; use social engineering through software app "Messenger" & grab confidential information from their victim;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2730063/lietuviskai-ir-rusiskai-kalbeje-sukciai-is-klaipediecio-isviliojo-19-7-tukst-euru) scammers deploy vishing attacks, foreign tongue through impersonation & telecommunication means;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2731022/rusiskai-kalbeje-sukciai-is-triju-zmoniu-isviliojo-105-5-tukst-euru) scammers deploy vishing attacks, foreign tongue through impersonation & telecommunication means.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
Plausible loss of Integrity.
```

```
##### I ncident

According following article [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2731138/lrtk-uzblokavo-tris-naujas-piratines-filmu-svetaines-kopijas) exists redirected versions of banned web sites. Redirected web sources must be banned. Full list of banned web sites could be found in here [rtk.lt](https://www.rtk.lt/lt/atviri-duomenys/interneto-svetaines-kuriose-pazeidziamos-autoriu-teises). Banned web sites, that approve international sanctions could be found in here [rtk.lt](https://www.rtk.lt/lt/atviri-duomenys/ribojimai-susije-su-tarptautiniu-sankciju-igyvendinimu).
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
Loss of Integrity.
Loss of Authenticity.
```

```
##### I ncident

According following articles:
* [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2732051/is-keturiu-zmoniu-sukciai-isviliojo-per-21-tukst-euru) scammers use telecommunication means, deploy vishing attack, impersonation, foreign tongue, targeted phishing and (or) fraud attack via social media's computer or mobile phone software app, pharming site;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2735032/sukciai-pasisavino-tukstancius-siusdami-fiktyvias-nuorodas-apsimesdami-bankininkais) scammers use telecommunication means, deploy vishing attack, impersonation, foreign tongue, targeted phishing, fake employment, fake delivery, man-in-the-middle & "Smart ID" (and (or) pharming site);
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2737035/gyventojai-sukciams-atidave-ir-12-tukst-ir-beveik-30-tukst-euru) scammers target elderly, use telecommunication means, deploy vishing attack, impersonation, foreign tongue, deploy fake financial site for pharming sensitive data, phishing & fake ads;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2738031/sukciai-pinigus-isviliojo-melagingai-skelbdami-apie-greita-uzdarbi-fiktyvius-fondus) scammers mass produce stored content with malicious articles, that contain phishing links for the way of earning money, activation of phishing links allows to set up a communication, that result in money loss, deploy vishing attack, foreign tongue, the fake donation & pharming site for withdrawing not approved amount of money & w/o clear consent for that amount.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
Plausible loss of Integrity.
```

```
##### I ncident

According following article [LRT.lt](https://www.lrt.lt/naujienos/sveikata/682/2738061/prasideda-dideles-apimties-e-sveikatos-naujinimai-ka-svarbu-zinoti-pacientams) information system e.sveikata has upcoming update, so during this update their system gonna be unavailable.
```

```
##### R esults
Loss of availability for 6-8 hours.
```

```
##### I ncident

According following articles information system e.sveikata are not fully functional, does not have proffesional developers, it could not service their clients & it have a lot of interruptions & hangups:
* [LRT.lt](https://www.lrt.lt/naujienos/sveikata/682/2741424/registru-centras-atsipraso-del-e-sveikatos-trikdziu-ieskome-tikslios-priezasties);
* [LRT.lt](https://www.lrt.lt/naujienos/sveikata/682/2747147/4-milijonus-per-metus-kainuojancia-sistema-valdyti-nera-profesionalu);
* [LRT.lt](https://www.lrt.lt/naujienos/sveikata/682/2750220/ir-vel-stringa-e-sveikata);
* [LRT.lt](https://www.lrt.lt/naujienos/sveikata/682/2751410/registru-centras-e-sveikatos-trikdziai-gali-testis-iki-kaledu).
```

```
##### R esults
Partial loss of availability.
Increased risk for information security, cybersecurity and privacy protection.
```

```
##### I ncident

According following articles:
* [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/nusikaltimai_ir_nelaimes/sukciai-vilniuje-isviliojo-daugiau-nei-364-tukst-euru/) scammers use telecommunication means, deploy vishing attack, foreign tongue, impersonation, pretexting, mobile phone links which withdrawn more than 25 thousand euros;
* [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/nusikaltimai_ir_nelaimes/alytuje-ir-vilniuje-sukciai-is-zmoniu-isviliojo-117-tukst-euru/) scammers target elderly, use telecommunication means, impersonation, victim by himself try to use fake financial account;
* [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/nusikaltimai_ir_nelaimes/sukciu-grobis-vilniete-atidave-per-66-tukst-euru-klaipediete---65-tukst-euru/) scammers target elderly, use telecommunication means, deploy vishing attack, foreign tongue, impersonation, failed authentication to the financial bank account resulted loss of 65 thousand euros;
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2742023/sukciai-is-dvieju-gyventoju-isviliojo-po-65-tukst-euru) scammers target elderly, use telecommunication means, deploy vishing attack, impersonation, hacking, financial organization through e.system permit to withdrawn more than 65 thousand euros;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2743037/sukciai-is-telegram-per-tris-menesius-is-moters-isviliojo-per-25-tukst-euru) scammers deploy romantic scam & investment scam through social media, use telecommunication means, vishing attack, foreign tongue, impersonation, malicious advertisements, unknown way of grabbing physical asset (& credentials) to retrieve financial assets;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2744029/rusiskai-kalbeje-sukciai-is-panevezio-senjores-isviliojo-30-tukst-euru) scammers target elderly, use telecommunication means, deploy vishing attack, foreign tongue, impersonation, social engineering, probable decoy website & cross-site request forgery attack, actions w/o a trace;
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2745030/is-keturiu-zmoniu-sukciai-isviliojo-71-6-tukst-euru) scammers target elderly, use telecommunication means, deploy vishing attack, social engineering, (e-)credential grabbing, the fake financial & pharming site for withdrawing money & w/o clear consent for that amount;
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2746033/sukciams-vel-pavyko-isvilioti-tukstancius-euru) scammers mostly target elderly, use telecommunication means, deploy vishing attack, impersonation, social engineering, (e-)credential grabbing, the fake financial & pharming site for withdrawing money & w/o clear consent for that amount;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2750022/sukciai-is-pabrades-gyventojo-isviliojo-13-tukst-euru) scammers high chance, that deploy skimming devices, use telecommunication means, deploy vishing attack, impersonation, social engineering, make offers of fake employment. 
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
Plausible loss of Integrity.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Security Researchers [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2745171/ka-sukciai-daro-su-nutekintais-duomenimis-ir-ka-daryti-jei-jus-apgavo) suggests to begin using virtual cards, single use cards of a financial institution to decrease chance of direct threat to official bank account. Responsible communication with official financial institution, that is responsible for official "what you have" asset, could help to solve uncertainty of a client.
```

```
##### I ncident

According following articles a lot of web sites was unavailable & got interruptions, because of "Cloudflare" issues:
* [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2749238/kas-yra-svetainiu-sutrikimus-sukeles-cloudflare-ir-ar-ivykis-susijes-su-spalio-incidentu);
* [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2749353/lrt-trumpai-kodel-neveike-naujienu-portalai-bei-kitos-interneto-svetaines).
```

```
##### R esults
Partial loss of availability.
```

```
##### I ncident

According following articles:
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2752040/sostineje-ir-svencioniu-rajone-sukciai-is-zmoniu-isviliojo-apie-37-2-tukst-euru) scammers has usual locations as their hot spots. At this point scammers use telecommunication means, deploy vishing attack, foreign tongue, impersonation, social engineering, fake web site with online authenticator;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2755052/klaipediete-pranese-apie-vasara-ids-jos-isviliotus-12-3-tukst-euru) scammers deploy advertisements, that are used for gaining contacts for their social engineering attacks, deploy vishing attack, foreign tongue, investment scam;
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2761017/sukciai-is-gyventoju-per-para-isviliojo-per-30-tukst-euru) scammers by just using telecommunication means, deploy vishing attack, foreign tongue, impersonation;
* [ELTA](https://www.lrt.lt/naujienos/lietuvoje/2/2763047/sukciai-is-sostines-ir-mazeikiu-rajono-gyventoju-isviliojo-beveik-13-tukst-euru)  scammers use telecommunication means, impersonation, pharming sites (incl. Man-in-the-Middle), financial asset robbing or skimming attack, social engineering, withdrawn financial assests w/o owners' consent;
* [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/2764019/sukciai-is-dvieju-sostines-gyventoju-isviliojo-daugiau-kaip-25-tukst-euru) scammers use telecommunication means, impersonation, deploy vishing attack, foreign tongue;
* [ELTA](https://www.respublika.lt/lt/naujienos/lietuva/nusikaltimai_ir_nelaimes/sukciai-is-keturiu-salies-gyventoju-isviliojo-534-tukst-euru) scammers use telecommunication means, impersonation, deploy vishing attack, foreign tongue, investment scam over social media;
* [Verslo žinios](https://www.vz.lt/ziniasklaida/2025/12/02/a-valujaviciaus-ir-verslo-ziniu-vardais-bando-pasinaudoti-sukciai-siekia-isvilioti-pinigus-577556) official site of "Verslo žinios" does not trust ziniosverslo.lt website. This website could pretend itself as official site of "Verslo žinios" when in reality they are not. "Verslo žinios" is a registered trademark in red and white colors and should not be used w/o consent of "Verslo žinios". "Verslo žinios" has found a fake & forged news and try to inform their readers about scammers.
```

```
##### R esults
Plausible loss of Money.
Plausible loss of Privacy.
Plausible loss of Confidentiality.
Plausible loss of Integrity.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Financial Institutions as usual must enumerate their Customer Sites and prohibid use of their Authenticator by unknown Entity Sites.
* Professional Social Media Services must deploy security measures against advertisements of scamming.
* According [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/2763086/ijungus-nauja-apsauga-operatoriai-kas-savaite-sustabdo-apie-0-5-mln-sukciu-skambuciu) exists commitment for communication regarding use of legal and technical counter-scam measures, more clear registration and usability rules for SIM cards, improved data exchange between organizations and law enforcement.
```

```
