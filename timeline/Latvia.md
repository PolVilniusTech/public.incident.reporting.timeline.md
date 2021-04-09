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

TODO.
