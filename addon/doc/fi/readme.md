# Leikepöydän sisällön käsittelijä #

*	Tekijä: Noelia Ruiz Martínez
*	Lataa [vakaa versio][1]
*	Lataa [kehitysversio][2]

Tätä lisäosaa käytetään tekstin lisäämiseen leikepöydälle, mistä voi olla
hyötyä, jos haluat yhdistää tekstin eri osia yhdeksi kokonaisuudeksi
liittääksesi sen jonnekin.  Leikepöydän sisällön voi myös tyhjentää.

## Näppäinkomennot ##
*	NVDA+Windows+C: Lisää valittu/tarkastelukohdistimella merkitty teksti tai
  MathML-objekteja kuvaavat Unicode-pistekirjoitusmerkit leikepöydälle.
*	NVDA+Windows+X: Tyhjennä leikepöydän sisältö.
*	NVDA+Windows+F9: Merkitse tarkastelukohdistimen nykyinen sijainti leikepöydälle kopioitavan tekstin alkukohdaksi. Tekstiä ei lisätä, jos käytät näppäinkomentoa NVDA+F9.
*	Ei määritetty: Kopioi tai leikkaa leikepöydälle sekä pyytää vaihtoehtoisesti vahvistuksen toiminnon suorittamiselle.

Huomaa, että edellä mainittuja komentoja on mahdollista muuttaa kohdasta
NVDA-valikko -> Asetukset -> Syötekomennot ja valitsemalla avautuvasta
valintaikkunasta Tekstin tarkastelu -kategoria.

## Asetukset-valikko ##
*	Leikepöydän sisällön käsittelijä: Mahdollistaa erottimen määrittämisen, jota voidaan käyttää tekstilohkojen etsimiseen, kun lisätty tekstikokonaisuus on ensin liitetty jonnekin.
On myös mahdollista valita, liitetäänkö lisätty teksti jo leikepöydällä olevan tekstin loppuun vai alkuun, suoritetaanko käytettävissä olevat toiminnot (lisää, tyhjennä leikepöytä, kopioi ja leikkaa) heti vai vahvistuksen pyytämisen jälkeen, ja pyydetäänkö aiemman sisällön korvaamiseen vahvistus, jos leikepöydällä on vain tekstiä.

Huomautuksia:

*	Edellä mainittua komentoa on mahdollista muuttaa kohdasta NVDA-valikko ->
  Asetukset -> Syötekomennot ja valitsemalla avautuvasta valintaikkunasta
  Asetukset-kategoria.
*	Vahvistusta ei pyydetä NVDA:n ilmoitusruudun ollessa avoimena, vaan
  toiminnot suoritetaan heti.

## Muutokset versiossa 6.0

*	 Lisätty vaihtoehtoja, joilla voidaan valita, pyydetäänkö käytettävissä olevien toimintojen suorittamiseen vahvistus.
*	Lisätty Vahvista kopiointi- ja Vahvista leikkaaminen -asetukset, joille voidaan määrittää syötekomennot Syötekomennot-valintaikkunasta.
*	Lisätty valintaikkuna Vahvista kopiointi- ja Vahvista leikkaaminen -toiminnallisuuksien  määrittämiseen lisäosan asennuksen aikana. Kun nämä asetukset ovat käytössä, kopioinnin (Ctrl+C) ja leikkaamisen (Ctrl+X) suorittamiselle pyydetään vahvistus.
*	Korjattu tekstinlisäämiskomennon (Windows+NVDA+C) ohje.

## Muutokset versiossa 5.0 ##

*	Valintaikkunan visuaalista esitystä on parannettu noudattamaan NVDA:n
  ikkunoiden ulkoasua.
*	Edellyttää NVDA:n 2016.4-versiota tai uudempaa.

## Muutokset versiossa 4.0 ##
*	NVDA hallitsee nyt lisäosan asetuksia, jotta profiilien käyttäminen eri
  erottimien tallentamiseen olisi mahdollista, eikä asetusten kopiointia
  tarvita niiden tuomiseksi asennettaessa lisäosaa uudelleen.
*	Lisäosan asetusvalintaikkunan Lisää teksti leikepöydän nykyisen sisällön
  alkuun -valintaruutua käyttäen on nyt mahdollista valita, liitetäänkö
  lisätty teksti leikepöydällä jo olevan tekstin loppuun vai alkuun.

## Muutokset versiossa 3.0 ##
*	MathML-objekteja kuvaavat pistekirjoitusmerkit voidaan lisätä
  leikepöydälle, mikäli MathPlayer on asennettu.
*	Mikäli erotinta ei ole määritetty, tekstiosuuksien väliin lisätään yksi
  tyhjä rivi.
*	Leikepöydän sisällön käsittelijän asetusvalintaikkunan avaamista varten
  voidaan määrittää pikanäppäin.
*	Asetusvalintaikkunaan lisätty valintaruutu, jolla voidaan määrittää,
  kopioidaanko erotin käyttäjän NVDA-asetusten kansioon, josta se voidaan
  tuoda asennettaessa lisäosaa uudelleen.

## Muutokset versiossa 2.0 ##
*	Hindinkielisiä merkkejä voidaan käyttää tekstiosuuksien välisenä
  erottimena.

## Muutokset versiossa 1.0 ##
*	Ensimmäinen versio.

[[!tag dev stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=ccd

[2]: http://addons.nvda-project.org/files/get.php?file=ccd-dev
