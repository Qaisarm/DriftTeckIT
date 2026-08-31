# L4 – IP-adresser, nätverk och subnät
## 40 Flervalsfrågor (MCQ)

Baserat på materialet i L4.

## Del 1: Klass A och nätverksnummer – Grundläggande

**1. Vad används nätverksnumret till i en IP-adress?**

A) För att identifiera en specifik användare  
B) För att identifiera vilket nätverk enheten tillhör  
C) För att identifiera datorns operativsystem  
D) För att identifiera datorns MAC-adress  

**2. Hur många bitar används för nätverksnumret i en klass A-adress?**

A) 4 bitar  
B) 8 bitar  
C) 16 bitar  
D) 24 bitar  

**3. Hur många bitar används för hostnumret i en klass A-adress?**

A) 8 bitar  
B) 16 bitar  
C) 24 bitar  
D) 32 bitar  

**4. Vilken av följande är ett exempel på en klass A IP-adress enligt materialet?**

A) 150.100.50.25  
B) 192.168.1.1  
C) 10.0.0.1  
D) 210.100.20.35  

**5. Vilket intervall anges för klass A-nätverk?**

A) 1–126  
B) 128–191  
C) 192–223  
D) 224–255  

**6. Vilken del av IP-adressen identifierar nätverket i klass A?**

A) De sista 8 bitarna  
B) De första 8 bitarna  
C) De första 16 bitarna  
D) De sista 24 bitarna  

**7. Vad är nätverksnumret för adresser mellan 10.0.0.0 och 10.255.255.255?**

A) 0  
B) 10  
C) 127  
D) 255  

**8. Hur många möjliga nätverksnummer finns teoretiskt i klass A enligt materialet?**

A) 64  
B) 100  
C) 128  
D) 256  

## Del 2: Reserverade adresser och Loopback – Medel

**9. Vilket nätverksnummer är reserverat och används inte för vanliga nätverk?**

A) 1  
B) 10  
C) 0  
D) 126  

**10. Vad används 127.0.0.0 för?**

A) Broadcast  
B) Loopback  
C) Default gateway  
D) DNS  

**11. Vilken adress är den vanligaste loopback-adressen?**

A) 0.0.0.0  
B) 10.0.0.1  
C) 127.0.0.1  
D) 192.168.1.1  

**12. Vad händer när man kör `ping 127.0.0.1`?**

A) Datorn skickar ett testmeddelande till sig själv  
B) Datorn startar om  
C) Datorn kontaktar routern  
D) Datorn skickar data till internet  

**13. Varför är loopback användbar vid felsökning?**

A) Den testar internetanslutningen  
B) Den testar om datorns nätverksfunktion fungerar  
C) Den ändrar IP-adressen  
D) Den startar DHCP  

**14. Om du kan pinga 127.0.0.1 men inte en annan dator på nätverket, vad kan det indikera?**

A) Datorns nätverksfunktion fungerar, men det finns problem med anslutningen till andra enheter  
B) RAM-minnet är trasigt  
C) Operativsystemet saknas  
D) Datorn saknar CPU  

**15. Vilket intervall består loopback-adresserna av enligt materialet?**

A) 10.x.x.x  
B) 127.x.x.x  
C) 192.x.x.x  
D) 255.x.x.x  

**16. Hur många användbara nätverksnummer finns i klass A enligt materialet?**

A) 124  
B) 125  
C) 126  
D) 127  

## Del 3: Host-ID, nätverksadress och broadcast – Medel

**17. Vilken formel används för att beräkna antalet möjliga host-ID?**

A) 2n  
B) 2n + 2  
C) 2ⁿ − 2  
D) n² − 2  

**18. Varför subtraherar man 2 när man beräknar möjliga host-ID?**

A) Två IP-adresser används av DNS  
B) En adress används för nätverket och en för broadcast  
C) Två adresser används av routern  
D) Två adresser används för DHCP  

**19. Vad kännetecknar en nätverksadress?**

A) Alla host-bitar är satta till 0  
B) Alla host-bitar är satta till 1  
C) Alla nätverksbitar är satta till 0  
D) Alla bitar är satta till 1  

**20. Vilken adress är nätverksadressen för 192.168.1.0/24?**

A) 192.168.1.1  
B) 192.168.1.10  
C) 192.168.1.254  
D) 192.168.1.0  

**21. Kan nätverksadressen 192.168.1.0 tilldelas en vanlig host?**

A) Ja, alltid  
B) Ja, om datorn använder WiFi  
C) Nej  
D) Endast om DNS används  

**22. Vilken adress är broadcast-adressen för nätverket 192.168.1.0/24?**

A) 192.168.1.0  
B) 192.168.1.1  
C) 192.168.1.254  
D) 192.168.1.255  

**23. Vad händer när ett paket skickas till broadcast-adressen?**

A) Endast routern tar emot paketet  
B) Alla enheter på nätverket tar emot förfrågan  
C) Endast DNS-servern tar emot paketet  
D) Paketet skickas till internet  

**24. Vilka adresser kan användas för enheter i nätverket 192.168.1.0/24 enligt materialet?**

A) 192.168.1.0–192.168.1.255  
B) 192.168.1.1–192.168.1.254  
C) 192.168.1.2–192.168.1.253  
D) 192.168.0.1–192.168.0.254  

## Del 4: ARP och IP-adresser – Medel/Svår

**25. Vad står ARP för?**

A) Address Resolution Protocol  
B) Address Routing Process  
C) Automatic Resolution Protocol  
D) Advanced Routing Protocol  

**26. Vad används ARP till?**

A) För att hitta en annan enhets fysiska MAC-adress  
B) För att ändra subnätmasken  
C) För att skapa en IP-adress  
D) För att starta om nätverkskortet  

**27. När en enhet behöver hitta MAC-adressen till en annan enhet på samma nätverk, vad skickas?**

A) En ARP-begäran  
B) En DNS-begäran  
C) En DHCP-server  
D) En BIOS-förfrågan  

**28. Till vilken adress skickas ARP-begäran enligt materialet?**

A) Nätverksadressen  
B) Broadcast-adressen  
C) Loopback-adressen  
D) Default gateway-adressen  

**29. Vilken enhet svarar på en ARP-begäran?**

A) Alla enheter svarar  
B) Endast den enhet som har den IP-adress som efterfrågas  
C) Endast routern  
D) Endast DNS-servern  

**30. Vilken adress representerar hela nätverket 192.168.1.0/24?**

A) 192.168.1.0  
B) 192.168.1.1  
C) 192.168.1.254  
D) 192.168.1.255  

## Del 5: Subnätmask och CIDR – Svår

**31. Vilken subnätmask motsvarar `/8`?**

A) 255.255.255.0  
B) 255.255.0.0  
C) 255.0.0.0  
D) 255.255.255.255  

**32. Vilken subnätmask motsvarar `/16`?**

A) 255.0.0.0  
B) 255.255.0.0  
C) 255.255.255.0  
D) 255.255.255.255  

**33. Vilken subnätmask motsvarar `/24`?**

A) 255.0.0.0  
B) 255.255.0.0  
C) 255.255.255.0  
D) 255.255.255.128  

**34. Hur många bitar används för nätverksdelen med subnätmasken 255.255.255.0?**

A) 8  
B) 16  
C) 24  
D) 32  

**35. Hur många host-bitar finns i ett `/24`-nätverk?**

A) 4  
B) 8  
C) 16  
D) 24  

**36. Vilken IP-adress används som exempel tillsammans med subnätmasken 255.255.255.0?**

A) 10.0.0.1  
B) 172.16.0.1  
C) 192.168.1.10  
D) 150.100.50.25  

**37. Vilket nätverk tillhör IP-adressen 192.168.1.10 med masken 255.255.255.0?**

A) 192.168.0.0  
B) 192.168.1.0  
C) 192.168.1.10  
D) 192.168.10.0  

**38. Vilken är hostdelen i exemplet 192.168.1.10/24?**

A) 192  
B) 168  
C) 1  
D) 10  

**39. Vilken binär form motsvarar subnätmasken 255.255.255.0?**

A) 11111111.11111111.11111111.00000000  
B) 00000000.00000000.00000000.11111111  
C) 11111111.00000000.11111111.00000000  
D) 11111111.11111111.00000000.11111111  

**40. Vilket påstående beskriver en korrekt subnätmask?**

A) 0:or måste komma före 1:or  
B) 1:or kommer först och 0:or kommer sedan  
C) 1:or och 0:or kan blandas fritt inom en oktett  
D) Alla oktetter måste vara 255  

## Facit – L4

1. **B**
2. **B**
3. **C**
4. **C**
5. **A**
6. **B**
7. **B**
8. **C**
9. **C**
10. **B**
11. **C**
12. **A**
13. **B**
14. **A**
15. **B**
16. **C**
17. **C**
18. **B**
19. **A**
20. **D**
21. **C**
22. **D**
23. **B**
24. **B**
25. **A**
26. **A**
27. **A**
28. **B**
29. **B**
30. **A**
31. **C**
32. **B**
33. **C**
34. **C**
35. **B**
36. **C**
37. **B**
38. **D**
39. **A**
40. **B**

---

# L6 – DOS / Kommandotolk
## 40 Flervalsfrågor (MCQ)

Baserat på materialet i L6.

## Del 1: DOS och Kommandotolken – Grundläggande

**1. Vad står CLI för?**

A) Computer Language Interface  
B) Command Line Interface  
C) Command Login Internet  
D) Computer Link Interface  

**2. Vad är DOS/Windows kommandotolk?**

A) Ett grafiskt bildredigeringsprogram  
B) Ett gränssnitt där man skriver kommandon  
C) Ett antivirusprogram  
D) En webbläsare  

**3. Är MS-DOS och Windows kommandotolk case sensitive enligt materialet?**

A) Ja, alltid  
B) Endast i Windows 11  
C) Nej  
D) Endast för lösenord  

**4. Vad betyder att kommandotolken inte är case sensitive?**

A) Den skiljer inte mellan små och stora bokstäver  
B) Den accepterar bara stora bokstäver  
C) Den accepterar bara små bokstäver  
D) Den kan inte läsa bokstäver  

**5. Vilket kommando används för att visa hjälp för ett kommando?**

A) help  
B) info  
C) manual  
D) assist  

## Del 2: Help, Systeminfo och History – Lätt/Medel

**6. Vad visar kommandot `help`?**

A) Nätverksanslutningar  
B) Hjälp för ett kommando  
C) Användarkonton  
D) IP-adresser  

**7. Vilket kommando kan användas för att få hjälp om `cd`?**

A) help cd  
B) cd help  
C) cd /helpme  
D) info cd  

**8. Vad visar kommandot `systeminfo`?**

A) Endast IP-adressen  
B) Fullständig systeminformation om Windows-datorn  
C) Endast användarnamn  
D) Endast hårddiskens storlek  

**9. Vad används `history` till enligt materialet?**

A) För att radera kommandon  
B) För att visa tidigare körda kommandon  
C) För att starta om datorn  
D) För att visa användarkonton  

**10. Vilket kommando används som exempel för att visa kommandohistoriken?**

A) history/show  
B) doskey/history  
C) command/history  
D) cmd/history  

**11. Vad är syftet med kommandohistorik?**

A) Att visa kommandon som redan har körts  
B) Att skapa nya användare  
C) Att ändra IP-adressen  
D) Att stänga av datorn  

## Del 3: IPConfig – Medel

**12. Vad visar `ipconfig`?**

A) IP-adress, subnätmask och default gateway  
B) Endast MAC-adressen  
C) Endast DNS-servern  
D) Windows användarlösenord  

**13. Vad visar `ipconfig /all`?**

A) Endast IP-adressen  
B) Hela TCP/IP-konfigurationen för alla adaptrar  
C) Endast default gateway  
D) Endast subnätmasken  

**14. Vilket kommando visar mest information om nätverksadaptrarna?**

A) ipconfig  
B) ipconfig /all  
C) ipconfig /show  
D) ipconfig /network  

**15. Vad gör `ipconfig /release`?**

A) Förnyar IP-adressen  
B) Tvingar nätverkskortet att släppa IP-numret  
C) Startar om datorn  
D) Raderar nätverkskortet  

**16. När är `ipconfig /release` relevant enligt materialet?**

A) När IP-adressen tilldelas automatiskt  
B) Endast vid statisk IP-adress  
C) Endast utan nätverkskort  
D) När datorn är avstängd  

**17. Vad gör `ipconfig /renew`?**

A) Raderar IP-adressen permanent  
B) Förnyar IP-adressen  
C) Stänger av nätverkskortet  
D) Tar bort DHCP  

**18. Vilken teknik används när `ipconfig /renew` automatiskt tilldelar IP-adress?**

A) DNS  
B) FTP  
C) DHCP  
D) ARP  

**19. Vilket kommando används för att förnya en automatiskt tilldelad IP-adress?**

A) ipconfig /new  
B) ipconfig /renew  
C) ipconfig /refresh  
D) ipconfig /reset  

## Del 4: PING och Output – Medel

**20. Vad används kommandot `ping` till?**

A) För att kontrollera kontakt med en angiven nätverksadress  
B) För att skapa ett användarkonto  
C) För att stänga av datorn  
D) För att ändra färgen på CMD  

**21. Vad kan anges efter `ping`?**

A) Endast ett användarnamn  
B) Ett IP-nummer eller en domän  
C) Endast en fil  
D) Endast ett lösenord  

**22. Vilket av följande är ett korrekt exempel från materialet?**

A) ping 192.168.1.5  
B) ping /192.168.1.5  
C) ping ipconfig  
D) ping user  

**23. Vilket kommando används i materialet för att pinga en domän?**

A) ping google.com  
B) google ping  
C) ping /google  
D) ping www  

**24. Vad kan `ping` hjälpa dig att kontrollera?**

A) Om din maskin har kontakt med en angiven adress  
B) Om Windows är aktiverat  
C) Om ett lösenord är korrekt  
D) Om en fil är krypterad  

**25. Vad betyder `|clip` enligt materialet?**

A) Skickar output till urklipp  
B) Raderar output  
C) Skickar output till internet  
D) Startar om kommandot  

**26. Vilket kommando är ett exempel på att skicka output till urklipp?**

A) ipconfig|clip  
B) clip|ipconfig  
C) ipconfig/clip  
D) ipconfig > clip  

**27. Vilket annat kommando visas som exempel tillsammans med `|clip`?**

A) ping  
B) systeminfo  
C) shutdown  
D) net user  

**28. Vad kan `ipconfig > fil.txt` användas till enligt materialet?**

A) För att skicka resultatet till en fil  
B) För att radera en fil  
C) För att starta en fil  
D) För att komprimera en fil  

## Del 5: Köra flera kommandon – Medel/Svår

**29. Vad används `&&` till?**

A) För att köra två kommandon tillsammans  
B) För att radera två kommandon  
C) För att skapa ett lösenord  
D) För att visa IP-adressen  

**30. Vilket exempel på `&&` finns i materialet?**

A) ipconfig && systeminfo  
B) ipconfig && ping  
C) systeminfo && shutdown  
D) ping && net user  

**31. Vad gör kommandot `ipconfig && systeminfo`?**

A) Kör de två kommandona tillsammans  
B) Raderar båda kommandona  
C) Kör bara systeminfo  
D) Startar om datorn  

## Del 6: Användarkonton – Medel/Svår

**32. Vilket huvudkommando används för att hantera användarkonton i materialet?**

A) user  
B) net  
C) account  
D) userset  

**33. Vilket kommando visar alla användarnamn?**

A) net users  
B) net user  
C) users net  
D) net account  

**34. Hur lägger man till ett användarnamn med lösenord enligt materialet?**

A) net user användarnamn lösenord /add  
B) add user användarnamn lösenord  
C) net add användarnamn  
D) user /create användarnamn  

**35. Vilket kommando används i materialets exempel för att skapa användaren Elev2?**

A) net user Elev2 /add  
B) net user Elev2 Jj123456/add  
C) net add Elev2 Jj123456  
D) user Elev2 Jj123456  

**36. Vilken parameter används för att ta bort ett användarkonto?**

A) /remove  
B) /delete  
C) /del  
D) /erase  

**37. Vilket kommando används i materialet för att ta bort användaren Elev2?**

A) net user Elev2 /delete  
B) net user Elev2 /del  
C) net delete Elev2  
D) delete user Elev2  

**38. Vad ska man göra när man arbetar med dessa kommandon för användarkonton?**

A) Köra CMD som administratör  
B) Starta webbläsaren  
C) Stänga av nätverket  
D) Logga ut från Windows  

## Del 7: Color och Shutdown – Medel/Svår

**39. Vad används kommandot `color` till enligt materialet?**

A) För att ändra färgerna i kommandotolken  
B) För att ändra IP-adressen  
C) För att ändra användarlösenordet  
D) För att ändra Windows-temat  

**40. Vad gör kommandot `shutdown /s /t 0`?**

A) Startar om datorn efter 5 sekunder  
B) Försätter datorn i viloläge  
C) Stänger av datorn direkt  
D) Loggar ut användaren  

## Facit – L6

1. **B**
2. **B**
3. **C**
4. **A**
5. **A**
6. **B**
7. **A**
8. **B**
9. **B**
10. **B**
11. **A**
12. **A**
13. **B**
14. **B**
15. **B**
16. **A**
17. **B**
18. **C**
19. **B**
20. **A**
21. **B**
22. **A**
23. **A**
24. **A**
25. **A**
26. **A**
27. **B**
28. **A**
29. **A**
30. **A**
31. **A**
32. **B**
33. **B**
34. **A**
35. **B**
36. **C**
37. **B**
38. **A**
39. **A**
40. **C**
