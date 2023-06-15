### References for the Research:
* site-check.cert.lt
* https://www.nksc.lt/tikrinti.html
* https://www.cert.orange.pl/aktualnosci/raport-cert-orange-polska-za-2020-rok 6-13 p.

### 2016

##### I ncident

According [@lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/151146/vrk-rinkejo-puslapis-bus-isjungtas-kol-bus-pasalintos-gresmes) temporarily were shut down „Voter Page“ Portal (following — System), because security gap has been found. Reported the Central Electoral Commission (following — VRK, engl. lang. CEC).
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
* Define what kind of information should be available for the User of the System;
* Review Identification & Authentication & Authorization Mechanismus;
* Question of Documentation and Specification understanding and clarity from Client/Requestor perspective;
* Question of Documentation and Specification understanding and clarity from Contractor/Company perspective.

```

```
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
* Check if Servers Ethernet interface needs upgrade into latest fiber-optic Ethernet. 
* Distributing Resources and aligning to the Server capability at serving the Customers.
* Look for cache capability for speeding up processes.
```

```
##### I ncident

According [@Delfi.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/188552/antradieni-ryte-buvo-sutrikusi-dalis-telia-paslaugu) there was a disruption to the operation of „Telia“ platform for sending the SMS. Partly because of this „Ežys“ web site didn't work either.
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
* [DNS Lookup Service](https://dnschecker.org/)
* [About DNS and it's configuration on Windows, Mac, Ubuntu](https://dnschecker.org/dns-articles/how-dns-works-how-to-find-dns-of-your-pc.html)
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
* Check functionality and test out the Configuration of the System.
* Check legal documents and ensure that System are tested for Governance Compliance.
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
* Documents, with misinformation for sharing data to the third party does not always are correct, because the Person, who Approves could misunderstood on some points, so more "checkboxes" for vital points have to be checked.
* Limit access to the Authentication mechanism for the external Entities and Users. 
* Answer to the Question(s): Does there should be History related information of All/Many/Some the Clients accessible for some User Account? If yes, then what were the Impact to the Company, if such data would be lost?
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
*  in Country, where exists democratic order, subjects from non-democratic country should abide the order. Sharing Private data in this case would lead into the consequences to the non-democratic Government, who are requesting the data from the subject.
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
*  ease availability of the functionality, which You are Searching, in the Start should be valued the same as Phishing attack.
*  functionality providers has to persuade their Users that they are working in specific country and order, which would help to see the possible consequences of using such Service.
*  conducting Risk analysis to the Data of the Application would easily show the possible consequences.
*  control of functionality of the system should be distributed into different roles with to role aligned privileges.
*  organisational and technical control, documentation/legislation are required for sending or leaving notice(s) of unknown and uncontrollable access to the system and it's Data. Integrity of such information should be preserved.
```

```
### 2021

##### I ncident

According [@Lrt.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1349079/kada-tiksliai-buvo-pavogti-citybee-klientu-duomenys-atsakymas-gali-lemti-20-mln-euru-bauda) more than 100 thousand Clients of the Automobile sharing Service „CityBee“ got notified about Anonymous intruders who disclosed their private information. 
More references:
* [@Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/1553145/del-nutekejusiu-duomenu-110-tukst-euru-bauda-citybee-valdanciai-prime-leasing)
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
*   There should be Way to privide the proof of the (e-)Service legitimity, i.e. for local Business certificates: [VMI.lt](https://www.vmi.lt/cms/verslo-liudijimu-duomenu-tikrinimas1).
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
* To retrieve goods anyone could identify themselves by providing name, surname, e-mail address.
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
*  Regularly Install Security Patches and Use Security Scan Tool from Official Site of the [cert.lt](https://site-check.cert.lt/).
   
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
* If the Client owns the Device of the e-Service, then it should be a way to try and enforce 2 (two-way) Authentication for selected dangerious operations. 
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
##### I ncident

According [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/1467245/bandyta-surengti-kibernetine-ataka-pries-uzsienio-reikalu-ministerija) and LRT TV () in Darknet Site is possible to purchase leaked public electronic mail-box of the Ministry of Foreign Affairs of Republic of Lithuania (following — Ministry). Ministry not provided any real useful comments on this event.

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
* Proper Security checks were not implemented during Design and Prototyping.
* System were not tested manually for dangerious possible User Input of the System.
* Automated tools lacks functionality to test out from different User Roles perspective, because mostly Automated tools don't know or can't be Configured to find out, what these Roles should be able to do or what they should see.       
```

```
##### I ncident

According [BNS](https://www.lrt.lt/naujienos/lietuvoje/2/1538042/buhaltere-ikliuvo-i-sukciu-pinkles-o-prienu-savivaldybes-istaiga-neteko-daugiau-nei-35-tukst-euru) Article  some Employee of the Institution got fabricated e-mail with the Request from Director of this Institution. 
```

```
##### R esults 
The Request of the Director were completed successfully. 
The Director denies that the Request were sended by him.
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
* The European Computer Driving Licence (ECDL) should help to know more about Devices and how to use them Safely. Citizens should get backup from Country Government, so more Citizens would have easier access and would know how to operate during extreme Events and Incidents.
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

According [-](https://www.lrt.lt/naujienos/lietuvoje/2/1628142/simasius-skelbia-atsaukiamas-leidimas-didziajam-seimos-gynimo-marsui-stabdys-yandex-veikla-vilniuje) more and more Services are Closed in the Country which are providing e-Services.

More sources:
* [@Lrt.lt](https://www.lrt.lt/naujienos/eismas/7/1629105/minske-maziau-pavezeju-bolt-traukiasi-is-baltarusijos)
* [-](https://www.lrt.lt/naujienos/verslas/4/1627182/aibe-stabdo-rusisku-ir-baltarusisku-prekiu-tiekima-ukrainai-skirs-100-tukst-euru)
* [-](https://www.lrt.lt/naujienos/verslas/4/1625935/pigu-lt-nutraukia-prekyba-rusiskomis-ir-baltarusiskomis-prekemis)
* [-](https://www.lrt.lt/naujienos/verslas/4/1626204/lietuvos-pastas-stabdo-rusisku-ir-baltarusisku-prekiu-bei-leidiniu-platinima)
* [-](https://www.lrt.lt/naujienos/verslas/4/1626363/ekoagros-stabdo-veikla-rusijoje-ir-baltarusijoje)

```

```
##### R esults 
Less pluralism with the Entities-States which Operates more or less by 1% rules and 99% obeys of Political form.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
*    Something is wrong with Geopolitical situation when half of people shout about Ukraine: Crisis and other half - (non-international) War. 
*    High chance of Puppet regimes to Puppet individuals who are easily used of to do something unethical.
*    Nowadays most of Discussions happen in the Internet.
*    Only Internet won't help to the Physical Security of the Country, so there would be needed to increase spending to the Security of all ranges to the 5 GDP.
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
* signing with e-signature, e-stamp and (or) using e.document system with public view would give better proof of the events, which should or should not happen.
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
* If people lack of Knowledge, then they could be given some time to Learn Stuff including specific Rules, Policies and Legislations for specific Job. Periodical check-up of new updates and full Active document would be needed to take into the consideration. Usually such checks are made for Practice on First-Aid and Fire Protection knowledge and actions check-up.
* Conducting Risk Assessment on various organisational Risks is First for Organisations with High Profit and In Huge countity of Personnel. Smaller Organisations could not catch up with Risk Assessment and Management.    
```

```
##### I ncident

According [-](https://www.lrt.lt/en/news-in-english/19/1658475/fearing-russia-threat-germans-cancel-trips-to-lithuania-s-neringa) described events, which looks like that someone fears for the Incident like in Islands of the Japanese people.
```

```
##### R esults 
People don't travel near the border with the Bully.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Bullying is the same problem as Cyberbullying in the Internet.
* If someone does their Idealogy by stepping in someones turf only for that to make his Borders disputible and not integral to the Laws (and maybe specific ones), which requires 100% of Border Integrity, then such places would have serious consequences from the Stronger Side. Maybe not in instant fashion but in longer period of time, when they get back the Chance.
* Grabbing land by small pieces is nothing new, J.G.Caesar had his phrase, which well known for that. Normally it looks like unfaithful person, who pick ups around him on his wishes, but without any consent from other side. For first try to deal with that with the Phrase: "Shame on You!".
* Building more secure demilitarized area with border patrol would be way to go. And would need create rotation of personel from Defence Forces and Other personel who has right to hold a Weapon-Gun in his hands. Usually Health checkup for these People are more Strict than regulars-citizens-commoners who would not step up on the different side of the border by accident. 
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
* In search of History Defending Sides. Usually smaller Side can't Protect themselves good enough, because they do not have capacity to do it and in example some Culture may drop Poorest ones.
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
* In comparison there should not be allowed to register microsoft.<country_initials>, google.<country_initials> because You would be sued for phishing attack on the Big Tech Company. There still exists problem for names like m1crosoft.<country_initials> or goog1e.<country_initials>, because this could be used for creating fake hostname-domain name services over Internet, over Digital e.Space.
* By returning back to previous entities, they sound similar, but one of them are with longer sentence. Usually people are too lazy to type more, so with shorter sentence hostname-domain name already with advantage, rest is only question of quality of service. Does those (up to year old) services saying the Truth in their Slogans. Checking legitimacy for Payed Taxes to the Country Budget could be begint-started at first.
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
* if website would be updated into popular known frameworks, then would require to check for keeping it updated in regular basis.
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

According this Article [LRT.lt](https://www.lrt.lt/naujienos/pasaulyje/6/1701282/pamatykite-lietuvos-policijos-pareigunai-padeda-aptikti-nukautu-rusu-kunus-ukrainoje) Law enforcement Forces shown in the Victim Country.
```

```
##### R esults 
Possible of leak of metadata for specific coordinates.
Law enforcement Forces risking their Lives.
Who would be responsible for comming Guided Missle?
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Various devices are leaving coordinate metadata and that is positive approach.
* Does there should be Located Law enforcement Forces with permission of the Eurojust (against violation to the Law) and (or) the Europol (against Terrorists)? In the Article there are lacking data for presence of more International Order.
```

```
##### I ncident

According this Article [-](https://www.lrt.lt/naujienos/sveikata/682/1702044/prasoma-atimti-gydytojo-licencija-uz-kysininkavima-nuteistam-dar-vienam-chirurgui-uz-operacijas-eme-nuo-100-iki-400-euru) doctor lost his License.
```

```
##### R esults 
Doctor can't use his expertise which were build in many Years of Education in the Medicine Sector.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Nowadays even beggars, e.beggars (electronic device), i.beggars (internet platform) has electronic devices to collect Tips which are given by anyone who has smart device or card.
* Hospitals lack of electronic devices and Managers to collect money from Patients which unfortunately later on would be distributed evenly to all the Doctors and Nurses, who has the same Work in the Operation Room. Additionaly event from such Actions - Taxes should be payed too.
* There would be a lot of questions, in example, this Article [-](https://www.lrt.lt/naujienos/nuomones/3/1702078/marija-verner-kaip-pasauliui-sekasi-de-kolonizuoti-moteru-kunus) lacks gender neutral Job Names which something are done in here [-](https://www.unwomen.org/en/csw), but the Results could be not so [-](https://www.lrt.lt/naujienos/gyvenimas/13/1702004/makalius-apie-solo-keliones-yra-poru-kasmet-keliaujanciu-tuo-paciu-metu-bet-skirtingomis-kryptimis) and when in the Operation comes more than three Nurses, does this much are needed for simple Cut, Take out and Clean, Sew in example: the Human Condition:Cist'it-Cyst'yt.
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

According this Resolution [LRT.lt](https://e-seimas.lrs.lt/portal/legalAct/lt/TAP/7ccfdcc0cf8511ecb69ea7b9ba9d787b?positionInSearchResults=12&searchModelUUID=5013b01b-5740-45f3-91f6-d2cec93cdc67) it's required to change status of the defined Country into Terrorist Supporting Subject.
```

```
##### R esults 
Possible Threat to the Citizens-Persons who stays in the Terrorist Supporting Country.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Private Sector are stopping ties with the Agressor Country. Currently it counts about 1100 Abroad Companies who left the Russia and (or) Russian Federation (following — Aggressor Country).
* According the results of this Article [LRT.lt](https://www.lrt.lt/naujienos/lietuvoje/2/1728031/lietuvos-konsulas-apie-z-raidemis-apipaisyto-automobilio-incidenta-reguliariai-gauname-bjaurasties-su-visokiais-palinkejimais) there could be uncertainty for Republic of Lithuania who still have employees (diplomats, consul, etc.) in named Agressor Country. Who will take care for security of these employees in the engl. Moscow (Capital) / rus. Москвe (Cтолицe) of the Aggresor Country?
* One Issue would be for how many ties Aggresor Country has with Afghanistan (Taliban in power) and for next one: in how many Ways the Taliban are Democratic who are representing whole Afghanistan in United Nations Organisation.
* Uncertainty in Country Official ranks, because The People's Republic of China sended "Trustee of Issues" instead of any other diplomats and consuls, when the specific Institution in Republic of Lithuania was named as it was requested by Taipei Taiwan. It's unclear for following rhetoric Question: does someone forged the e-mail for such thing to happen, or it's huge differences in ethics, traditions and etc. between the Entities in Communication. 
```

```
##### I ncident

According this Article [LRT.lt](https://www.lrt.lt/naujienos/pasaulyje/6/1730350/pekinas-uzsipuole-nato-del-visiskai-beprasmisko-ispejimo-kinijos-atzvilgiu) is easy to see that there are Sample of "Man-in-the-Middle" attack. For example there are many articles like this with Sentences [ELTA](https://www.lrt.lt/naujienos/pasaulyje/6/1729443/nato-vadovas-sustiprintos-greitojo-reagavimo-pajegos-bus-pasirengusios-veikti-2023-iaisiais) for „Rusija kelia grėsmę ne tik Europai, bet ir visai NATO“.
```

```
##### R esults 
Middle Man gets "strong friendship with the People’s Republic of China" by sending them propaganda as it was from the "Republic of Lithuania". 
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Middle Man could survive for very long, i.e. get Payments, which are directed not for them, spread disinformation between separate Countries-States, create Situation of War for their part of Economy Machine, i.e. Rockets. But History knows that Best Rocket Engineers took the United States of America (USA) after WWII.
* Does there are at least Sanctions for those Disinformation spreaders, officers and higher ups? 
* If You send a pille of digital/crypto Money, then after transaction, would be wise to safely ask from other side for the real numbers (Income) and the (Digital/Crypto) Currency.
* Well not good for "People’s Republic of China", because the Propagandists Country(-ies) probably has cappability to create/are creating "(Small) Sattelite Republics" and makes more the word of "Republic" dirty, unpleasant. 
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
* Does Certificates of the Public key Cryptography of the SSH should be regularly updated like SSL Certs for Site Security? 
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

According this Article [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1820550/melynu-varneliu-chaosas-twitter-apsisaukeliai-apsimeta-itakingais-asmenimis-o-platforma-nezino-kaip-su-tuo-tvarkytis) Crow Sign/Symbol does not every time/always mean: What You See Is What You Are.
```

```
##### R esults
People may be fooled by entities on the Platform which has proof of their Identity.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* In some extend Social media of "Facebook" are trying to keep whole users community base as non-Fake Accounts. In that case each Union/State/Country has representatives who help to block those Fake Accounts, in instance by initiating and clicking Button to Report the User as Fake Account.
* Identity check and Private and Personal Information storage and management requires additional Compliance to specific jurisdictional and standard regulation. Does the Company are compliant with any of those standards?
* According provided Identity Check cost Sum, it is really very cheap. For proper Administration of all Users this Sum should be at least doubled or trippled. But even in this Situation does there will be enough of personell to manage this Question? 
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
* Probable purchase of domain naime are not checked by simple List of Critical or not so Critical Information Systems, where there would be added limitations how similar are domain names, which already exists and new wish of domain from some new entity, i.e. l and 1 are similar in used encoding table, so it means, when You purchase, i.e. domain name of "love", the "1ove" would be added in the Basked too, just to overcome such phisching scam from someone, in this sample the Victim is who does not have what to offer.  

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
* The Portal of common domain purchase in U.S.A. is [GoDaddy](https://www.godaddy.com/en-ie/tlds/net-domain?countryview=1&isc=e1domgon1&countryview=1&currencyType=EUR), which allows to do World-Wide purchases and promotes original Country names on which they have been decided for themselves, in instance the "Türkiye".
* Exists domain name forwarding, i.e. by going into "vmi.net" could be made Browser forwarding from Server side into a Site of "vmi.lt". In this case everything could end up better than described in the "R esults".
* Bi-polar situation in the LTU, when there exists Site's like [Data Agency of the Country](https://www.stat.gov.lt/), when ".gov" domain name in use just after ".lt". And in the end we own normal domain ".gov.lt" for the Government domain + LTU domain. Now let us take the situation of sample domain of Lithuanian institution [IVPK](https://ivpk.lrv.lt/), which produce ".lrv" domain + ".lt" domain. This is equal situation of Government domain + LTU domain. Who should answer the Question for the regulars, citizens, which one could be Trusted? or does they both (.gov.lt) and (.lrv.lt) are Trusted domains? where first represent TopLevelDomain + CountryCodeTopLevelDomain and second represent some simple Domain + CountryCodeTopLevelDomain.
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
* For number of Years public instututions provide links to Trusted Sources like in this Site [vlkk.lt](https://vlkk.lt/nuorodos/zodynai). Data Sync and Update from various Databases are yet simple. Common people can't get access in one place by specific regular Search "Tree", i.e. first link to Knowledgebase of Cybersecurity Terms and Definitions. By checking this [terminai.vlkk.lt](http://terminai.vlkk.lt/paieska?search=Cyberbullying&zodzio_dalis=0&kalba=2&kaip0=on&sritys=&statusas=0&rykiavimas=0) out, non-NULL result given, simple Zero.
* Zhōngwén or similar languages could be selected by terminai.vlkk.lt in Advanced Search Settings by clicking checkbox on the last option "All lang.". This option represents the same Ideas as the original Article. 
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
