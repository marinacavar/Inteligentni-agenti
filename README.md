# Inteligentni-agenti

2.Izmijeniti D1 - Deterministic Environment i D2 - Stochastic Environment simulacije na način da se pametni usisavač uvijek kreće prema najbližem prljavom dijelu prostorije, dok cijela prostorije nije čista.

3.Izmijeniti O2 - Partially observable simulaciju na način da se automobil koji naiđe na oštećenje na putu pomakne u susjednu traku i nastavi vožnju čime će okruženje postati potpuno vidljivo.

4.Izmijeniti E2 - Sequential Environment simulaciju na način da se proizvod automatski pojavljuje na traci nakon odrađenog broja otkucaja, a pojavljivanje novih proizvoda zaustavlja kada je serija kompletirana (30 ispravnih proizvoda) ili ako je serija neuspješna (3 neispravna proizvoda).

5.Izmijeniti MAS - Simple Colaboration na način da od dva agenta jedan može samo percipirati stijenu na dijelu okruženja na kojem se nalazi, a drugi samo može uzeti uzorak. Nakon što prvi agent otkrije stijenu, dojavljuje drugom poziciju, a drugi najbližom rutom dolazi do stijedne i uzima uzorak.

6.Osmisliti primjer koji bi prikazao višeagentski sustav u kojem se javlja pojedinačni sukob oko resursa (ciljevi nekompatiblni, vještine dostatne, resursi nedostatni).

7.Napraviti model sustava u kojem se nalaze dvije vrste agenata: predator (1 agent) i plijen (3 agenta uz vjerojatnost od 3% da će se pojaviti dodatni agenti ove vrste). Predator kruži po ivici modela, dok se agenti vrste plijen kreću nasumično. Ukoliko se plijen nalazi na udaljenosti manjoj od 3 od predatora, predator se  upućuje prema njemu, ubija ga, vraća se do ivice modela i nastavlja kretanje. Dimenzije modela neka budu 17 x 13, tj. x ∈ [-8, 8], y ∈ [-6, 6].

8.Napraviti modifikaciju prethodnog primjera za situaciju kada je se u sustavu nalaze dva para agenta vrste predator (tj. dva roditelja i dvoje djece) i tri agenta vrste plijen (uz vjerojatnost od 3% da će se pojaviti dodatni agenti). Svaki od predatora roditelja uočava i lovi plijen i tada poziva svoje predator dijete da ga pojede (ubije). Dijeca predator u međuvremenu stoji u nasuprotnim kutovima i u njih se vraćaju nakon što pojedu plijen.
