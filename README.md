# GNS3 vežbe zapredmet Bezbednost računarskih mreža

Ove vežbe se prvobitno bile rađene za moj diplomski rad "Analiziranje paketa i zaštita računarskih mreža" iz predmeta Bezbednost računarskih mreža, a kasnije su znatno poboljšane kako bi se primenjivale i na laboratorijskim vežbama u mojoj školi (Visoka ICT škola). Vežbe sadrže koncepte CCNA Security kursa i demonstriraju neke napade na samu mrežu i uređaje. Cilj vežbi je više da se upoznaju studenti sa nekim od pretnji u računarskim mrežama, a ne da predstave 100% realnu situaciju, dakle u realnosti nije možda 100% kao što je i opisano u vežbama. Vežbe su odrađene u emulatoru GNS3, koji je besplatan i otvorenog koda za sve operativne sisteme.

Ostali ciljevi obuhvataju upoznavanje studenta sa Wireshark-om (kako detektovati napad, na šta obratiti pažnju, kako zabeležiti određene pakete i koje sve informacije se mogu zabeležiti) i osnovnim protokolima i mogućnostima koje se mogu konfigurisati na Cisco ruterima i svičevima kako bi se ti napadi sprečili.

Vrsta uređaja koji se koriste u vežbama su:
1. Ruter Cisco IOU L3 155-2T
2. Svič Cisco IOU L2 15.2d
3. Firefox uređaj čiji se _image_ fajl može skinuti preko GNS3
4. Kali Linux virtuelna mašina sa instaliranim paketima: dsniff, ettercap, yersinia, sslstrip, isc-dhcp-server i nmap.
5. Ubuntu ili Windows virtuelna mašina

Vežbe su dostupne svima ko želi da se malo igra sa GNS-om i možete ih menjati, dopunjavati, deliti kako vam je volja. U koliko imate neke predloge ili želje bilo za nove napade ili formate vežbi, greške u njima i slično, slobodno me kontaktirajte ili pošaljite pull request pa ću ga pregledati u najkraćem mogućem roku.

**Napomena: Zloupotreba ovih vežbi, u smislu izvršenja opisanih i demonstriranih napada, na tuđe računare i mreže se smatra krivičnim delom, te vas upozoravam da to ne činite. Svrha vežbi je čista akademska, da se nauči nešto novo, prepoznaju moguće pretnje i načini da se zaštitite od istih. U koliko se opredelite da ih zloupotrebite, sami snosite posledice!**
