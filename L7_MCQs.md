# L7 -- DOS-kommandon och Batch-filer -- MCQ

Baserat på filen **L-7.pdf**.

## Del 1: Fil- och kataloghantering

### 1. Vad är målet med L7 enligt materialet?

**A)  Extra DOS-kommandon samt batchfiler och script-teknik**\
B)  Endast nätverkskonfiguration\
C)  Endast Linux-kommandon\
D)  Installation av Windows

### 2. Vilket kommando används för att kopiera en eller flera filer till en annan plats?

A)  MOVE\
**B)  COPY**\
C)  TYPE\
D)  XCOPY

### 3. Vad gör kommandot `COPY`?

**A)  Kopierar en eller flera filer till en annan plats**\
B)  Flyttar kataloger\
C)  Visar innehållet i en textfil\
D)  Tar bort en katalog

### 4. Vad gör följande kommando?

`copy MyFiles\Documents\Message.txt images`

A)  Flyttar Message.txt till Images\
**B)  Kopierar Message.txt från Documents till Images**\
C)  Visar Message.txt\
D)  Byter namn på Message.txt

### 5. Vad betyder `*.bmp` i ett COPY-kommando?

**A)  Alla BMP-filer**\
B)  Endast filen bmp\
C)  Alla textfiler\
D)  En katalog som heter bmp

### 6. Vad gör följande kommando?

`copy c:\images\*.bmp d:\BMPfolder`

**A)  Kopierar alla BMP-filer från images till BMPfolder**\
B)  Flyttar hela images-katalogen\
C)  Visar alla BMP-filer\
D)  Raderar BMP-filerna

### 7. Vad är skillnaden mellan COPY och XCOPY enligt materialet?

**A)  XCOPY kopierar filer och kataloger tillsammans med underkataloger**
    och deras innehåll\
B)  COPY fungerar bara med kataloger\
C)  XCOPY används bara för textfiler\
D)  Det finns ingen skillnad

### 8. Vad gör kommandot `MOVE`?

A)  Visar en fil\
**B)  Flyttar en eller flera filer och mappar till en annan plats**\
C)  Kopierar endast textfiler\
D)  Skapar en batchfil

### 9. Vad används kommandot `TYPE` till?

**A)  För att visa innehållet i en textfil**\
B)  För att flytta en fil\
C)  För att skapa en katalog\
D)  För att starta en tjänst

### 10. Vad visar kommandot `type testfile.txt`?

A)  Namnet på användaren\
**B)  Innehållet i testfile.txt**\
C)  IP-adressen\
D)  Alla filer i katalogen

## Del 2: CMD -- viktiga egenskaper

### 11. Är MS-DOS och Windows kommandotolk case sensitive enligt materialet?

A)  Ja\
**B)  Nej**\
C)  Endast för mappar\
D)  Endast för filer

### 12. Vad betyder att kommandotolken inte är "case sensitive"?

**A)  Den skiljer inte mellan små och stora bokstäver**\
B)  Den accepterar endast stora bokstäver\
C)  Den accepterar endast små bokstäver\
D)  Den skiljer alltid mellan stora och små bokstäver

### 13. Vad händer när en fil eller katalog raderas på kommandotolken?

A)  Den flyttas till papperskorgen\
B)  Den flyttas automatiskt till Desktop\
**C)  Den flyttas inte till papperskorgen**\
D)  Den kopieras till en backup

### 14. Hur får man mer information om ett kommando i CMD?

**A)  Skriver `/?` efter kommandot**\
B)  Skriver `/help` före kommandot\
C)  Skriver `info` efter kommandot\
D)  Trycker Ctrl + Alt + Del

### 15. Vilket kommando används som exempel för att få hjälp om `dir`?

A)  `help dir`\
**B)  `dir /?`**\
C)  `dir help`\
D)  `/? dir`

## Del 3: Batch-filer

### 16. Vad är en batchfil enligt materialet?

**A)  Ett Windows-programmeringsspråk som kan hanteras med enkla editorer**\
B)  En typ av bildfil\
C)  En nätverksanslutning\
D)  En Linux-kärna

### 17. Vilken filändelse har en BAT-fil?

A)  `.txt`\
B)  `.cmd`\
**C)  `.bat`**\
D)  `.exe`

### 18. Vad är en BAT-fil egentligen?

**A)  En vanlig textfil med filändelsen `.bat`**\
B)  En binär Windows-fil\
C)  En bildfil\
D)  En databasfil

### 19. Hur är kommandona organiserade i ett batchscript?

**A)  I rader och utförs i sekvens**\
B)  Slumpmässigt\
C)  Endast ett kommando kan köras\
D)  De körs bakifrån och fram

### 20. Vilket program kan användas för att skapa en batchfil?

**A)  Notepad (Anteckningar)**\
B)  Kalkylatorn\
C)  Aktivitetshanteraren\
D)  Paint

### 21. Hur sparar man en batchfil enligt materialet?

**A)  Som `ValfrittNamn.bat`**\
B)  Som `ValfrittNamn.txt`\
C)  Som `ValfrittNamn.exe`\
D)  Som `ValfrittNamn.cmdx`

### 22. Hur kan man utföra en batchfil enligt materialet?

**A)  Genom att dubbelklicka på filen**\
B)  Genom att öppna BIOS\
C)  Genom att starta om datorn\
D)  Genom att använda Aktivitetshanteraren

## Del 4: md och kataloger

### 23. Vad används kommandot `md` till i materialets övning?

**A)  För att skapa en katalog**\
B)  För att kopiera en fil\
C)  För att visa filinnehåll\
D)  För att flytta en katalog

### 24. Vad gör följande kommando?

`md mapp1`

**A)  Skapar katalogen mapp1**\
B)  Raderar mapp1\
C)  Kopierar mapp1\
D)  Visar mapp1

### 25. Vad gör följande kommando?

`md mapp1 mapp2`

**A)  Skapar två kataloger, mapp1 och mapp2**\
B)  Flyttar mapp1 till mapp2\
C)  Kopierar mapp1 till mapp2\
D)  Tar bort båda katalogerna

## Del 5: echo, pause och cd

### 26. Vad gör `@echo off` i en batchfil enligt materialet?

**A)  Undviker text som följer efter ett kommandoutförande**\
B)  Pausar kommandot\
C)  Skapar en katalog\
D)  Flyttar en fil

### 27. Vad gör kommandot `pause`?

**A)  Pausar kommandoutförandet och visar "Press any key to continue...."**\
B)  Stänger CMD\
C)  Raderar batchfilen\
D)  Skapar en textfil

### 28. Vad gör `echo Hej allihopa > laboration.txt`?

**A)  Skriver texten "Hej allihopa" till en ny fil**\
B)  Visar IP-adressen\
C)  Flyttar laboration.txt\
D)  Tar bort textfilen

### 29. Vad används `cd` till i materialets batchövning?

**A)  För att ändra arbetskatalog**\
B)  För att kopiera en fil\
C)  För att skapa en användare\
D)  För att visa en textfil

### 30. Vad gör `cd ..`?

**A)  Backar ett steg till föregående katalog**\
B)  Går till en ny användare\
C)  Skapar en katalog\
D)  Stänger kommandotolken

### 31. Vad gör `cd\` enligt materialets exempel?

**A)  Går till roten av den aktuella enheten**\
B)  Går en katalog upp\
C)  Skapar en ny katalog\
D)  Kopierar en fil

## Del 6: Batchövningen

### 32. Vilka mappar ska skapas i batchövningens exempel?

**A)  test1 och test2**\
B)  images och documents\
C)  mapp1 och mapp2\
D)  root och desktop

### 33. Vad heter textfilen som skapas i test1?

A)  Message.txt\
**B)  laboration.txt**\
C)  testfile.txt\
D)  kod.txt

### 34. Vilken text ska skrivas i `laboration.txt`?

A)  Hej!\
B)  Hello World!\
**C)  Hej allihopa**\
D)  Welcome!

### 35. Vad gör följande kommando?

`copy test1/laboration.txt test2`

**A)  Kopierar laboration.txt från test1 till test2**\
B)  Flyttar test2 till test1\
C)  Skapar laboration.txt i test1\
D)  Raderar laboration.txt

### 36. Vad gör följande kommando?

`move test2 C:\`

**A)  Flyttar test2 till roten på C: **\
B)  Kopierar test2 till Desktop\
C)  Byter namn på test2\
D)  Tar bort test2

### 37. Vad gör följande kommando?

`rename test2 RootFolder`

**A)  Byter namn på test2 till RootFolder**\
B)  Flyttar test2 till RootFolder\
C)  Kopierar test2 till RootFolder\
D)  Skapar en ny fil

### 38. Vad är syftet med `@echo off` i den färdiga batchfilen?

**A)  Undvika text som följer efter ett kommandoutförande**\
B)  Skapa två kataloger\
C)  Kopiera en fil\
D)  Byta namn på en katalog

### 39. Vilket kommando i batchfilen skapar textfilen `laboration.txt`?

**A)  `echo Hej allihopa > laboration.txt`**\
B)  `type laboration.txt`\
C)  `copy laboration.txt`\
D)  `md laboration.txt`

### 40. Vilket kommando i den färdiga batchfilen byter namn på `test2`?

A)  `move test2 C:\`\
B)  `cd\`\
**C)  `rename test2 RootFolder`**\
D)  `copy test2 RootFolder`

------------------------------------------------------------------------

# Facit

1.  A\
2.  B\
3.  A\
4.  B\
5.  A\
6.  A\
7.  A\
8.  B\
9.  A\
10. B\
11. B\
12. A\
13. C\
14. A\
15. B\
16. A\
17. C\
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
33. B\
34. C\
35. A\
36. A\
37. A\
38. A\
39. A\
40. C
