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
##### I ncident

According [@Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/1230743/narkotikai-pasto-siuntose-pareigunu-nebestebina-uzsimota-drausti-jiems-gaminti-skirtu-medziagu-siuntima) a Narcotics could be purchased Online. Shipment over Post Office service could be used to deliver purchased Packages.
```

```
##### R esults 
Electronic Services are used for trafficing illegal substances.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
*  The Article mostly provide Idea only about narcotics import issue(s). The Article d'nt take in to the account local production capabilities.
*  The Statistics found in here [unodc.org](https://www.unodc.org/unodc/en/data-and-analysis/) provide a bad situation in the European and North American Continent - identified & not completely identified purchase(s) over a Darknet.
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
*   If Web Site has number of Authentication Levels (i.e. public Site, Authenticated Site) then Web Administrator should get proper requests, which could explain on which Level Job should be completed.
*   If there were no extra Job, then the Audit Logs could answer to the Question: what happened? unless the Security incident happen which lead into loss of Integrity and Authenticity of Journaling Data Logs.  
*   General Data protection Reglament only works in Private Sector. For Public Sector it would need to look into the local Regulations and to Report the Issue.
*   Common Automated Security Check tools can't tell, which information should be Public and which - Not. OpenAI Bot allow to Set Up Your Learning Data, then it could be good to find out the problem, which were given in the previous Sentence.
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
*   The Article provide Fact "Telecomunication Company should never check SMS of their Users". If Telecomunication Company don't do that, then in addition they should not give Access to anybody else? because an Assets of a Person(s) is Untouchable. Illegal Orders may be the Problem for some kind of Jurisdictions.
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
*  According provided jurisdictional document the disinformation means that this misinformation information are speaded deliberately. This should mean that subject did that on the purpose. The Jurisdictional Act also provide a lot ties with the Lithuanian Republic and it's Independence & Sovereignty. 
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
*  According this Article You should not open pop-ups at all.
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
* The r/n of the company by taking in the Account this Article should be "120124533". From row of similar company name's there could be not clear for the client(s) whose they really are (was) registered for that exact company.
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
* Information exchanged between the electronic device and the service center should be protected with encryption and decryption, encoding and decoding, integrity checks, stamps and signatures. When this mechanism has to be updated, then the service could be tested in a testing environment before an original update commense.
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
* The use of the qualified digital signature are not wide-spread. The digital-signature for themself could include private information like personal identity code, home address & major of applications does not ask: what are required at minimum & what You are willing to share. Recommendation to not use for the social media accounts.
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

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2193161/bendrove-ignitis-patyre-programisiu-ataka) e.service (Software as a service) of a company "Ignitis" got a successful cyberattack.
```

```
##### R esults
Twenty thousand client's data were lost. This include data as a First Name, a Last Name, an E-mail address, a RFID data, a license plate number of an electromobile.
Electromobile charging was unavailable & client's could not use e.service.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* In a situation when e.service's (i.e. Software as a service) could be a service, which operates from other jurisdiction there could be issues to local security staff to defend local Rights for example to get a Compensation for a Client's. When e.service exists in the same economic zone, then there should be enough of safeguards in place to solve case like this.
* Company representative suggested for the client's to change their password's of the e.service.
* In a situation of existance of unclonable RFID-tag's electromobile should be directly connected with a Tag. If this could be electromobile sharing service who depend by data in online database, then in a worst case of situation those electromobile's could be snached. There are nothing new by opening... the car with a Tag. Yet, mostly known that the mobile phone could be used instead of a Tag & this probably should be a different situation.
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
* National Cyber Security Center (NCSC) own nice Tool [nksc.lt](https://www.nksc.lt/tikrinti.html). This IP checker provide information about Computer Activity in TCP/IP Computer Network. I.e. this Computer IP Address not registered in "NKSC/CERT-LT" Database for full 30 day period. When Mobile phone(s) are important in daily social life, then why does the Police don't open possibility to test out Fixed & Mobile phone addresses for being in a "Database"? When Person really want to call it back, then at least he could check that phone number (not)exists in a common "Database" for number of cases.  
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
* Internet is meant for the Internet e.Payments. When Person want to stop participating in unknown gambling activities, then this Person should take in an account plausibility that this(-ose) internet sites could deny his request for gambling, ref. [epaslaugos.lt](https://www.epaslaugos.lt/portal/service/74420/13221?searchId=dc364005-8bed-4487-b267-56e67ed3d504).
* When Person want to make Money Investment, then awareness of selecting right place are very important. Ref. [lb.lt](https://www.lb.lt/lt/investavimas-kaip-atpazinti-sukcius#ex-1-2).
* At the previous reference domain are plausible to locate illegal and forbbiden investment internet sites. DNSSEC widespread use could enforce protective means when this tool are in use [nksc.lt](https://www.nksc.lt/uzkarda.html) and protection - full automatic.
* Your computer - smartphone connection don't have DNSSEC support? Public and Private Key Cryptography Key Management usually are made by telecommunication companies and they provide list of DNS services, which Client should use. Registration for personal DNSSEC keys could help and improve the situation or usual approach - use Anti-Virus Software with this type of service. Anyway, common non-Browser Software Product could just not use this tech, then awareness of Software Product(s) plausibilities also are needed.   
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
* Smart Home, Smart Automobile industry has measures that with mobile phone, smart card You could open Doors. Safety and Emission Recalls shown in here [bmwusa.com](https://www.bmwusa.com/safety-and-emission-recalls.html). This should include Software and Hardware issues. Taking care of Your own Asset should go as priority no. One. p.s. Site Search in [bmw.com](https://www.bmw.com/en/search.html#recall) for Recall provide only "Fictional" Results.
```

```
##### I ncident

According this Article [Lrt.lt](https://www.lrt.lt/naujienos/lietuvoje/2/2215652/kaip-ir-kokie-tamo-duomenys-buvo-nutekinti-vogta-is-vartotoju-kompiuteriu-ispeja-del-galimo-pavojaus) TAMO e.service users are constantly attacked from entities who want to get data from this Site. Statement: Probable data collection activity from a long long past. Service users compromising e.service, so probably they need to refresh Knowledge of Cybersecurity.
```

```
##### R esults
e.Service users compromising their own e.Service Accounts.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* When there is a talk about National Cyber Security Center, then citizens could argue that they use some type Browser Software, which could be at fault, to access this e.Service.
* Does popular Browser Sofware is a very secure Software? I.e. Google Browser - a free (and open) Software.
* TAMO has Google supported Cookiebot functionality, use www.googletagmanager.com + www.google.com/recaptch + fonts.googleapis.com. What this Site does not has is a guided functionality of [developers.google.com](https://developers.google.com/publisher-tag/guides/content-security-policy). Allowing what is allowed, rejecting what is not allowed and there should be less problems for e.Service Users, because they probably has smart enough Browser Software.
* Data collection activity from a long long time? When somebody could include malicious code in the source code of the System (directly/indirectly). When this could be the case, then they could grab the data of hundreds and thousands people. Secure versioning of a TAMO code? secure architecture re-check of a authentication mechanism? searching for plausible data stealer code and how this was introduced to the System.
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
* The problem could be related with non-legal investment and about that Person(s) should build awareness using this source from the Lithuanian Bank: [lb.lt](https://www.lb.lt/lt/sukciavimas).
* IP address to hostname conversion service could be at fault, fake Site could be build by the scammer who just look like a original Site. In this case Banking institution should have e.banking site with good and proper defences, i.e.  [lb.lt](https://www.lb.lt) has Header Security Rules "frame-ancestors 'self' monetos.lb.lt coins.lb.lt *.cv.lt *.cvonline.lt;". This data clearly provide data to the modern Browser App(s) and answer the serious questions: what are allowed and what aren't allowed?
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
* In Republic of Lithuania from previous view points there should be huge shortage of experts who could solve legal issues of Cryptocurrency and to protect the public interest. Uncontrolled Cryptocurrency could mean only huge gap in financial literacy when regular "Paypal" Accounts are "monitored" [vmi.lt](https://www.vmi.lt/evmi/pagrindinis?p_p_id=com_liferay_portal_search_web_portlet_SearchPortlet&p_p_lifecycle=0&p_p_state=maximized&p_p_mode=view&_com_liferay_portal_search_web_portlet_SearchPortlet_mvcPath=%2Fview_content.jsp&_com_liferay_portal_search_web_portlet_SearchPortlet_redirect=https%3A%2F%2Fwww.vmi.lt%2Fevmi%2Fpagrindinis%3Fp_p_id%3Dcom_liferay_portal_search_web_portlet_SearchPortlet%26p_p_lifecycle%3D0%26p_p_state%3Dmaximized%26p_p_mode%3Dview%26_com_liferay_portal_search_web_portlet_SearchPortlet_redirect%3Dhttps%253A%252F%252Fwww.vmi.lt%252Fevmi%252Fpagrindinis%253Fp_p_id%253Dcom_liferay_portal_search_web_portlet_SearchPortlet%2526p_p_lifecycle%253D0%2526p_p_state%253Dnormal%2526p_p_mode%253Dview%26_com_liferay_portal_search_web_portlet_SearchPortlet_mvcPath%3D%252Fsearch.jsp%26_com_liferay_portal_search_web_portlet_SearchPortlet_keywords%3DPaypal%26_com_liferay_portal_search_web_portlet_SearchPortlet_formDate%3D1710941103070%26_com_liferay_portal_search_web_portlet_SearchPortlet_scope%3Dthis-site&_com_liferay_portal_search_web_portlet_SearchPortlet_assetEntryId=793543&_com_liferay_portal_search_web_portlet_SearchPortlet_type=content&inheritRedirect=true).
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
* In technological way second level domains does not communicate with each other when the whole Web Software for first level domain is with the same Framework. When one content admin make changes in his second level domain news page as the result an other content admin who used his link does not get any notification(s). The whole purpose of using second level domains with unified framework should solve communication issues as described above. One contant admin feels at ease when he manage his own Site, no accountability of his to other content admin(s). Regular way to solve this issue — collecting all page modifications (history) at one place and providing unified button to open latest version of a page. This way there could be less problems with interlinking between different sites. Usualy content has limited time to exist and to solve this issue this(these) page(s) could provide information for how long the information are relevant. When using framework probably easies way would be to cache or scrap the content into own database, so content admin(s) could be at ease.
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

According this check [-](https://github.com/PolVilniusTech/public.incident.reporting.timeline.md/blob/main/Lithuania/Images/RRT%20not%20Available%202024-03-29.PNG) and provided Image in the GitHub Service RRT Site is not Available.
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
* HTTP response code of 404 means that while regular GET request in response got "NOT FOUND". This could mean that PDF file is not in a place where it should be. Plausible situation is that after a new file upload the site were not updated.
* In a chance when there were more vulnerable information reporting for security researchers couldn't get so simple, i.e. [-](https://judu.lt/.well-known/security.txt) or [-](https://judu.lt/security.txt) return HTTP response code 404. GPG/PGP information for encrypting message(s) is unknown.
* In West exists a hyghiene for linking documents in table like fashion. This means that information when the document were uploaded could be shown in page. This type of "Meta" information is unknown.
* Even after getting some document in the Page, i.e. [judu.lt](https://judu.lt/wp-content/uploads/2021/06/VT-2020-ataskaita.pdf) in the beginning client will get response code of 200 and cache the document in the HTTP client Software. Afterwards gonna be 304 "NOT MODIFIED" response code's while this document does not change.
* These documents contain valuable information for understanding what are planned beforehand. Take a sample of [judu.lt](https://judu.lt/wp-content/uploads/2021/06/VT-2020-ataskaita.pdf) in p. 78 & table 24 provided information about old trolleys park. There is provided idea that they don't contain "USB charging ports". Does this is very huge flaw? According the Article [cnn.com](https://edition.cnn.com/2023/04/12/tech/fbi-public-charging-port-warning/index.html) provided idea for a "juice jacking" problem. Does this is linked with only energy? No. Corrupted charging USB port could allow for a malicious actor to lock a device or extract personal data (emails, text messages, photos, contacts) & do not forget for something as password too. Take a sample that there could even be left some bunch of "infected cables". In the question: what to do? She could say: use electrical outlet instead of unknown USB charging port & cables. At least use Your own charger and USB cord.   
```

```
##### I ncident

According this check [Ktu.lt](https://github.com/PolVilniusTech/public.incident.reporting.timeline.md/blob/main/Lithuania/Images/EBOOKS%20too%20long%20to%20respond%202024-04-15.PNG) link does not respond. The existence of this Site were found from common Web Site [Lrt.lt](www.lrt.lt).
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

According the Article [Lrt.lt](https://www.lrt.lt/naujienos/verslas/4/2248995/sukciai-is-imones-vilniuje-apgaules-budu-isviliojo-beveik-305-tukst-euru) a personel received malicious request over email to transfer money using fabricated message.
```

```
##### R esults
Entity lost hefty sum of money.
```

```
##### L earning from Mistakes

From such incidents there are possible to learn a lot. I.e.:
* Unsolicited messages and SPAM over e-mail tech are an common approach for phishing attacks in the Internet. Clients use email applications with in-build protective means, i.e. phishing filter, scam filter. Exists chance that security measure(s) gonna fail to block this message or those messages. For this reason general SPAM should be less effective, but huge in numbers (more blocking necessary). Targeted phishing emails has bigger success rate and could impact into losing hefty sum of money.
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
* Take sample from other institution document [e-tar.lt](https://www.e-tar.lt/portal/lt/legalAct/ef108e70e9de11e6bf03a1097d29892a). This one does not provide actual information about internet site name. There is provided information about how this e-mail should be made off. By knowing real email schema there are plausible to conduct a phishing attack.
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
* Regular Citizens does not require to provide declarations. Only when exist requirement to pay Tax this citizen should get notification in the VMI system, i.e. You sold old Car and got extra money, then Pay a Tax. Everyone who forget should receive notifications from VMI.
* In the situation when institution at fault and made error, then citizen is not responsible and payment should be void. Currently technologies like [satellites.pro](https://satellites.pro/France_map) helps in solving some of these problems.
* Human Error could be a leading problem in any sector including Information Security, Cybersecurity and Privacy protection. Poor quality automatized and untested functionality could be missused by threat agent.
```

```
