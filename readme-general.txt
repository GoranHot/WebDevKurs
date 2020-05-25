HTTP - Protokol koji omogucava komunikaciju na web-u.

Request Method: GET
(instrukcija koju klijent salje serveru)

Server Code: 200 
(tip koda kao poruke... 200 da je uspjesno, 502 bad gateway, 404 - not found etc.)

Remote Adress: 99.86.243.79:443
(remote adressa sajta kojem pristupamo)

API - Applicaiton Programming Interface
Veza izmedju slojeva aplikacije, vise djelova aplikacije. Kako komponente komuniciraju jedne izmedju drugih.
npr. Na serveru imate dio koda koji ceka od klijenta da bude pozvan, klijent posalje zahtjev kroz API npr funkciju "user", koja ce iz servera da vrati sve usere,
tj. listu svih korisnika.

Front-End Framework:
Angular, React, Vue, Svelte

Back-End Framework:
Node.js (Javascript)
Django (Python)
Laravel (PHP)
GO

---------------
IP - Adresa uredjaja na mrezi
DNS - Imenik interneta
Search Engine - Pretrazivac web-adressa
ISP - Internet Servis Provajder
Proxy - Preusmjerivac
VPN - Virtuelna Privatna Mreza
Cache - Privremeno skladiste
Ostalo - HTTPs, Paketi, TCP


TCP - Transmission Control Protocol, radi sa Internet Protokolom (IP), koji definise kako kompjuteri salju pakete podataka jedan drugom.
To je standard koji definise kako da se uspostavi mrezna komunikacija kroz koju ce aplikacije moci da izmjene podatke.

Hexadecimal are base 16 numbers, 0-9 is self-explanatory, and A-F is for numbers ten to fifteen. And is easiest way to translate bites which range from 
00000000 to 11111111, and variations between.
Hexadecimal is sixdigit when used in colors, so that it can denote up to 16mil colors (16 to the power of 6).

RGB system used in modern display techonology is additive, as it adds and mixes the light sources to produce color.
In CSS, it's based on three levels of Red, Green and Blue in 256 increments to produce the same 16mil color pallet ie. (256, 0, 0) denotes pure red.
From Hexadecimal it's 16x16 (two leters 0F) and it gives 256. Smart, eh.

CMYK system, used in printers uses subtractive color, being that it's based on prediction of how our eyes will perceive the light after it reflects off of something, ie. paper.
It predicts how the spectral power distribution of light after it passes through successive layers of partially absorbing media.

-----------------
## Elementi
Postoje dva tipa elemenata:
<tag>...</tag> - pair elementi HTML dokumenta
<tag/> - "self-closing tags" ili "void tags", zovu ih i empty elements
U HTML5, slash "/" je opcionalan u self-closing tagu.

## Atributi
Pruzaju dodatne informacije o elementu. Definise se u startnom tagu.
<tag attribute="value"> Content </tag>

<p title="I'm a tooltip"> - title je key, value je I'm a tooltip </p>
<img src="img_girl.jpg" alt="Girl with a jacket">
<input required />
<p style="color:red">I am a paragraph</p>
<a href="https://www.w3schools.com">Click here</a>

Neki atributi npr. "required" nemaju potrebe za navodnicima il' sl.
SEO - Search Engine Optimization

NE koristi headings tagove da ucinis tekst vecim il' da bi bio boldovan. Lose je za SEO. Koristi CSS.

Font weight za boldovanje.

<pre> tag </pre> - Defines preformatted text, element is displayed in a fixed-width font, and the text preserves both spaces and line breaks. The text will be displayed exactly as written in the HTML source code.

## Formatiranje teksta

<b> - Bold tekst
<strong> - Bitan tekst - bolji za SEO
<i> - Italic tekst 
<em> - Naglašen (Emphasized) tekst - bolji za SEO
<mark> - Markiran tekst 
<small> - Mali tekst 
<del> - Precrtan tekst 
<ins> - Podvučen (Inserted) tekst 
<sub> - Subscript tekst 
<sup> - Superscript tekst 
<q> - citat, dodaje “ ” za tekst u <q> ... </q>


## URL Struktura
Tip Protokola:
http - popularan i dalje, komunikacija nije enkriptovana
https - za sigurnije web strane, komunikacija enkriptovana
ftp - upload i download fajlova
file - lokalno, na vašem računaru

prefix - prefiks domena (za http default je www)
domain - definiše ime domena (w3schools.com u našem primjeru)
port - definiše broj porta na serveru/hostu (default za http je 80)
path - definiše putanju na serveru (ako se izostavi, onda je podrazumijevano root direktorijum sajta)
filename - definiše ime dokumenta ili resursa

Unutar URL-a " " space se gledao kao %20.