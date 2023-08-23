#  H1 Oma linux

## Millainen on vapaa ohjelmisto?

Vapaa ohjelmisto tarkoittaa, että ohjelmistoa saa vapaasti käyttää, kopioida, tutkia, muuttaa tai kehittää.

**Vapaa ohjelmisto koosttuu neljästä vapaudesta:**

* Ohjelmistoa voi käyttää niin kuin itse haluaa
* Vapaus muokata ohjelmistoa makunsa mukaan, niin että se toimii kuten haluaa
* Vapaus jakaa ohjelmistoa muiden käyttöön
* Vapaus jakaa muokattua ohjelmistoa muiden käyttöön

Ilman näitä vapauksia, ohjelmistoa ei voi kutsua vapaaksi.

**Vapaa ohjelmisto voi olla kaupallinen**

- Vapaa ohjelmisto ei tarkoita, että sitä ei voi käyttää kaupallisesti
- Vapaan ohjelmiston täytyy kuitenkin aina täyttää neljän vapauden kohdat
- Jos jotakin vapautta rajoitetaan, tai niistä pyydetään maksua, ei ohjelmistoa luokitella enää vapaaksi

**Paketoinnin ja jakelun säännöt**

- Kun muokkaa jonkun toisen ohjelmaa on tärkeää merkitä se sinun muokkaamaksi, jotta pystyy tunnistamaan sen hetkisen tekijän.
- Jos aikaisempi kehittäjä haluaa muokatun ohjelmiston lähdekoodin, täytyy se hänelle toimittaa.

  **Oikeudelliset seikat**

- Jos ohjelmiston vapaudet voivat muuttua tai kehittäjä rajoittaa niitä myöhemmin, ei ohjelmistoa voi kutsua vapaaksi.

  ## Lähteet ##

  GNU. What is Free Software? Luettavissa: https://www.gnu.org/philosophy/free-sw.html#four-freedoms. Luettu: 23.8.2023.
  
# Ubuntu asennus #

**Tämä asennus suoritettiin Windows 10 käyttöjärjestelmällä 23.8.2023.**

**VirtualBox versio 7.0.10**

- Asensin ensin VirtualBox ohjelmiston
- Ohjelmiston käynnistyttyä painoin "New" nappia

 ![alt text](https://github.com/faltjon/linuxkurssi/blob/main/0-uusi-vm.png "Vaihe 0")
 
- Sen jälkeen valitsin "Expert mode"
  
 ![alt text](https://github.com/faltjon/linuxkurssi/blob/main/1-expert-mode.png "Vaihe 1")

Expert modessa annetaan nimi, valitaan ISO tiedosto, tyyppi ja versio.
- ISO Image: debian-live-12.1.0-amd64-xfce.iso
- Type: Linux
- Version: Debian (64-bit)
- Valitaan "Skip Unattended Installation
- Seuraavaksi avasin Hardware välilehden

  ![alt text](https://github.com/faltjon/linuxkurssi/blob/main/2-settings.png "Vaihe 2")


Hardware kohdassa seuraavat asetukset:
- Base Memory: 4000 MB
- Processors: 4
- Sitten valitsin Hard Disk välilehden
 
 ![alt text](https://github.com/faltjon/linuxkurssi/blob/main/vaihe-3.png "Vaihe 3")

 
Hard Disk kohdassa seuraavat asetukset:
- Hard Diskille 40 GB tilaa
- Lopuksi tallenna asetukset painamalla "Finish"

 ![alt text](https://github.com/faltjon/linuxkurssi/blob/main/vaihe-4-hard-disk.png "Vaihe 4")


 - Seuraavaksi käynnistin virtuaalikoneen tupla klikkaamalla sitä hiiren oikealla painikkeella

 ![alt text](https://github.com/faltjon/linuxkurssi/blob/main/vaihe-5-kaynnistys.png "Vaihe 5")


Avautuu Debian aloitusikkuna
- Valitsin nuolinäppäimillä "Live System (amd64)
- Painoin enter
  
![alt text](https://github.com/faltjon/linuxkurssi/blob/main/vaihe-6-asennus.png "Vaihe 6")

- Hetken kuluttua pääsin työpöytä näkymään ja käynnistin työpöydältä ohjelman "Install Debian"
- Käynnistin ohjelman painamalla "Launch Anyway"
  
  ![alt text](https://github.com/faltjon/linuxkurssi/blob/main/Vaihe-7-asennuksen-aloitus.png "Vaihe 7")

  - Seuraavaksi laitoin kieleksi Suomi
  - Painoin Seuraava
  
  ![alt text](https://github.com/faltjon/linuxkurssi/blob/main/vaihe-8-kieli.png "Vaihe 8")
  - Sijainniksi laitoin Alue: Europe ja Vyöhyke: Helsinki
  - Painoin seuraava
    
![alt text](https://github.com/faltjon/linuxkurssi/blob/main/vaihe-9-aikavyohyke.png "Vaihe 9")
    
  - Näppäimistöasetuksissa kieleksi Suomi ja Default
  - painoin seuraava
    
![alt text](https://github.com/faltjon/linuxkurssi/blob/main/vaihe-10-nappaimisto.png "Vaihe 10")

- Osiot-kohdassa valitsin "Tyhjennä asema" ja painoin seuraava

  ![alt text](https://github.com/faltjon/linuxkurssi/blob/main/vaihe-11-osiot.png "Vaihe 11")

- Käyttäjät-kohdassa annoin käyttäjän- ja tietokoneen nimen sekä salasanan.
- Painoin seuraava

![alt text](https://github.com/faltjon/linuxkurssi/blob/main/vaihe-12-kayttaja.png "Vaihe 12")

Yhteenveto-välilehdessä alanapit ovat piilossa ja ne saa näkyviin suurentamalla ruudun painamalla neliötä oikealta ylhtäältä
- Painoin "Asenna"
- Asennus kesti n. 10 minuuttia.
  
![alt text](https://github.com/faltjon/linuxkurssi/blob/main/vaihe-13-yhteenveto.png "Vaihe 13")

- Asennuksen jälkeen painoin "Valmis" ja virtuaalitietokone käynnistyi uudelleen
- Uudelleenkäynnistymisen jälkeen avautui kirjautumisvalikko
- Kirjauduin sisään
  
![alt text](https://github.com/faltjon/linuxkurssi/blob/main/vaihe-14-kirjautuminen.png "Vaihe 14")

 - Työpöydällä testasin, hiiren, näppäimistön ja internet-yhteyden, jotka toimivat normaalisti.
   
![alt text](https://github.com/faltjon/linuxkurssi/blob/main/Vaihe-15-testaus.png "Vaihe 15")
