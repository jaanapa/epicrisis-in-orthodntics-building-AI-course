# Epikriisi-oikomisessa
Building AI course project
AI-AVUSTEINEN EPIKRIISI OIKOMISESSA  final project for the Building AI course

## Summary

Suomessa arviolta yli 20000 uutta oikomispotilasta vuodessa julkisella puolella.Oikomishoito kestää yleensä 1-6 vuotta sisältäen useita käyntejä.
Epikriisi on loppuyhteenveto tehdystä hoidosta ja sen kirjoittamiseen menee paljon työaikaa, koska tarvittavat tiedot etsitään useiden vuosien merkinnöistä.
AI menetelmien avulla epikriisin teko nopeutuisi . 


## Background

AI- metodeilla olisi mahdollista löytää potilaskäyntien kirjauksista oleelliset kohdat hoidon kulusta. Oikomista tekevien (lähinnä julkinen puoli)hammaslääkäreiden työaikaa
säästyisi muille tehtäville. 

This is how you make a list, if you need one:
* problem 1 Kirjattava, milloin alkutarkastus ollut, diagnoosi ja hoitosuunnitelma
* problem 2 Kirjattava, mikä koje vuorollaan ollut ja kuinka pitkään se on ollut käytössä 
(yleensä ollut useita eri kojeita peräkkäin. Esim. oikomislevy, kiinteätkojeet, retentiolevy)
* problem 3 Kirjattava, milloin lopputarkastus on ollut ja hoidon lopputulos


## How is it used?

Jokaiseen hoitokäyntiin kirjataan tiedot käynnistä, sen sisällöstä ja lisäksi erikseen toimenpidekoodit. Alkutarkastus ja lopputarkastus tulevat omille erillisille
lomakkeille (tai kohtiin). Kirjattujen toimenpidekoodien avulla voitaisiin etsiä ne käynnit, jolloin epikriisin kannalta olennaista on tapahtunut (esim. irtokojeen sovitus 
tai kiinteän kojeen purkaminen- toimenpidekoodit). Tämä tapahtuisi Bayer´s classifiersin tapaisesti.Natural Language Processing avulla poimittaisiin oikomislaitteiden nimet
ja myös alku- ja lopputarkastusten tiedot. Tärkeintä olisi löytää suuresta materiaalimäärästä ne käynnit, jolloin uusi koje tullut käyttöön ja vanhan käyttö loppunut.Lisäksi
tietysti kyseisen oikomiskojeen nimi.
Oikomista tekevät hammaslääkärit käyttäisivät ohjelmaa ja se olisi saatavana nykyisiin potilastietojärjestelmiin sopivana (on eri järjestelmiä käytössä, mutta toimenpidekoodit
ovat samat)

## Challenges

Koska en hallitse koodausta, on tämä projekti vain ajatuksen tasolla. En myöskään tiedä, onko ongelma sellainen, että sen ratkaisu olisi taloudellisesti kannataavaa kunnille. 
Jos uusi ohjelma olisi kallis ja hankala saada toimimaan nykyisissä tietojärjestelmissä, ei rahoitusta varmasti löydy. Lisäksi osa potilaan tiedoista voi nyt sijaita eri 
jäejestelmässä (vanhemmassa), kuin uudemmat tiedot. Siksi toimenpidekoodit olisivat lähtökohtana, ne eivät ole muuttuneet.

## What next?

Ehkä LifeCaren tai Appotin tai vastaavien potilastietojarjestelmien tekijät joskus kiinnostuvat ideasta...

