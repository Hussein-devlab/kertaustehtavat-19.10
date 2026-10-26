# Kertaustehtävät 19.10.

Python-kertaustehtävät, joissa harjoitellaan `if - elif - else` -rakennetta, `while`- ja `for`-silmukoita sekä listoja. Jokainen tehtävä on omassa tiedostossaan, ja koodissa on kommentit, jotka selittävät mitä ohjelma tekee.

Ohjelman voi ajaa komennolla:

```
python tehtava1.py
```

## if - elif - else

### Tehtävä 1 – Päiväpalkka (`tehtava1.py`)
Ohjelma kysyy tuntipalkan, tehdyt tunnit ja viikonpäivän. Päiväpalkka lasketaan kertomalla tuntipalkka tehdyillä tunneilla. Jos päivä on sunnuntai, tuntipalkka kerrotaan ensin kahdella. Viikonpäivä muutetaan pieniksi kirjaimiksi `lower()`-funktiolla, jotta sekä "Sunnuntai" että "sunnuntai" toimivat.

### Tehtävä 2 – Jaollisuus (`tehtava2.py`)
Ohjelma kysyy kokonaisluvun ja tarkistaa jakojäännösoperaattorilla `%`, onko luku jaollinen kolmella, viidellä vai molemmilla. Ehto "molemmilla" tarkistetaan ensimmäisenä, koska muuten esimerkiksi luku 15 jäisi jo ensimmäiseen ehtoon ("kolmella jaollinen").

## while

### Tehtävä 3 – Tuotantolinja (`tehtava3.py`)
Ohjelma tulostaa "Tuote valmistettu!" ja kysyy "Jatketaanko tuotantoa?". Silmukka jatkuu niin kauan, kunnes käyttäjä vastaa "Ei". Lopuksi tulostetaan "Tuotanto lopetettu!".

### Tehtävä 4 – Neliöjuuret (`tehtava4.py`)
Ohjelma kysyy kokonaislukuja. Negatiivisesta luvusta tulostetaan "Virheellinen numero" ja positiivisesta luvusta lasketaan neliöjuuri `math`-kirjaston `sqrt`-funktiolla. Kun käyttäjä syöttää nollan, silmukka päättyy.

### Tehtävä 5 – Tarina (`tehtava5.py`)
Ohjelma pyytää sanoja ja lisää ne tarinaan välilyönnillä erotettuna. Kun käyttäjä kirjoittaa "loppu", ohjelma tulostaa valmiin tarinan. **Bonus** on tehty: ohjelma muistaa edellisen sanan, ja silmukka loppuu myös, jos sama sana syötetään kahdesti peräkkäin.

## Listarakenne

### Tehtävä 6 – Lista ja järjestäminen (`tehtava6.py`)
Ohjelma pyytää lukuja ja lisää ne listaan `append()`-funktiolla. Jokaisen lisäyksen jälkeen lista tulostetaan lisäysjärjestyksessä sekä pienimmästä suurimpaan järjestettynä `sorted()`-funktiolla. Nolla lopettaa ohjelman, eikä sitä lisätä listaan.

### Tehtävä 7 – Pitkät sanat (`tehtava7.py`)
Ohjelmassa on itse tehty lista sanoja. Ohjelma käy sanat läpi ja laskee `len()`-funktion avulla, kuinka monessa sanassa on enemmän kuin 5 kirjainta.

## for

### Tehtävä 8 – Valmistuskustannukset (`tehtava8.py`)
Listassa on viiden tuotteen valmistuskustannukset. Ohjelma käy ne läpi `for`-silmukalla, tulostaa jokaisen kustannuksen ja laskee samalla summan. Lopuksi tulostetaan kokonaiskustannus (53.0 €).

### Tehtävä 9 – Tehtaan tuotanto (`tehtava9.py`)
Ohjelma kysyy, mitä tuotetta valmistetaan ja kuinka monta. Tuotteiden nimet ja määrät tallennetaan kahteen eri listaan. Kysymistä jatketaan niin kauan kuin käyttäjä vastaa "Kyllä". Kun käyttäjä vastaa "Ei", ohjelma tulostaa "Tuotanto lopetettu!" ja käy listat läpi `for`-silmukalla tulostaen jokaisen tuotteen ja sen määrän (esim. "Pöytä: 20 kpl").
