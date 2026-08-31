# CLI och DOS Batch – 50 MCQs (svenska, blandade svårighetsgrader)
Instruktion: Ange det rätta svaret (eller två riktiga vid två-svar). För frågor med två rätt svar, ange båda correspondingly i svaret.

## Del 1: CLI-kommandon (Windows Command Prompt och PowerShell)

### 1. Vilket kommando visar nätverkskonfiguration i Windows?

**A)  ipconfig**\
B)  ping\
C)  tracert\
D)  nslookup

### 2. Vilket kommando används för att pinga en adress?

A)  ipconfig\
**B)  ping**\
C)  tracert\
D)  nslookup

### 3. Vilket kommando används för att spåra en väg till en IP-adress?

A)  ipconfig\
B)  ping\
**C)  tracert**\
D)  nslookup

### 4. Vilket kommando används för att slå upp DNS-namn?

A)  ipconfig\
B)  ping\
C)  tracert\
**D)  nslookup**

### 5. Vilket kommando visar systeminformation i Windows?

**A)  systeminfo**\
B)  tasklist\
C)  diskpart\
D)  chkdsk

### 6. Vilket kommando används för att visa öppna portar? (två korrekta variant)

**A)  netstat**\
B)  tasklist\
C)  tracert\
D)  ipconfig

### 7. Vilket kommando används för att avsluta ett aktivt kommando i Windows?

**A)  Ctrl+C**\
B)  Ctrl+Z\
C)  Ctrl+Break\
D)  Ctrl+D

### 8. Vilket kommando används för att skapa en katalog i CLI?

**A)  mkdir**\
B)  rmdir\
C)  md\
D)  >

### 9. Vilket alternativ beskriver skillnaden mellan mkdir och rmdir? (två rätt svar)

**A)  mkdir skapar en katalog; rmdir tar bort**\
B)  mkdir används i batch; rmdir endast i Linux\
C)  Båda raderar filer; endast mkdir skapar kataloger\
D)  Ingen av dem raderar filer

### 10. Vilket kommando används för att kopiera filer rekursivt i batch?

A)  copy /S\
**B)  xcopy /S**\
C)  move /R\
D)  del /S

### 11. Vilket kommando används för att flytta filer?

A)  copy\
**B)  move**\
C)  rename\
D)  xcopy

### 12. Vad gör kommandot del?

A)  Skapar en ny fil\
**B)  Tar bort filer**\
C)  Döljer filer\
D)  Flyttar filer

### 13. Vilken batch-skript-rad används för att stänga av datorn?

**A)  shutdown /s**\
B)  reboot\
C)  exit\
D)  poweroff

### 14. Vad gör @echo off i en batch-fil?

A)  Aktiverar utskrift av varje kommando\
**B)  Dölj kommando-utdata**\
C)  Startar en ny kommandotolk\
D)  Kör automatisk uppgift

### 15. Vilken filändelse används för batch-skript?

**A)  .bat**\
B)  .exe\
C)  .cmd\
D)  .sh

### 16. Vilket kommando används för att visa innehållet i en katalog i batch-skript?

A)  ls\
**B)  dir**\
C)  show\
D)  list

### 17. Vilket kommando används för att visa aktuell arbetskatalog?

A)  pwd\
**B)  cd**\
C)  dir\
D)  chdir

### 18. Vilket kommando används för att få hjälp om ett kommando i CMD?

**A)  help**\
B)  info\
C)  man\
D)  ?

### 19. Vilket kommando används för att visa nätverksstatus i batch-skript?

A)  ipconfig\
B)  netstat\
**C)  netsh**\
D)  ping

### 20. Vilket kommando används för att köra ett program i bakgrunden (kör i bakgrunden)?

**A)  start /b**\
B)  run\
C)  exec\
D)  launch


## Del 2: Batch-filer och skript-logik (Frågor 21–40)

### 21. Vad gör kommandot for /f i batch-skript? (två rätt svar)

**A)  Parsar textfiler**\
B)  Skapar användare\
C)  Långsamt kör scriptet\
**D)  Utför op-gånger på varje rad i en fil**

### 22. Vilken rad används för att avsluta en batch-fil?

**A)  exit**\
B)  end\
C)  stop\
D)  quit

### 23. Vilket är syftet med @echo off i batch-skript?

**A)  Dölj körningens log**\
B)  Öka hastigheten\
C)  Ändra färg på texten\
D)  Starta om datorn

### 24. Vilket kommando används för att visa filinnehåll i batch?

**A)  type**\
B)  cat\
C)  echo\
D)  show

### 25. Vilka två av följande används ofta tillsammans i batch-filer för loggning? (två rätt)

**A)  echo >> log.txt**\
B)  log.txt = append\
**C)  set /p**\
D)  pause

### 26. Vilket kommando används för att ta bort en katalog och dess innehåll?

**A)  rmdir /s**\
B)  rm -r\
C)  del /f /s\
D)  erase /r

### 27. Vilket kommando används för att visa systeminformation i batch-skript?

**A)  systeminfo**\
B)  info\
C)  sysinfo\
D)  ver

### 28. Vilket av följande används för att köra en batch-fil vid uppstart i Windows?

A)  Starta från Start -> Debug\
B)  Lägg till i Autostart\
C)  Schemaläggning i Task Scheduler\
**D)  Både B och C är rätt**

### 29. Vilket kommando används för att kopiera en hel mapprekursivt i batch-skript?

A)  copy /E\
B)  xcopy /E\
C)  robocopy /MIR\
**D)  B och C**

### 30. Vilket program används ofta för att redigera batch-filer?

**A)  Notepad**\
B)  Word\
C)  Excel\
D)  Paint

### 31. Vilket av följande uttryck är sant om batch-skriptens variabler innehåll? (två rätt)

A)  Variabler används utan att deklarera\
**B)  Variabler sätts med set x=value**\
C)  Variabler är alltid strängar\
**D)  Variabler kan användas i if-satser**

### 32. Vilket av följande används för att kontrollera returvärde i batch-skript?

**A)  if %errorlevel%==0**\
B)  if %errorlevel% = 0\
C)  if defined error\
D)  if errorlevel==0

### 33. Vilket kommando kan användas för att läsa en textfil rad för rad i batch?

**A)  for /f**\
B)  while\
C)  read\
D)  scan

### 34. Vad gör kommandot echo off i batch-skript?

A)  Skriver varje rad till skärmen\
**B)  Dölj utskriften av kommandon**\
C)  Startar en ny process\
D)  Avslutar programmet

### 35. Vilket av följande är en vanlig metod för att skapa en enkel batch-fil?

**A)  Skriv i Notepad och spara som .bat**\
B)  Skriv i Word och spara som .txt\
C)  Skriv i Excel och spara som .csv\
D)  Skriv i Notepad och spara som .txt

### 36. Vilket kommando används för att byta arbetskatalog i batch-skript?

**A)  cd**\
B)  chdir\
C)  dir\
D)  set

### 37. Vilket av följande används för att hantera arkiv i batch-skript?

A)  zip\
B)  tar\
**C)  xcopy**\
D)  archive

### 38. Vilket kommando används för att visa användarkonton i Windows?

**A)  net user**\
B)  users\
C)  whoami\
D)  account

### 39. Vilket kommando används för att uppdatera miljövariabler i en batch-skript?

**A)  set**\
B)  env\
C)  export\
D)  var

### 40. Vilket av följande är en vanlig felkälla i batch-skript?

A)  Fel i radslut\
B)  Fel i parenteser i IF/ FOR\
C)  Fel i citattecken\
**D)  Alla ovanstående**


## Frågor 41–50 (Avancerade batch-skript och praktiska övningar)

### 41. Vilket kommando används för att skapa en katalog och först skicka in i den nya katalogen i samma rad?

**A)  mkdir ny \&\& cd ny**\
B)  mkdir ny; cd ny\
C)  cd ny mkdir\
D)  create ny

### 42. Vilket kommando används för att klippa ut vissa filer till en annan plats i batch?

A)  copy\
**B)  move**\
C)  cut\
D)  paste

### 43. Vad gör kommandot label i batch-skript?

**A)  Ändrar volymens etikett**\
B)  Låter dig märka filer\
C)  Laddar etiketter från nätverk\
D)  Byter filnamn

### 44. Vilket av följande är en användbar teknik för att skriva loggfiler i batch-skript?

**A)  echo log >> logfile.txt**\
B)  log > logfile.txt\
C)  write log.txt\
D)  log << EOF

### 45. Vilket är ett bra sätt att felsöka batch-skript?

**A)  Använda pause och visa variabler**\
B)  Köra utan felhantering\
C)  Ingen logg\
D)  Bara köra som admin

### 46. Vilket kommando används för att läsa inkommande parametrar i batch-skript? (två rätt)

**A)  %1**\
B)  %a\
**C)  %\***\
D)  %ARG%

### 47. Vilket filändelse används vanligtvis för batch-skript?

**A)  .bat**\
B)  .sh\
C)  .ps1\
D)  .cmd

### 48. Vad gör kommandot 'pause' i batch-skript?

**A)  Pausar exekveringen tills användare trycker en tangent**\
B)  Fördröjer start med 5 sekunder\
C)  Avslutar skriptet\
D)  Väntar på nätverket

### 49. Vilket av följande är en typisk struktur i en batch-skript med en IF-sats?

**A)  if EXIST file.txt ( echo found )**\
B)  if file.txt exists ( echo ok )\
**C)  if %errorlevel%==0 ( echo OK )**\
D)  if true ( echo true )

### 50. Vilket kommando används för att skriva över en befintlig fil?

**A)  echo > file.txt**\
B)  del > file.txt\
C)  rem > file.txt\
D)  copy /Y source.txt dest.txt

# Facit

1.  A\
2.  B\
3.  C\
4.  D\
5.  A\
6.  A\
7.  A\
8.  A\
9.  A\
10.  B\
11.  B\
12.  B\
13.  A\
14.  B\
15.  A\
16.  B\
17.  B\
18.  A\
19.  C\
20.  A\
21.  A, D\
22.  A\
23.  A\
24.  A\
25.  A, C\
26.  A\
27.  A\
28.  D\
29.  D\
30.  A\
31.  B, D\
32.  A\
33.  A\
34.  B\
35.  A\
36.  A\
37.  C\
38.  A\
39.  A\
40.  D\
41.  A\
42.  B\
43.  A\
44.  A\
45.  A\
46.  A, C\
47.  A\
48.  A\
49.  A, C\
50.  A