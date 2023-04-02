# Kansanopisto-tsoha
Database app practice using Flask+PostGreSQL

Tavoitteena on luoda tietokantasovellus kuvitteelliselle kansanopistolle kurssien ja kurssikokonaisuuksien luomiseen ja suoritusten rekisteröintiin ja seurantaan. Käyttäjiä on sovelluksella kahdentasoisia: opettajat ja opiskelijat.

HUOM! On ollut vähän vaikeuksia sekä PostgreSQL:n, että Gitin käytön kanssa, joten ei ole toimivaa pohjaa valmiina vielä! (2.4.)

## Ominaisuudet
- opiskelijat voivat rekisteröityä/kirjautua sisään
- opiskelijat voivat ilmoittautua kursseille, joista saa opintopisteitä ja suorituksia
- opiskelijat voivat nähdä suorittamansa kurssit, opintopisteiden määrän ja arvosanojensa keskiarvon
- opettajat voivat rekisteröityä/kirjautua sisään
- opettajat voivat luoda uusia koulutusohjelmia ja kursseja
- opettajat voivat rekisteröidä kurssisuorituksia
- opettajat voivat nähdä listauksen vetämistään kursseista

## Tietokantataulut:
- courses (nimi, kurssitunnus, kuvaus, vetäjä, opintopisteet, koulutusohjelma)
- students (nimi, opnro, op:t)
- teachers(nimi, tunnus/opnro)
- programs (nimi, kuvaus, vastuuopettaja, opintopisteitä)
- submits (kurssi, opiskelija, kesken/valmis, arvosana, op:t)


 HUOM! On ollut vähän vaikeuksia sekä PostgreSQL:n, että Gitin käytön kanssa, joten ei ole toimivaa pohjaa valmiina vielä! (2.4.)
