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
* For such Incidents when Case are Closed, then there should be available the Raport(s) how to fix the Problem(s), i.e. [fbi.com](https://www.fbi.gov/file-repository/dns-changer-malware.pdf/view).
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
    * What I do? (in total results in non-existing damage, in total results in catastrophic damage)
```

```

TODO.


