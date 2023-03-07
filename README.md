# Diplomska naloga - uporabniške zgodbe
<details>
<summary><b>Glavni administrator</b></summary>

## 1. Kreiranje administratorja stavbe

> **Prioriteta:** 1
> </br>**Ocena:** 1
> </br>**Zgodba:** Glavni administrator lahko kreira administratorja stavbe in mu povezavo za registracijo pošlje na e-mail.
> </br>**Opombe:** /
> </br>**Sprejemni testi:** Administratorju stavbe določi le email.

## 2. Dodajanje stavbe

> **Prioriteta:** 1
> **</br>Ocena:** 2
> **</br>Zgodba:** Glavni administrator lahko kreira in upravlja s stavbo.
> **</br>Opombe:** Glavni administrator je le en.
> **</br>Sprejemni testi:** Za kreiranje stavbe so pomembni: Naslov stavbe, poštna številka, administrator stavbe in podatki o njej.

</details>

<details>
<summary><b>Administrator stavbe</b></summary>

## 1. Registracija

> **Prioriteta:** 1
> **</br>Ocena:** 1
> **</br>Zgodba:** Administrator stavbe na mail dobi podatke za prijavo v aplikacijo. Ob prvi prijavi, ga sistem pozove v spremembo gesla.
> **</br>Opombe:** Za uporabo aplikacije, si mora geslo spremeniti.
> **</br>Sprejemni testi:** Geslo mora biti dovolj zahtevno (vsaj 6 znakov, vsaj ena velika črka in vsaj 2 števili in en znak).

## 2. Vnos podatkov o stavbi

> **Prioriteta:** 2
> **</br>Ocena:** 2
> **</br>Zgodba:** Administrator stavbe lahko kadarkoli spremeni podatke o stavbi.
> **</br>Opombe:** /
> **</br>Sprejemni testi:** Urejanje polnilnic, podjetij in podatkov o stavbi

## 3. Dodajanje polnilnic

> **Prioriteta:** 2
> **</br>Ocena:** 2
> **</br>Zgodba:** Administrator stavbe lahko kadarkoli doda polnilnico.
> **</br>Opombe:** /
> **</br>Sprejemni testi:** Polnilnica vsebuje podatke o moči, lokaciji, maks število zaporednih terminov, maks ur polnjenja in kateremu podjetju pripada. Ustvari lahko tudi polnilnico ki pripada le gostu (uporabniku, ki ni registriran).

## 4. Kreiranje administratorja podjetja

> **Prioriteta:** 1
> </br>**Ocena:** 4
> </br>**Zgodba:** Administrator stavbe lahko kreira administratorja podjetja in mu povezavo za registracijo pošlje na e-mail.
> </br>**Opombe:** /
> </br>**Sprejemni testi:** Administratorju podjetja določi le email.

## 5. Dodajanje podjetja

> **Prioriteta:** 1
> **</br>Ocena:** 2
> **</br>Zgodba:** Administrator stavbe lahko upravlja s podjetjem (s polnilnicami, ki pripadajo).
> **</br>Opombe:** Stavba ima le enega administratorja stavbe.
> **</br>Sprejemni testi:** Za kreiranje stavbe so pomembni: Nadstropje/soba podjetja in podatki o polnilnicah.
</details>

<details>
<summary><b>Administrator podjetja</b></summary>

## 1. Registracija

> **Prioriteta:** 1
> **</br>Ocena:** 1
> **</br>Zgodba:** Administrator podjetja na mail dobi podatke za prijavo v aplikacijo. Ob prvi prijavi, ga sistem pozove v spremembo gesla.
> **</br>Opombe:** Za uporabo aplikacije, si mora geslo spremeniti.
> **</br>Sprejemni testi:** Geslo mora biti dovolj zahtevno (vsaj 6 znakov, vsaj ena velika črka in vsaj 2 števili in en znak).

## 2. Vnos podatkov podjetja

> **Prioriteta:** 1
> **</br>Ocena:** 2
> **</br>Zgodba:** Administrator podjetja lahko upravlja s podjetjem (s polnilnicami, ki pripadajo).
> **</br>Opombe:** Podjetje ima le enega administratorja podjetja.
> **</br>Sprejemni testi:** Spreminja lahko: Nadstropje/soba podjetja, maks število zaporednih terminov, maks ur polnjenja.

## 3. Kreiranje uporabnika

> **Prioriteta:** 1
> </br>**Ocena:** 4
> </br>**Zgodba:** Administrator podjetja lahko kreira uporabnika in mu povezavo za registracijo pošlje na e-mail.
> </br>**Opombe:** /
> </br>**Sprejemni testi:** Uporabniku določi le email.

## 4. Sproščanje terminov

> **Prioriteta:** 1
> </br>**Ocena:** 4
> </br>**Zgodba:** Administrator podjetja, lahko kadarkoli sprosti termin.
> </br>**Opombe:** /
> </br>**Sprejemni testi:** Uporabnik z rezerviranim terminom, dobi email o spremembi.

## 5. Izdaja RFID kartice

> **Prioriteta:** 1
> </br>**Ocena:** 4
> </br>**Zgodba:** Administrator podjetja, uporabniku generira rfid kartico
> </br>**Opombe:** /
> </br>**Sprejemni testi:** Uporabnik z rfid kartico lahko uporablja polnilnico.
</details>
<details>
<summary><b>Uporabnik</b></summary>

## 1. Registracija

> **Prioriteta:** 1
> **</br>Ocena:** 1
> **</br>Zgodba:** Uporabnik na mail dobi podatke za prijavo v aplikacijo. Ob prvi prijavi, ga sistem pozove v spremembo gesla.
> **</br>Opombe:** Za uporabo aplikacije, si mora geslo spremeniti.
> **</br>Sprejemni testi:** Geslo mora biti dovolj zahtevno (vsaj 6 znakov, vsaj ena velika črka in vsaj 2 števili in en znak).

## 2. Rezervacija termina

> **Prioriteta:** 1
> **</br>Ocena:** 1
> **</br>Zgodba:** Uporabnik si lahko rezervira termin.
> **</br>Opombe:** Če je termin zasede, ga aplikacija doda v čakalno vrsto.
> **</br>Sprejemni testi:** Termini morajo zadoščati omejitvam polnilnice (št. zaproednih rezervacij)

## 3. Sprostitev termina

> **Prioriteta:** 1
> **</br>Ocena:** 1
> **</br>Zgodba:** Uporabnik si lahko sprosti termin.
> **</br>Opombe:** /
> **</br>Sprejemni testi:** Termin dobi naslednji v čakalni vrsti.

## 4. Prevzem termina

> **Prioriteta:** 1
> **</br>Ocena:** 1
> **</br>Zgodba:** Uporabnik lahko v primeru odpovedu drugega uporabnika termin prevzame.
> **</br>Opombe:** Uporabnik mora biti v času sprostitve v čakalni vrsti za termin.
> **</br>Sprejemni testi:** O prevzemu termina je obveščen preko emaila.
</details>
<details>
<summary><b>Gost</b></summary>

## 1. Rezervacija termina

> **Prioriteta:** 1
> **</br>Ocena:** 1
> **</br>Zgodba:** Gost si lahko rezervira termin.
> **</br>Opombe:** Če je termin zasede, ga aplikacija doda v čakalno vrsto. Polnilnica za goste je posebaj in je vidna brez prijave.
> **</br>Sprejemni testi:** Termini morajo zadoščati omejitvam polnilnice (št. zaproednih rezervacij)
</details>
