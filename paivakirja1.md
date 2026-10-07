# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Gitin perusteet olivate helppoja sillä olen käyttänyt gittiä jo yli 3 vuotta. Olen päässyt tekemään paljon näitä peruskomentoja. Uusin komento oli minulle git switch. tämä on uusi käytäntö minulle sillä olen käyttänyt vanhaa git checkout komentoa, joka on edelleen vielä käytössä. Halusin tässä harjoituksessa oppia käyttämään tätä uutta versiota. 
Myös haarojen käyttä oli minulle selkeää tässä tehtävässä. 

Kokonaisuudessa tämä oli kyllä erittäin kattava ja on aina hyvä käydä näitä perustoimintoja läpi, sillä ne saattavat unohtua, jos ei niitä pääse käyttämään. 

Täysin uusi komento minulle oli tämä tag komento, joka tulee olemaan hyödyllinen. tämä auttaa minua visualisoimaan jos joudun tarkastelemaan muutokisia. Minulla on välillä käynyt niin että olen tehnyt paljon committejä jotakin tiettyä featuria varten ja kun olen joututnut tarkastelemaan historiaa niin menen usein sekaisin missä on mitäkin.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git add .     Lisää kaikki nykyise muutokset staging alueelle.
git commit -m   tallentaa muutokset git historiaan tietyllä viestillä
git log (--stat --oneline)      näyttää repon commit historian eri muodoissa
git mv          Siirtää tai nimeää uudelleen jonkin tiedoston
git rm          Poistaa tiedoston ja merkkaa sen gittiin
git tag         Lisää commitille tunnisteen
git switch -    Palaa edelliseen haaraan
git reset (--hard) Poistaa tiedoston styaging alueelta
git restore     Hylkää tiedostoon tehdyt tallentamattomat muutokset
git brach       Näyttää  repositorian haarat ja aktiivisen haaran 
git switch -c ...   Luo uuden haaran ja siirtyy siihen
git merge --no--ff- yhdistää haaran kyseisen haaraan ja tekee erillisen merge commitin
