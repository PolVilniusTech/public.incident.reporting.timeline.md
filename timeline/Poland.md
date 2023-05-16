### References for the Research:
* site-check.cert.lt
* https://www.cert.orange.pl/aktualnosci/raport-cert-orange-polska-za-2020-rok

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

According [@TheGuardian.com](https://www.rtlnieuws.nl/tech/artikel/5226954/deepfake-rusland-navalny-europese-politici) parlamentarians from European Union had video chat with other person, who used deepfake technology using distance audio-video communication Solution.
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
##### I ncident

According [wyborcza.pl](https://wyborcza.pl/7,173236,27247035,polish-authorities-ignored-early-reports-of-cyber-attacks-on.html) and other Polish Sites the Government officials were attacked by Internet from external Criminals.   

```

```
##### R esults 

Private and even sensitive data of Government officials were leaked.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
*   Country Officials (incl. Government) don't have Securely pre-installed devices for communication between each other.
*   For Internal and External Criminals over Internet and other Communication Sources there are no proper legislation implemented. If there exists such legislation, then it not works.
```

```
### 2022

##### I ncident

According [ELTA](https://www.lrt.lt/naujienos/pasaulyje/6/1810554/lenkijos-senato-serveriai-patyre-kibernetine-ataka) some Cyber-Security attack were done to the site of Polish Parlament.
```

```
##### R esults 
Plausible:
* Service interruptions for the citizens who are in need of this Service
* Offline Internal Network
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* EU jurisdictional acts has ties with UN legislation. The Security Council of the UN has the powers to decide restrictive measures binding for all UN members.
* Information Cyber-Security related restrictive measures has to be implemented by all UN members and displayed in instance of known place: [sanctionsmap.eu](https://www.sanctionsmap.eu/)
* There are way to find specific documents which explain the situation, i.e. [finance.ec.europa.eu](https://finance.ec.europa.eu/publications/intellectual-property-rights_en). These documents are not perfect, additional notice that I. instead of "person or entity" could be described as "person entity or organisation entity" and II. instead of "Annex" would be used "Attachment", unless You want include some pages to the main document, then "Annex" section would be not needed anymore.

```

```
### 2023

##### I ncident

According [Kinga Wysocka, EurActiv](https://www.lrt.lt/pl/wiadomosci/1261/1888756/czasopisma-politycy-i-media-jak-rosja-i-chiny-sieja-dezinformacje) there are issues with Foreign Countries for Disinformation. And because Media does not understand the Polish language, they have copied three magazines from the Europe.
```

```
##### R esults 
* Some under 18 years old may be affected.
* The trend for Disinformation of disinformation.
```

```
##### L earning from Mistakes 

From such incidents there are possible to learn a lot. I.e.:
* Before posting check, if You understand the Content, which will be sended for Search Engines to index.
* Before posting check, if there are no magazines, which are "labeled" with 18+ or so, freely accessable over the Internet. By going into such Websites asking for "Cookies" are one, and asking if You are "18+" are other issue. Probably in this information age no-one remembers Compact Discs and their markings.
* Ethics code of the Media in Question, open magazines, which readers/auditorium probably are all 18+ just were posted in National Website.
* The Website [EURACTIV.pl](https://www.euractiv.pl/) shows Partners number of entities, including [Wyborcza.pl](https://wyborcza.pl/). By look of Wyborcza there are around five/ten links of those "Partners" and no EURACTIV. Assume one-sided disinformation Site of the EURACTIV.pl
* Probably other Countries could be affected with such professional Content found in here/or not.

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
