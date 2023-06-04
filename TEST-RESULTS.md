# Assignment : Testiranje

1) Osnovne aritmetičke operacija:
o	Sabiranje: 
Unos: 4+3
Očekivani rezultat: 7
o	Oduzimanje: 
Unos: 10-5
Očekivani rezultat: 5
o	Množenje: 
Unos: 4*7
Očekivani rezultat: 28
o	Dijeljenje: 
Unos: 24/8
Očekivani rezultat: 3
Rezultat testiranja : PASS

2) Operacije sa zagradama :
Unos: "2*(6-2)"
očekivani rezultat: "8.0"
dobijeni rezultat : "ERROR"
rezultat testiranja : FAIL

3) Prioritet računskih operacija:
Unos: 12+15*3
Očekivani rezultat: 57
Unos: 10-5*3+4
Očekivani rezultat: -1
Unos: 6/2+5 
Očekivani rezultat: 8
Unos: 8+2/8-3
Očekivani rezultat: 5.25
Rezultat testiranja : PASS

4) Testiranje decimalnih brojeva: 
Unos: 2.5+3.5
Očekivani rezultat: 6.0
Unos: 4.2-2.1
Očekivani rezultat: 2.1
Unos: 1.5*3.0 
Očekivani rezultat: 4.5
Unos: 10.0/3.0
Očekivani rezultat: 3.3333333
Rezultat testiranja : PASS

5)  Dijeljenje sa 0 :
unos: "8/0"
očekivani rezultat : "Inffinity"
rezultat testiranja : PASS

6) Testiranje neispravnih izraza: 
Unos: 7++6 
Očekivani rezultat: "ERROR"
dobijeni rezultat : 0.0
Ulaz: 72-  
Očekivani rezultat: "ERROR"
dobijeni rezultat : 0.0
Unos: 7*4+
Očekivani rezultat: "ERROR"
dobijeni rezultat : 0.0
Unos: tri + tri
Očekivani rezultat: "ERROR"
dobijeni rezulat : 0.0
Unos: +++++
Očekivani rezultat: "ERROR"
Dobijeni rezultat : 0.0
Rezultat testiranja : FAIL

# Zapažanje :
Većina navedenih slučajeva testiranja u Test planu su prošli.
Izuzetak je unos više pluseva ili više minusa gdje bi trebalo da ispiše: ERROR, a na izlazu je pisalo Final result 0.0. Pored toga, greška se desšava i u operacijama sa
zagradama, gdje umjesto očekivanog rezultata, dobijamo "ERROR". 
Izuzev ovih grešaka, sva ostala testiranja su zadovoljila kriterij. Program je brz i efikasan i ispunjava uslove za koje je namjenjen. 







