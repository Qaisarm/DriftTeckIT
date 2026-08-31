# CLI och DOS Batch – 50 MCQs (svenska, blandade svårighetsgrader)

Instruktion: Ange det rätta svaret (eller två riktiga vid två-svar). För frågor med två rätt svar, ange båda correspondingly i svaret.

Del 1: CLI-kommandon (Windows Command Prompt och PowerShell)

1. Vilket kommando visar nätverkskonfiguration i Windows?
A) ipconfig
B) ping
C) tracert
D) nslookup
Rätt svar: A
2. Vilket kommando används för att pinga en adress?
A) ipconfig
B) ping
C) tracert
D) nslookup
Rätt svar: B
3. Vilket kommando används för att spåra en väg till en IP-adress?
A) ipconfig
B) ping
C) tracert
D) nslookup
Rätt svar: C
4. Vilket kommando används för att slå upp DNS-namn?
A) ipconfig
B) ping
C) tracert
D) nslookup
Rätt svar: D
5. Vilket kommando visar systeminformation i Windows?
A) systeminfo
B) tasklist
C) diskpart
D) chkdsk
Rätt svar: A
6. Vilket kommando används för att visa öppna portar? (två korrekta variant)
A) netstat
B) tasklist
C) tracert
D) ipconfig
Rätt svar: A
7. Vilket kommando används för att avsluta ett aktivt kommando i Windows?
A) Ctrl+C
B) Ctrl+Z
C) Ctrl+Break
D) Ctrl+D
Rätt svar: A
8. Vilket kommando används för att skapa en katalog i CLI?
A) mkdir
B) rmdir
C) md
D) >
Rätt svar: A
9. Vilket alternativ beskriver skillnaden mellan mkdir och rmdir? (två rätt svar)
A) mkdir skapar en katalog; rmdir tar bort
B) mkdir används i batch; rmdir endast i Linux
C) Båda raderar filer; endast mkdir skapar kataloger
D) Ingen av dem raderar filer
Rätt svar: A
10. Vilket kommando används för att kopiera filer rekursivt i batch?
A) copy /S
B) xcopy /S
C) move /R
D) del /S
Rätt svar: B
11. Vilket kommando används för att flytta filer?
A) copy
B) move
C) rename
D) xcopy
Rätt svar: B
12. Vad gör kommandot del?
A) Skapar en ny fil
B) Tar bort filer
C) Döljer filer
D) Flyttar filer
Rätt svar: B
13. Vilken batch-skript-rad används för att stänga av datorn?
A) shutdown /s
B) reboot
C) exit
D) poweroff
Rätt svar: A
14. Vad gör @echo off i en batch-fil?
A) Aktiverar utskrift av varje kommando
B) Dölj kommando-utdata
C) Startar en ny kommandotolk
D) Kör automatisk uppgift
Rätt svar: B
15. Vilken filändelse används för batch-skript?
A) .bat
B) .exe
C) .cmd
D) .sh
Rätt svar: A
16. Vilket kommando används för att visa innehållet i en katalog i batch-skript?
A) ls
B) dir
C) show
D) list
Rätt svar: B
17. Vilket kommando används för att visa aktuell arbetskatalog?
A) pwd
B) cd
C) dir
D) chdir
Rätt svar: B
18. Vilket kommando används för att få hjälp om ett kommando i CMD?
A) help
B) info
C) man
D) ?
Rätt svar: A
19. Vilket kommando används för att visa nätverksstatus i batch-skript?
A) ipconfig
B) netstat
C) netsh
D) ping
Rätt svar: C
20. Vilket kommando används för att köra ett program i bakgrunden (kör i bakgrunden)?
A) start /b
B) run
C) exec
D) launch
Rätt svar: A

Del 2: Batch-filer och skript-logik (Frågor 21–40)

21. Vad gör kommandot for /f i batch-skript? (två rätt svar)
A) Parsar textfiler
B) Skapar användare
C) Långsamt kör scriptet
D) Utför op-gånger på varje rad i en fil
Rätt svar: A, D
22. Vilken rad används för att avsluta en batch-fil?
A) exit
B) end
C) stop
D) quit
Rätt svar: A
23. Vilket är syftet med @echo off i batch-skript?
A) Dölj körningens log
B) Öka hastigheten
C) Ändra färg på texten
D) Starta om datorn
Rätt svar: A
24. Vilket kommando används för att visa filinnehåll i batch?
A) type
B) cat
C) echo
D) show
Rätt svar: A
25. Vilka två av följande används ofta tillsammans i batch-filer för loggning? (två rätt)
A) echo >> log.txt
B) log.txt = append
C) set /p
D) pause
Rätt svar: A, C
26. Vilket kommando används för att ta bort en katalog och dess innehåll?
A) rmdir /s
B) rm -r
C) del /f /s
D) erase /r
Rätt svar: A
27. Vilket kommando används för att visa systeminformation i batch-skript?
A) systeminfo
B) info
C) sysinfo
D) ver
Rätt svar: A
28. Vilket av följande används för att köra en batch-fil vid uppstart i Windows?
A) Starta från Start -> Debug
B) Lägg till i Autostart
C) Schemaläggning i Task Scheduler
D) Både B och C är rätt
Rätt svar: D
29. Vilket kommando används för att kopiera en hel mapprekursivt i batch-skript?
A) copy /E
B) xcopy /E
C) robocopy /MIR
D) B och C
Rätt svar: D
30. Vilket program används ofta för att redigera batch-filer?
A) Notepad
B) Word
C) Excel
D) Paint
Rätt svar: A
31. Vilket av följande uttryck är sant om batch-skriptens variabler innehåll? (två rätt)
A) Variabler används utan att deklarera
B) Variabler sätts med set x=value
C) Variabler är alltid strängar
D) Variabler kan användas i if-satser
Rätt svar: B, D
32. Vilket av följande används för att kontrollera returvärde i batch-skript?
A) if %errorlevel%==0
B) if %errorlevel% = 0
C) if defined error
D) if errorlevel==0
Rätt svar: A
33. Vilket kommando kan användas för att läsa en textfil rad för rad i batch?
A) for /f
B) while
C) read
D) scan
Rätt svar: A
34. Vad gör kommandot echo off i batch-skript?
A) Skriver varje rad till skärmen
B) Dölj utskriften av kommandon
C) Startar en ny process
D) Avslutar programmet
Rätt svar: B
35. Vilket av följande är en vanlig metod för att skapa en enkel batch-fil?
A) Skriv i Notepad och spara som .bat
B) Skriv i Word och spara som .txt
C) Skriv i Excel och spara som .csv
D) Skriv i Notepad och spara som .txt
Rätt svar: A
36. Vilket kommando används för att byta arbetskatalog i batch-skript?
A) cd
B) chdir
C) dir
D) set
Rätt svar: A
37. Vilket av följande används för att hantera arkiv i batch-skript?
A) zip
B) tar
C) xcopy
D) archive
Rätt svar: C
38. Vilket kommando används för att visa användarkonton i Windows?
A) net user
B) users
C) whoami
D) account
Rätt svar: A
39. Vilket kommando används för att uppdatera miljövariabler i en batch-skript?
A) set
B) env
C) export
D) var
Rätt svar: A
40. Vilket av följande är en vanlig felkälla i batch-skript?
A) Fel i radslut
B) Fel i parenteser i IF/ FOR
C) Fel i citattecken
D) Alla ovanstående
Rätt svar: D

Frågor 41–50 (Avancerade batch-skript och praktiska övningar)

41. Vilket kommando används för att skapa en katalog och först skicka in i den nya katalogen i samma rad?
A) mkdir ny \&\& cd ny
B) mkdir ny; cd ny
C) cd ny mkdir
D) create ny
Rätt svar: A
42. Vilket kommando används för att klippa ut vissa filer till en annan plats i batch?
A) copy
B) move
C) cut
D) paste
Rätt svar: B
43. Vad gör kommandot label i batch-skript?
A) Ändrar volymens etikett
B) Låter dig märka filer
C) Laddar etiketter från nätverk
D) Byter filnamn
Rätt svar: A
44. Vilket av följande är en användbar teknik för att skriva loggfiler i batch-skript?
A) echo log >> logfile.txt
B) log > logfile.txt
C) write log.txt
D) log << EOF
Rätt svar: A
45. Vilket är ett bra sätt att felsöka batch-skript?
A) Använda pause och visa variabler
B) Köra utan felhantering
C) Ingen logg
D) Bara köra som admin
Rätt svar: A
46. Vilket kommando används för att läsa inkommande parametrar i batch-skript? (två rätt)
A) %1
B) %a
C) %\*
D) %ARG%
Rätt svar: A, C
47. Vilket filändelse används vanligtvis för batch-skript?
A) .bat
B) .sh
C) .ps1
D) .cmd
Rätt svar: A
48. Vad gör kommandot 'pause' i batch-skript?
A) Pausar exekveringen tills användare trycker en tangent
B) Fördröjer start med 5 sekunder
C) Avslutar skriptet
D) Väntar på nätverket
Rätt svar: A
49. Vilket av följande är en typisk struktur i en batch-skript med en IF-sats?
A) if EXIST file.txt ( echo found )
B) if file.txt exists ( echo ok )
C) if %errorlevel%==0 ( echo OK )
D) if true ( echo true )
Rätt svar: A, C
50. Vilket kommando används för att skriva över en befintlig fil?
A) echo > file.txt
B) del > file.txt
C) rem > file.txt
D) copy /Y source.txt dest.txt
Rätt svar: A

