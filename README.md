# veb-servisi
Kreiranje veb servisa i veb aplikacije koja ga koristi. Koriscen je REST stil arhitekture
Potrebno je kreirati veb servis i veb aplikaciju koja ga koristi. Veb servis može biti proizvoljne funkcionalnosti, kao i aplikacija.Prilikom kreiranja veb servisa, neophodno je koristiti REST stil arhitekture. Format podataka može da bude proizvoljan (XML, JSON). Takođe, veb servis mora sadržati bar dve funkcije, a aplikacija koristi navedene funkcije, kreiranjem odgovarajućih klijenata. Trebalo bi implementirati jedan AJAX poziv servisa u okviru aplikacije. Za izradu veb servisa je moguće koristiti proizvoljnu tehnologiju (nije neophodan PHP).

bazu podataka sa međusobno povezanim tabelama (najmanje 2 tabele);
obradu zahteva pomoću različitih HTTP metoda (GET, POST, PUT, DELETE) i izvršavanje bar dve CRUD operacije nad bazom podataka. CRUD operacije bi trebalo da se izvrše pozivanjem adekvatnih HTTP metoda;
naprednije funkcionalnosti, koje će kasnije moći da se upotrebe za pristup sa različitih klijenata (npr. veb aplikacija, Android aplikacija i sl.);
HTTP zaglavlja za slanje specifičnih podataka (npr. željeni format odgovora);
jedan fajl koji definiše više funkcija veb servisa i na osnovu nekog ulaznog parametra vrši se definisanje koja funkcija se poziva.
naprednu obradu i parsiranje JSON i XML podataka
napredno rutiranje zahteva (može da se koristi neki framework, kao što je Flight).
Takođe, za najvišu ocenu, potrebno je da sve stranice aplikacije budu adekvatno povezane (u smislu dizajna i funkcionalnosti) i da funkcionalnosti veb servisa budu adekvatne, u skladu sa tematikom aplikacije koja ga koristi. Na primer, ukoliko je tema aplikacije prodavnica, a veb servis predstavlja konvertor valuta, potrebno je da se uz pomoć veb servisa klikom na odgovarajući taster automatski konvertuju cene svih proizvoda u željenu valutu.

Osim kreiranja klijenta za sopstveni veb servis, aplikacija treba da sadrži i poziv ka nekom javnom veb servisu, koji je u skladu sa tematikom aplikacije i koji je integrisan sa ostatkom sajta na adekvatan način. Potrebno je naći neki javni veb servis koji nije opisan u primerima datim u skripti.


U tekstualnom fajlu treba ukratko opisati šta radi veb servis, uloge svih fajlova i ubaciti screenshot-ove ključnih funkcionalnosti. U ovom fajlu je potrebno ubaciti jasnu dokumentaciju svake funkcije servisa, po uzoru na dokumentaciju nekog javnog API-ja (npr. Twitter API) ili na primer iz skripte FlightPHP. Isti fajl kompresovati (zip, rar, 7z) zajedno sa ostalim fajlovima i postaviti na Moodle kao rešenje zadatka.
