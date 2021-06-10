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
### 2021

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

According [LRT.lt](https://www.lrt.lt/naujienos/mokslas-ir-it/11/1428867/nutekinta-didele-apimtis-kilobaitas-lt-klientu-duomenu-rekomenduojama-pakeisti-slaptazodzius) there were found the data leak from the e-Shop.
```

```
##### R esults 
About 191 thousand chunks of Data of the e-Shop Clients were lost including name, surname, email address, phone number, living apartament adress, encoded passwords.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
*   Don't use the same password in different Software Systems.
*   If there is no need, then don't provide Personal Data.
*   Use password managers, i.e. physical notebooks w/o risky Networks.

For e-Shops:
*  For how long You are going to keep the Data?  
*  What purpose of collecting personal data of the Citizens?
*  Does such Data are required to use every day/week/month/year?  
*  Does there are way to authorize Customers to the Service using, i.e. e-Government Gateway solutions and not keep the Data at all?
*  Does politics about Incident Response is in place and effective?
   
```

```

TODO.

