# L6 -- DOS / Kommandotolken -- MCQ

Baserat på filen **L6_Command-Line**.

## Del 1: Kommandotolken och grundläggande kommandon

### 1. Vad står CLI för?

A)  Command Line Interface\
B)  Computer Link Interface\
C)  Command Level Internet\
D)  Control Line Input

### 2. Vad handlar materialet främst om?

A)  Windows grafiska gränssnitt\
B)  DOS och Windows kommandotolk\
C)  Databashantering\
D)  Nätverkskablar

### 3. Är MS-DOS och Windows kommandotolk case sensitive enligt materialet?

A)  Ja, alltid\
B)  Nej, de skiljer inte mellan små och stora bokstäver\
C)  Endast i Windows 11\
D)  Endast i DOS

### 4. Vad gör kommandot `help`?

A)  Visar hjälp för ett kommando\
B)  Visar IP-adressen\
C)  Startar om datorn\
D)  Skapar ett användarkonto

### 5. Vilket kommando används som exempel för att visa hjälp om `cd`?

A)  `help cd`\
B)  `cd help`\
C)  `help /cd`\
D)  `cd /help`

### 6. Vad visar `systeminfo`?

A)  Fullständig systeminformation för Microsoft Windows-datorn\
B)  Endast IP-adressen\
C)  Endast användarnamn\
D)  Endast tidigare kommandon

### 7. Vad används `history` till enligt materialet?

A)  För att visa alla kommandon som redan körts\
B)  För att radera kommandon\
C)  För att starta om datorn\
D)  För att visa nätverkskort

### 8. Vilket kommando visas som exempel för att visa kommandohistorik?

A)  `history /all`\
B)  `doskey/history`\
C)  `show history`\
D)  `cmd history`

## Del 2: IP-konfiguration

### 9. Vad visar kommandot `ipconfig`?

A)  IP-adress, subnätmask och default gateway för adaptrar\
B)  Endast MAC-adressen\
C)  Endast DNS-servrar\
D)  Endast användarkonton

### 10. Vad visar `ipconfig /all`?

A)  Hela TCP/IP-konfigurationen för alla adaptrar\
B)  Endast aktuell IP-adress\
C)  Endast default gateway\
D)  Endast trådlösa nätverk

### 11. Vad gör `ipconfig /release`?

A)  Tvingar nätverkskortet att släppa sitt IP-nummer\
B)  Förnyar IP-adressen\
C)  Startar om datorn\
D)  Visar nätverksinformation

### 12. När är `ipconfig /release` relevant enligt materialet?

A)  När IP-adressen tilldelas automatiskt\
B)  Endast när IP-adressen är statisk\
C)  När datorn saknar RAM\
D)  När Windows ska stängas av

### 13. Vad gör `ipconfig /renew`?

A)  Förnyar IP-adressen\
B)  Raderar IP-adressen permanent\
C)  Visar systeminformation\
D)  Skapar en ny användare

### 14. Vilken teknik nämns tillsammans med `ipconfig /renew`?

A)  DNS\
B)  DHCP\
C)  FTP\
D)  HTTP

## Del 3: PING och output

### 15. Vad används kommandot `ping` till?

A)  För att kontrollera om datorn har kontakt med en angiven IP-adress
    eller domän\
B)  För att skapa en användare\
C)  För att stänga av datorn\
D)  För att visa systeminformation

### 16. Vilket är ett exempel på ett `ping`-kommando i materialet?

A)  `ping 192.168.1.5`\
B)  `ping /192.168.1.5`\
C)  `192.168.1.5 ping`\
D)  `ping ipconfig`

### 17. Kan `ping` användas mot en domän enligt materialet?

A)  Ja, exempelvis `ping google.com`\
B)  Nej, endast IP-adresser fungerar\
C)  Endast mot localhost\
D)  Endast mot routern

### 18. Vad gör `|clip`?

A)  Skickar output från kommandot till urklipp\
B)  Raderar output\
C)  Startar om CMD\
D)  Krypterar output

### 19. Vilket kommando visas som exempel för att kopiera `ipconfig`-output till urklipp?

A)  `ipconfig | clip`\
B)  `clip ipconfig`\
C)  `ipconfig > clip`\
D)  `ipconfig /clipboard`

### 20. Vad gör `>` i exemplet `ipconfig > fil.txt`?

A)  Skickar output till filen `fil.txt`\
B)  Raderar filen\
C)  Startar filen\
D)  Visar IP-adressen i webbläsaren

### 21. Vad gör `&&` i kommandotolken?

A)  Kör två kommandon tillsammans\
B)  Stoppar alla kommandon\
C)  Skapar en användare\
D)  Kopierar text till urklipp

### 22. Vilket kommando visas som exempel på användning av `&&`?

A)  `ipconfig && systeminfo`\
B)  `ipconfig && ping`\
C)  `systeminfo && delete`\
D)  `ipconfig > systeminfo`

## Del 4: Användarkonton

### 23. Vilket huvudkommando används för att hantera användarkonton i materialet?

A)  `net`\
B)  `user`\
C)  `account`\
D)  `accountnet`

### 24. Vilket kommando används för att visa alla användarnamn?

A)  `net users`\
B)  `net user`\
C)  `show users`\
D)  `users /all`

### 25. Hur lägger man till ett användarkonto enligt materialet?

A)  `net user användarnamn lösenord /add`\
B)  `add user användarnamn`\
C)  `net add user`\
D)  `user /create`

### 26. Vilket kommando används för att ta bort ett användarkonto?

A)  `/delete`\
B)  `/remove`\
C)  `/erase`\
D)  `/kill`

### 27. Vilket kommando visas som exempel för att ta bort användaren Elev2?

A)  `net user Elev2 /del`\
B)  `delete user Elev2`\
C)  `net delete Elev2`\
D)  `user Elev2 /remove`

### 28. Vad ska man göra för att kunna utföra övningen med användarkonton enligt materialet?

A)  Köra CMD som administratör\
B)  Starta webbläsaren som administratör\
C)  Starta Aktivitetshanteraren\
D)  Stänga av nätverket

### 29. Vilket användarnamn används i övning 3?

A)  Elev2\
B)  SAM\
C)  Admin\
D)  Student

### 30. Vilket lösenord anges för användaren SAM i övningen?

A)  `Ss123456`\
B)  `SAM123456`\
C)  `Ss654321`\
D)  `123456`

## Del 5: COLOR

### 31. Vad används kommandot `color` till enligt materialet?

A)  För att ange färger i kommandotolken\
B)  För att ändra IP-adressen\
C)  För att skapa en användare\
D)  För att stänga av datorn

### 32. Hur många hexadecimala tal anges med `color`?

A)  Ett\
B)  Två\
C)  Tre\
D)  Fyra

### 33. Vad anger det första hexadecimala talet i `color`?

A)  Bakgrundsfärg\
B)  Förgrundsfärg/text\
C)  IP-adress\
D)  Standardgateway

### 34. Vad anger det andra hexadecimala talet?

A)  Bakgrundsfärg\
B)  Förgrundsfärg/text\
C)  Nätverksadress\
D)  Användarnamn

### 35. Vad är resultatet av kommandot `color 17` enligt materialets färgtabell?

A)  Blå text på svart bakgrund\
B)  Vit text på blå bakgrund\
C)  Blå bakgrund med vit text\
D)  Grön text på röd bakgrund

## Del 6: Shutdown

### 36. Vad används kommandot `shutdown` till?

A)  För att stänga av eller starta om datorn\
B)  För att visa IP-adressen\
C)  För att skapa användare\
D)  För att visa kommandohistorik

### 37. Vad gör `shutdown /s`?

A)  Startar om datorn\
B)  Stänger av datorn\
C)  Försätter datorn i viloläge\
D)  Visar systeminformation

### 38. Vad gör `shutdown /r`?

A)  Startar om datorn\
B)  Stänger av datorn\
C)  Förnyar IP-adressen\
D)  Tar bort en användare

### 39. Vad betyder `/t xxx` i shutdown-kommandot?

A)  Anger en tidsgräns i sekunder före åtgärden\
B)  Anger användarnamn\
C)  Anger IP-adress\
D)  Anger färg

### 40. Vad gör `shutdown /h`?

A)  Försätter den lokala datorn i viloläge\
B)  Stänger av datorn direkt\
C)  Startar om datorn\
D)  Visar hjälp

### 41. Vad händer med kommandot `shutdown /s /t 0`?

A)  Datorn startar om efter 0 sekunder\
B)  Datorn stängs av direkt\
C)  Datorn går i viloläge\
D)  Datorn väntar i 60 sekunder

### 42. Vad händer med `shutdown /r /t 5`?

A)  Datorn stängs av efter 5 sekunder\
B)  Datorn startar om efter 5 sekunder\
C)  Datorn går i viloläge efter 5 minuter\
D)  Datorn förnyar IP-adressen efter 5 sekunder

------------------------------------------------------------------------

# Facit

1.  **A**\
2.  **B**\
3.  **B**\
4.  **A**\
5.  **A**\
6.  **A**\
7.  **A**\
8.  **B**\
9.  **A**\
10. **A**\
11. **A**\
12. **A**\
13. **A**\
14. **B**\
15. **A**\
16. **A**\
17. **A**\
18. **A**\
19. **A**\
20. **A**\
21. **A**\
22. **A**\
23. **A**\
24. **B**\
25. **A**\
26. **A**\
27. **A**\
28. **A**\
29. **B**\
30. **A**\
31. **A**\
32. **B**\
33. **A**\
34. **B**\
35. **C**\
36. **A**\
37. **B**\
38. **A**\
39. **A**\
40. **A**\
41. **B**\
42. **B**
