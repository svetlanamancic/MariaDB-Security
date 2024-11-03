Seminarski rad iz predmeta Sistemi za upravljanje bazama podataka.
Tema seminarskog rada je Sigurnost MariaDB servera baze podataka.

U digitalnoj eri, kada je osnovna valuta informacija, baza podataka ima funkciju sefa, koji čuva neprocenljivo blago podataka. Ipak, usled bujice digitalnih transakcija i interakcija, digitalna skladišta suočavaju se sa stalno prisutnom pretnjom, koja ugrožava suštinu njihovog postojanja. Pretnja se ogleda u narušavanju poverljivosti (eng. Confidentiality), integriteta (eng. Integrity) i dostupnosti (eng. Availability) informacija, već dobro poznate trijade (Confidentiality, Integrity, Availability - CIA) u oblasti bezbednosti informacionih sistema. Poverljivost, integritet i dostupnost su osnovni bezbednosni zahtevi i od suštinskog su značaja za zaštitu podataka.

Pretnje integritetu i poverljivosti podataka su višestruke, obuhvatajući širok spektar ranjivosti i vektora napada, koji koriste slabosti u strukturi bezbednosti baze podataka. Neke od najčešćih pretnji bezbednosti baze podataka uključuju:
  Neovlašćeni pristup
  SQL Injection napadi
  Denial of Service napadi
  Man-in-the-Middle napadi
  Oštećenje podataka (eng. data corruption)
  Curenje podataka (eng. data leaks)

Na slici je jednostavan primer čiji je cilj demonstracija kako bi napadač, koji prisluškuje mrežni saobraćaj, mogao da dođe do podataka skladištenih u bazi iako nema direktan pristup bazi i ne može da izvršava upite (Man-In-The-Middle napad), i važnost enkripcije podataka u tranzitu.

![image](https://github.com/user-attachments/assets/f0738c5b-8ac1-4b9c-a48f-de59c460f9ab)


......

Implementacijom robusnih kontrola pristupa, protokola za enkripciju i rigoroznih mehanizama monitoringa, organizaije mogu ublažiti rizike povezane sa neovlašćenim pristupom, krađom podataka i zlonamernim aktivnostima. Međutim, kako sajber pretnje neprestano evoluiraju, bezbednosna politika zahteva kontinuirano prilagođavanje i poboljšanje kako bi bila ispred potencijanih ranjivosti. Bezbednosne mere se moraju preduzeti na više nivoa kako bi se osigurala bezbednost podataka, od fizičke bezbednosti servera, preko operativnog sistema i servera baze podataka , do koda aplikacije.
