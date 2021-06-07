Drugi kolokvijum - Napredno web programiranje

Na postojeću aplikaciju, koja se nalazi na:

https://github.com/Jovic92/Jovic92-NWP-Kol2-Template

Dodati i pozvati:
Potrebne servise za komunikaciju između korisničkih komponenti i servera koji obrađuje korisnika(login i registracija)
Potrebne servise za komunikaciju komponenti koje predstavljaju prikaz informacija o filmovima, njihov “update” kao i dodavanje novih filmova.(obratiti pažnju na komentare)
Dodati potrebne Input, Output direktive kao i Emitere
Dodati interceptor servis, koji presreće saobraćaj i dodaje token u header zahteva kao “X-AUTH-HEADER”
Ispuniti konstantu routes u app-routing.module.ts odgovarajućim rutama do komponente
Dodati guard.
----------------------------------------------------------------------------------------------------------------
Izmeniti malo stranice koristeći AngularMaterial
Izmeniti kod da uvek prikazuje po godinama najmlađe filmove
(Odabrati jednu od dve tačkama ponuđene stavke)

U oba projekta uraditi
	npm install
U MovieInfo projektu još:
	npm install bootrap
	npm install rxjs-compat (ovo možda, ako rxjs ne bude radio)
U Server projektu možda instalirati:
	npm install cors

Ukoliko, ne želite u početku da se petljate sa Security-em, unutar Server/movie.js zakomentarišite sve pozive metode checkIfLoggedIn
