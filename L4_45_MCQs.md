# L4 -- IPv4, Nätverksklasser och Subnätmasker -- MCQ

Baserat på filen **"L4 info.docx(2).pdf"**.

## Del 1: Klass A-nätverk

### 1. Hur många bitar används för nätverksnumret i ett klass A-nätverk?

A)  4 bitar\
B)  8 bitar\
C)  16 bitar\
D)  24 bitar

### 2. Hur många bitar används för hostnumret i ett klass A-nätverk?

A)  8 bitar\
B)  16 bitar\
C)  24 bitar\
D)  32 bitar

### 3. Vilken del av en klass A-IP-adress identifierar nätverket?

A)  De första 8 bitarna\
B)  De sista 8 bitarna\
C)  De första 24 bitarna\
D)  Alla 32 bitar

### 4. Vilken del av en klass A-IP-adress identifierar en enhet inom nätverket?

A)  De första 8 bitarna\
B)  De första 16 bitarna\
C)  De sista 24 bitarna\
D)  Endast den första oktetten

### 5. Vilken IP-adress används som exempel på en klass A-adress i materialet?

A)  192.168.1.1\
B)  172.16.0.1\
C)  10.0.0.1\
D)  200.1.1.1

### 6. Vilket nätverksnummer har alla adresser mellan 10.0.0.0 och 10.255.255.255 enligt materialet?

A)  1\
B)  10\
C)  127\
D)  255

### 7. Hur många teoretiska nätverksnummer finns i klass A enligt materialet?

A)  64\
B)  100\
C)  128\
D)  256

### 8. Vilka två nätverksnummer är reserverade och används inte för normala klass A-nätverk?

A)  0 och 127\
B)  1 och 128\
C)  10 och 127\
D)  0 och 255

### 9. Vad används 0.0.0.0 för enligt materialet?

A)  Loopback\
B)  Ett vanligt klass A-nätverk\
C)  Ett speciellt syfte/reserverat för routing\
D)  Broadcast

### 10. Vad används 127.0.0.0 för?

A)  Broadcast\
B)  Loopback\
C)  Multicast\
D)  DNS

### 11. Vilken adress är den vanligaste loopback-adressen enligt materialet?

A)  10.0.0.1\
B)  192.168.1.1\
C)  127.0.0.1\
D)  255.255.255.255

### 12. Hur många användbara nätverksnummer finns i klass A enligt materialet?

A)  124\
B)  125\
C)  126\
D)  127

## Del 2: Loopback och host-ID

### 13. Vad händer när du kör `ping 127.0.0.1`?

A)  Datorn skickar ett testmeddelande till sig själv\
B)  Datorn pingar internetleverantören\
C)  Datorn pingar routern\
D)  Datorn skickar en broadcast till hela nätverket

### 14. Vad kan loopback användas för att testa?

A)  Skärmens upplösning\
B)  Nätverksdrivrutin, protokoll och nätverksprogramvara\
C)  Hårddiskens storlek\
D)  RAM-minnets hastighet

### 15. Om du kan pinga 127.0.0.1 men inte en annan dator på nätverket, vad kan det betyda?

A)  Datorn saknar helt nätverksfunktionalitet\
B)  Nätverksstacken fungerar, men det finns ett problem med anslutningen
    till andra enheter\
C)  CPU:n är trasig\
D)  Loopback-adressen är felaktig

### 16. Vilket adressområde anges som loopback-adresser i materialet?

A)  10.x.x.x\
B)  127.x.x.x\
C)  192.x.x.x\
D)  255.x.x.x

### 17. Vilken formel används för att beräkna antalet möjliga host-ID?

A)  2ⁿ\
B)  2ⁿ − 1\
C)  2ⁿ − 2\
D)  n² − 2

### 18. Varför subtraherar man 2 i formeln för antal möjliga host-ID?

A)  Två IP-adresser används för nätverksadress och broadcast-adress\
B)  Två IP-adresser används för DNS\
C)  Två adresser används alltid av routern\
D)  Två adresser används för loopback

### 19. Hur många möjliga host-ID har ett klass A-nätverk enligt materialets exempel?

A)  254\
B)  65 534\
C)  16 777 214\
D)  16 777 216

### 20. Hur många möjliga host-ID har ett klass B-nätverk enligt materialets exempel?

A)  254\
B)  65 534\
C)  16 777 214\
D)  128

### 21. Hur många möjliga host-ID har ett klass C-nätverk enligt materialets exempel?

A)  128\
B)  192\
C)  254\
D)  256

## Del 3: Nätverksadress och broadcast

### 22. Vad är en nätverksadress?

A)  En adress som representerar hela nätverket\
B)  En adress som alltid tilldelas routern\
C)  En adress för en specifik dator\
D)  En MAC-adress

### 23. Hur är host-bitarna satta i en nätverksadress?

A)  Alla till 1\
B)  Alla till 0\
C)  Varannan till 1\
D)  Slumpmässigt

### 24. Vilken är nätverksadressen för 192.168.1.0/24?

A)  192.168.1.1\
B)  192.168.1.254\
C)  192.168.1.255\
D)  192.168.1.0

### 25. Kan nätverksadressen 192.168.1.0 tilldelas till en vanlig host?

A)  Ja, alltid\
B)  Ja, om routern tillåter det\
C)  Nej\
D)  Endast med IPv6

### 26. Vilken är broadcast-adressen för nätverket 192.168.1.0/24?

A)  192.168.1.0\
B)  192.168.1.1\
C)  192.168.1.254\
D)  192.168.1.255

### 27. Vad händer när ett paket skickas till broadcast-adressen?

A)  Endast routern tar emot paketet\
B)  Alla enheter i nätverket tar emot paketet\
C)  Endast DNS-servern tar emot paketet\
D)  Paketet skickas tillbaka till avsändaren

### 28. Vilka adresser kan tilldelas hosts i nätverket 192.168.1.0/24 enligt materialet?

A)  192.168.1.0--192.168.1.255\
B)  192.168.1.1--192.168.1.254\
C)  192.168.1.0--192.168.1.254\
D)  Endast 192.168.1.1

## Del 4: ARP

### 29. Vad står ARP för?

A)  Address Routing Protocol\
B)  Address Resolution Protocol\
C)  Automatic Routing Protocol\
D)  Address Registration Process

### 30. Vad används ARP till?

A)  För att hitta en annan enhets fysiska MAC-adress på samma nätverk\
B)  För att skapa en subnätmask\
C)  För att tilldela IPv6-adresser\
D)  För att testa CPU:n

### 31. Vart skickas en ARP-begäran enligt materialet?

A)  Till loopback-adressen\
B)  Till nätverksadressen\
C)  Till broadcast-adressen\
D)  Till DNS-servern

### 32. Vem svarar på en ARP-begäran?

A)  Alla enheter svarar\
B)  Endast den enhet som har den efterfrågade IP-adressen\
C)  Endast routern\
D)  Endast DNS-servern

## Del 5: Subnätmask och CIDR

### 33. Vilket mönster måste en korrekt subnätmask följa i binär form?

A)  0:orna kommer först och 1:orna sedan\
B)  1:orna kommer först och 0:orna sedan\
C)  1 och 0 får blandas fritt\
D)  Alla bitar måste vara 1

### 34. Varför är 255.255.255.200 en felaktig subnätmask enligt materialet?

A)  Den innehåller en blandning av 1:or och 0:or inom en oktett\
B)  Den innehåller för många oktetter\
C)  Den är alltid en broadcast-adress\
D)  Den använder hexadecimala tecken

### 35. Vilken CIDR-notation motsvarar subnätmasken 255.0.0.0?

A)  /4\
B)  /8\
C)  /16\
D)  /24

### 36. Hur många bitar används för nätverksdelen med subnätmasken 255.0.0.0?

A)  8\
B)  16\
C)  24\
D)  32

### 37. Vilken CIDR-notation motsvarar 255.255.0.0?

A)  /8\
B)  /12\
C)  /16\
D)  /24

### 38. Med subnätmasken 255.255.0.0, hur många bitar används för hostdelen?

A)  8\
B)  16\
C)  24\
D)  32

### 39. Vilken CIDR-notation motsvarar 255.255.255.0?

A)  /8\
B)  /16\
C)  /20\
D)  /24

### 40. Med subnätmasken 255.255.255.0, hur många bitar används för hostdelen?

A)  4\
B)  8\
C)  16\
D)  24

### 41. Vilket nätverk tillhör IP-adressen 10.0.0.1 med subnätmask 255.0.0.0?

A)  10.0.0.0\
B)  10.0.0.1\
C)  10.255.255.255\
D)  0.0.0.0

### 42. Vilket nätverk tillhör IP-adressen 172.16.0.1 med subnätmask 255.255.0.0?

A)  172.16.0.1\
B)  172.16.255.255\
C)  172.16.0.0\
D)  172.0.0.0

### 43. Vilket nätverk tillhör IP-adressen 192.168.1.10 med subnätmask 255.255.255.0?

A)  192.168.0.0\
B)  192.168.1.0\
C)  192.168.1.10\
D)  192.168.1.255

### 44. Vad är hostdelen för 192.168.1.10/24 enligt materialets exempel?

A)  192.168.1.0\
B)  0.0.0.1\
C)  0.0.0.10\
D)  10.0.0.0

### 45. Vilken adress identifierar den specifika hosten i exemplet 192.168.1.10/24?

A)  192.168.1.0\
B)  192.168.1.10\
C)  192.168.1.255\
D)  255.255.255.0

------------------------------------------------------------------------

# Facit

1.  B\
2.  C\
3.  A\
4.  C\
5.  C\
6.  B\
7.  C\
8.  A\
9.  C\
10. B\
11. C\
12. C\
13. A\
14. B\
15. B\
16. B\
17. C\
18. A\
19. C\
20. B\
21. C\
22. A\
23. B\
24. D\
25. C\
26. D\
27. B\
28. B\
29. B\
30. A\
31. C\
32. B\
33. B\
34. A\
35. B\
36. A\
37. C\
38. B\
39. D\
40. B\
41. A\
42. C\
43. B\
44. C\
45. B
