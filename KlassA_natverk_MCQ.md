# Klass A nätverk – MCQ (baserat på L4 info.docx.pdf)

Instruktion: Välj rätt svar (A–D). Frågor som är markerade med **TVÅ RÄTTA** har exakt två korrekta alternativ.

## Frågor

1) I ett klass A-nätverk används hur många bitar till nätverksnumret?
A) 8 bitar
B) 16 bitar
C) 24 bitar
D) 32 bitar

2) I ett klass A-nätverk används hur många bitar till hostnumret?
A) 8 bitar
B) 16 bitar
C) 24 bitar
D) 32 bitar

3) Vilken analogi används i dokumentet för att förklara nätverksnummer och hostnummer?
A) Telefonnummer
B) Postadress (gata och husnummer)
C) Personnummer
D) Bankkonto

4) Vilken klass A-exempeladress nämns i dokumentet?
A) 192.168.1.10
B) 10.0.0.1
C) 150.100.50.25
D) 210.100.20.35

5) Vilket påstående stämmer om nätverksnumret i klass A enligt dokumentet?
A) Det är de sista 8 bitarna
B) Det är den första oktetten (första segmentet)
C) Det är alltid de sista 16 bitarna
D) Det är alltid den tredje oktetten

6) Dokumentet säger att det teoretiskt finns 128 möjliga nätverksnummer i klass A (0–127). Vilka två är reserverade och används inte för vanliga nätverk? (**TVÅ RÄTTA**)
A) 0
B) 10
C) 127
D) 126

7) Vad betyder 0.0.0.0 enligt dokumentet?
A) Loopback/localhost
B) Reserverat för routing och betyder ungefär att anslutning till detta nätverk inte finns ännu
C) Broadcast-adress för alla nätverk
D) Privat adress som inte routas

8) Vad är 127.0.0.0 reserverat för?
A) Routing
B) Loopback-adresser
C) Broadcast
D) Multicast

9) Vilken loopback-adress nämns som den vanligaste?
A) 10.0.0.1
B) 127.0.0.1
C) 192.168.1.255
D) 0.0.0.0

10) Enligt dokumentet: hur många användbara nätverksnummer finns i klass A när 0 och 127 räknas bort?
A) 124
B) 125
C) 126
D) 127

11) Vilket intervall anges som de användbara klass A-nätverksnumren?
A) 0 till 127
B) 1 till 126
C) 10 till 126
D) 128 till 191

12) Vad är en nätverksadress (nätverks-ID) enligt dokumentet?
A) En adress där alla host-bitar är satta till 0
B) En adress som alltid slutar på .255
C) En adress som alltid används av routern
D) En adress som kan tilldelas en valfri host

13) Vilket påstående stämmer om nätverksadressen enligt dokumentet?
A) Den kan tilldelas en enhet
B) Den representerar hela nätverket och kan inte tilldelas en enhet
C) Den används bara för broadcast
D) Den är alltid samma som loopback

14) I exemplet 192.168.1.0/24, vilka adresser kan tilldelas enheter enligt dokumentet?
A) 192.168.1.0 till 192.168.1.255
B) 192.168.1.1 till 192.168.1.254
C) 192.168.1.2 till 192.168.1.253
D) 192.168.1.10 till 192.168.1.255

15) Varför är 192.168.1.255 broadcast-adressen i ett /24-nät enligt dokumentet?
A) För att alla host-bitar (sista 8 bitarna) sätts till 1
B) För att alla nätverksbitar sätts till 0
C) För att den alltid är en loopback-adress
D) För att den alltid är reserverad för routing

16) Vad händer när ett paket skickas till broadcast-adressen enligt dokumentet?
A) Bara routern tar emot det
B) Alla enheter i nätverket tar emot det
C) Ingen tar emot det
D) Endast DNS-servern tar emot det

17) Vad används ARP (Address Resolution Protocol) till enligt dokumentet?
A) Att översätta domännamn till IP
B) Att hitta en annan enhets fysiska MAC-adress på samma nätverk
C) Att kryptera IP-trafik
D) Att routa paket mellan nätverk

18) Enligt dokumentet: var skickas en ARP-begäran när en enhet behöver ta reda på MAC-adressen?
A) Till nätverksadressen
B) Till broadcast-adressen
C) Till loopback-adressen
D) Till 0.0.0.0

19) Vilket påstående beskriver en korrekt subnätmask enligt dokumentet?
A) Det får finnas en blandning av 1:or och 0:or inom en oktett
B) 1:orna kommer först (nätverk) och 0:orna kommer sen (host)
C) 0:orna kommer först och 1:orna sen
D) Det spelar ingen roll i vilken ordning bitarna ligger

20) Vilken subnätmask ges som exempel på en **felaktig** subnätmask i dokumentet?
A) 255.255.255.0
B) 255.0.0.0
C) 255.255.255.200
D) 255.255.0.0

21) Vad är CIDR-formen för subnätmasken 255.0.0.0 enligt dokumentet?
A) /8
B) /16
C) /24
D) /32

22) Vad betyder subnätmasken 255.0.0.0 enligt dokumentet?
A) 16 bitar nätverk, 16 bitar host
B) 8 bitar nätverk, 24 bitar host
C) 24 bitar nätverk, 8 bitar host
D) 32 bitar nätverk, 0 bitar host

23) Vad är CIDR-formen för subnätmasken 255.255.0.0 enligt dokumentet?
A) /8
B) /12
C) /16
D) /24

24) I dokumentets exempel för 255.0.0.0 och IP-adressen 10.0.0.1, vilket nätverk anges?
A) 10.0.0.0
B) 10.0.0.1
C) 10.255.255.255
D) 0.0.0.0

25) I samma exempel (255.0.0.0 och 10.0.0.1), vilken hostdel anges?
A) 10.0.0.0
B) 0.0.0.0
C) 0.0.0.1
D) 255.0.0.0

26) Dokumentet visar en tabell över möjliga oktettvärden i en subnätmask. Vilket av följande finns i listan?
A) 250
B) 254
C) 200
D) 201

27) Vilken formel ges för att beräkna antalet möjliga host-ID?
A) 2^n + 2
B) 2^n − 2
C) 2n − 2
D) n^2 − 2

28) Varför subtraherar man 2 i formeln enligt dokumentet? (**TVÅ RÄTTA**)
A) En adress används för nätverksadressen (alla host-bitar 0)
B) En adress används för broadcast-adressen (alla host-bitar 1)
C) En adress används alltid för loopback
D) En adress används alltid för routing

29) I exemplet 192.168.1.10 med subnätmask 255.255.255.0, vad anges som nätverksdelen (nätet)?
A) 192.168.1.10
B) 192.168.1.1
C) 192.168.1.0
D) 192.168.1.255

30) I samma exempel (192.168.1.10 /24), vad anges som värddelen (hostdelen)?
A) 192
B) 168
C) 1
D) 10

## Facit
1 A
2 C
3 B
4 B
5 B
6 A,C
7 B
8 B
9 B
10 C
11 B
12 A
13 B
14 B
15 A
16 B
17 B
18 B
19 B
20 C
21 A
22 B
23 C
24 A
25 C
26 B
27 B
28 A,B
29 C
30 D

---

**PDF:** Öppna denna fil och välj *Skriv ut → Spara som PDF*.