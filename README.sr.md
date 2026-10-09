<a href="https://shoppoppers.rs/"><img src="media/cover.jpg" alt="Shop Poppers, naslovna strana na laptopu i telefonu" width="100%"></a>

# Shop Poppers

Web prodavnica u kojoj se deo kataloga poručuje, a ostatak je samo informativan, uz pravilo koje sprovodi server.

**[shoppoppers.rs](https://shoppoppers.rs/)** · [Studija slučaja](https://svilenkovic.rs/radovi/shop-poppers) · [English](README.md)

> [!NOTE]
> Klijentski projekat. Izvorni kod pripada klijentu i čuva se u privatnom repozitorijumu. Ova stranica opisuje šta sam uradio i kako.

<table>
  <tr><td><b>Klijent</b></td><td>Shop Poppers</td></tr>
  <tr><td><b>Delatnost</b></td><td>Online katalog i prodavnica</td></tr>
  <tr><td><b>Lokacija</b></td><td>Srbija</td></tr>
  <tr><td><b>Vrsta</b></td><td>Web prodavnica</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Dizajn, izrada, SEO, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>PHP 8.3, MariaDB, JavaScript, nginx</td></tr>
</table>

## O projektu

Shop Poppers prodaje u celoj Srbiji, uz plaćanje pouzećem. Deo kataloga se poručuje preko sajta, a ostali proizvodi su samo informativni: svaki ima cenu, fotografiju i svoju stranu, ali ne može da se kupi. Klijent je hteo da sve izgleda kao jedna kolekcija, a da se ipak ponaša različito.

Pravilo stoji na serveru. Kad se proizvod doda u korpu, i ponovo pri završetku porudžbine, server čita zapis proizvoda i prihvata samo artikle označene za poručivanje, pa izmena HTML-a ili ručno sastavljen zahtev ne otvaraju zadnja vrata. Cena, dostupnost i dostava ponovo se čitaju iz baze pre nego što se porudžbina prihvati, a vlasnik prebacuje proizvod iz jednog stanja u drugo jednim poljem u admin panelu.

## Šta sam uradio

- Jedan katalog u kome proizvodi za poručivanje i informativni proizvodi dele iste kartice, uz oznake i dugmad koji kažu šta je na kojoj moguće
- Provere na serveru pri dodavanju u korpu i pri završetku porudžbine, uz ponovni obračun cene, dostupnosti i dostave iz baze
- Pravilo dostave (jedan artikal se plaća, dva ili više besplatno) prikazano na sajtu, a obračunato na serveru
- Samo plaćanje pouzećem, pa sajt ne prikuplja podatke o karticama
- Admin panel za proizvode i porudžbine, u kome jedno polje prebacuje proizvod iz jednog stanja u drugo
- Strane proizvoda sa sopstvenim kanonskim adresama, Open Graph slikama i strukturisanim podacima; korpa, potvrde i admin deo van indeksa

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Shop Poppers, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Shop Poppers, naslovna strana na telefonu"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="Katalog: proizvodi za poručivanje i informativni proizvodi u istoj mreži">
<sub>Katalog: proizvodi za poručivanje i informativni proizvodi u istoj mreži</sub>

<img src="media/inner-2.webp" alt="Stranica proizvoda sa cenom, dostupnošću, korpom i kontaktom">
<sub>Stranica proizvoda sa cenom, dostupnošću, korpom i kontaktom</sub>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
