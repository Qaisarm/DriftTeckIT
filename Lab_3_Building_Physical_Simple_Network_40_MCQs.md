# Lab 3 -- Building a Physical Simple Network -- 40 MCQs

Baserat på filen **"Lab 3 -- Building a Physical Simple Network"**.

## Del 1: Nätverkets grunder och topologi

### 1. Vilka tre huvudkomponenter består nätverk av enligt labben?

**A)  Hosts, switches och routers**\
B)  PCs, printers och servers\
C)  CPUs, RAM och disks\
D)  Routers, keyboards och monitors

### 2. Vad ska byggas i denna labb?

**A)  Ett enkelt nätverk med två hosts och en switch**\
B)  Ett nätverk med fyra routrar\
C)  Ett trådlöst nätverk med fem accesspunkter\
D)  Ett nätverk utan switch

### 3. Hur många switchar krävs enligt Required Resources?

**A)  1**\
B)  2\
C)  3\
D)  4

### 4. Hur många datorer krävs?

A)  1\
**B)  2**\
C)  3\
D)  4

### 5. Vilka operativsystem anges för datorerna?

**A)  Windows 11/10**\
B)  Linux endast\
C)  macOS endast\
D)  Windows 7 endast

### 6. Hur många Ethernet-kablar krävs?

A)  En\
**B)  Två**\
C)  Tre\
D)  Fyra

### 7. Vilken IP-adress ska PC-A ha?

**A)  192.168.1.10**\
B)  192.168.1.11\
C)  192.168.0.10\
D)  192.168.1.1

### 8. Vilken IP-adress ska PC-B ha?

A)  192.168.1.10\
**B)  192.168.1.11**\
C)  192.168.0.11\
D)  192.168.1.1

### 9. Vilken subnet mask används av både PC-A och PC-B?

A)  255.255.0.0\
B)  255.0.0.0\
**C)  255.255.255.0**\
D)  255.255.255.255

### 10. Vilket verktyg ska användas för att verifiera anslutningen mellan datorerna?

**A)  ping**\
B)  dir\
C)  ipconfig\
D)  tracert

## Del 2: Ansluta och starta nätverket

### 11. Vad ska göras först i Part 1?

A)  Konfigurera IP-adresser\
**B)  Starta alla enheter**\
C)  Dela en mapp\
D)  Köra ping

### 12. Hur startas switchen enligt labben?

A)  Med en fysisk power-knapp\
**B)  Den startar när strömkabeln ansluts**\
C)  Med ett CMD-kommando\
D)  Genom att ansluta Ethernet-kabeln

### 13. Vad ska anslutas till PC-A:s NIC-port?

**A)  Ena änden av en Ethernet-kabel**\
B)  En HDMI-kabel\
C)  En USB-kabel\
D)  En strömkabel från switchen

### 14. Vart ska den andra änden av Ethernet-kabeln från PC-A anslutas?

A)  Till PC-B\
**B)  Till switchen**\
C)  Till routern\
D)  Till monitorn

### 15. Vad indikerar en grön lampa efter att PC-A anslutits korrekt?

**A)  Att PC-A är korrekt ansluten**\
B)  Att IP-adressen är fel\
C)  Att Windows Firewall är avstängd\
D)  Att PC-A har internet

### 16. Vad ska göras med PC-B?

**A)  Den ska också anslutas till switchen**\
B)  Den ska anslutas direkt till PC-A\
C)  Den ska inte anslutas\
D)  Den ska anslutas till en router

### 17. Varför rekommenderas att noggrant kontrollera kablarna efter anslutning?

**A)  För att minska tiden som behövs för senare felsökning**\
B)  För att installera Windows\
C)  För att ändra IP-adressen\
D)  För att skapa en delad mapp

## Del 3: Konfigurera IP-adresser

### 18. Vad är Part 2:s första steg?

**A)  Konfigurera statisk IP-adressinformation på datorerna**\
B)  Installera en switch\
C)  Skapa en delad mapp\
D)  Starta om datorerna

### 19. Vilken Windows-inställning öppnas först för att konfigurera nätverket på PC-A?

**A)  Settings**\
B)  Task Manager\
C)  File Explorer\
D)  Control Panel endast

### 20. Vilken kategori väljs i Settings?

**A)  Network & Internet**\
B)  Accounts\
C)  Personalization\
D)  Apps

### 21. Vilket alternativ väljs i vänsterpanelen?

**A)  Ethernet**\
B)  Bluetooth\
C)  VPN\
D)  Wi-Fi

### 22. Vad väljs efter Ethernet?

**A)  Change adapter options**\
B)  Windows Update\
C)  Device Manager\
D)  Firewall settings

### 23. Vilket nätverksinterface ska högerklickas?

**A)  Ethernet0**\
B)  Wi-Fi0\
C)  Network0\
D)  Internet0

### 24. Vilket alternativ väljs efter högerklick på Ethernet0?

**A)  Properties**\
B)  Delete\
C)  Rename\
D)  Diagnose

### 25. Vilket protokoll ska väljas i Ethernet0 Properties?

**A)  Internet Protocol Version 4 (TCP/IPv4)**\
B)  Internet Protocol Version 6 endast\
C)  HTTP\
D)  FTP

### 26. Vad ska klickas efter att TCP/IPv4 har valts?

**A)  Properties**\
B)  Delete\
C)  Disable\
D)  Diagnose

### 27. Vilket alternativ används för att manuellt ange IP-adressen?

**A)  Use the following IP address**\
B)  Obtain an IP address automatically\
C)  Use DHCP only\
D)  Automatic network discovery

### 28. Vilken IP-adress ska anges på PC-A?

**A)  192.168.1.10**\
B)  192.168.1.11\
C)  192.168.10.1\
D)  192.168.0.10

### 29. Vilken subnet mask ska anges på PC-A?

**A)  255.255.255.0**\
B)  255.255.0.0\
C)  255.0.0.0\
D)  255.255.255.255

### 30. Varför anges ingen default gateway i exemplet?

**A)  Det finns ingen router ansluten till nätverket**\
B)  PC-A saknar Ethernet\
C)  Switchar använder inte IP\
D)  Windows saknar gateway-inställning

### 31. Vad ska göras efter att IP-informationen har angetts?

**A)  Klicka OK och sedan OK i Ethernet0 Properties**\
B)  Starta om BIOS\
C)  Stänga av switchen\
D)  Radera Ethernet0

### 32. Vad ska göras för PC-B?

**A)  Upprepa föregående steg och ange PC-B:s IP-information**\
B)  Använda exakt samma IP-adress som PC-A\
C)  Lämna IP-adressen tom\
D)  Ansluta PC-B till internet

## Del 4: Verifiera inställningar och anslutning

### 33. Vilket verktyg används för att verifiera PC-inställningar och anslutning?

**A)  Command Prompt**\
B)  BIOS\
C)  Task Manager\
D)  File Explorer

### 34. Vilket kommando används för att visa PC:ns hostname och IPv4-information?

**A)  `ipconfig /all`**\
B)  `ipconfig`\
C)  `ping /all`\
D)  `netstat /all`

### 35. Vilket kommando ska köras från PC-A för att testa anslutningen till PC-B?

**A)  `ping 192.168.1.11`**\
B)  `ping 192.168.1.10`\
C)  `ping 255.255.255.0`\
D)  `ping 192.168.1.1`

### 36. Vad kan vara orsaken om ping inte fungerar?

**A)  Windows Firewall kan blockera ICMP echo requests**\
B)  PC:n har för mycket RAM\
C)  BIOS är för gammalt\
D)  Skärmen är avstängd

### 37. Vad rekommenderas om PC-A inte får svar från PC-B efter ett nytt ping-försök?

**A)  Försöka pinga PC-A från PC-B**\
B)  Byta operativsystem\
C)  Formatera datorn\
D)  Byta CPU

## Del 5: Delning av resurser

### 38. Vad ska skapas på PC1 i Del 2?

**A)  Mappen `Setup_prog` på C: **
B)  Mappen `Windows` på D: 
C)  Mappen `Network` på C: 
D)  Mappen `Share` på Desktop

### 39. Vad ska göras med mappen `Setup_prog`?

**A)  Den ska delas med alla användare**\
B)  Den ska raderas\
C)  Den ska flyttas till PC2\
D)  Den ska komprimeras

### 40. Hur öppnas den delade mappen från PC2 enligt labben?

**A)  `\\IP-adress\Setup_prog`**\
B)  `C:\Setup_prog`\
C)  `IP-adress/Setup_prog`\
D)  `\\Setup_prog\IP-adress`

# Facit

1.  A\
2.  A\
3.  A\
4.  B\
5.  A\
6.  B\
7.  A\
8.  B\
9.  C\
10. A\
11. B\
12. B\
13. A\
14. B\
15. A\
16. A\
17. A\
18. A\
19. A\
20. A\
21. A\
22. A\
23. A\
24. A\
25. A\
26. A\
27. A\
28. A\
29. A\
30. A\
31. A\
32. A\
33. A\
34. A\
35. A\
36. A\
37. A\
38. A\
39. A\
40. A
