# Assignment : Metrika,pregled i statička analiza
# LOC
Broj linija koda za sve fajlove iznosi 214.
Broj linija koda calculator.java iznosi 188.
Broj linija koda Start.java iznosi 26.

# Ciklomatska složenost metoda evaluateExpression i Calculate

Uz pomoć alata Codalyze u Visual Studio Code izračunata je ciklomatska složenost za metode evaluateExpression i metodu Calculate. Ciklomatska složenost iznosi 12, i za metode evaluateExpression i metodu Calculate. što bi značilo da je rizik umjeren.

# Kognitivna složenost metoda evaluateExpression i Calculate

Kognitivna složenost za metodu evaluateExpression iznosi 9, a za metodu Calculate iznosi 13. Možemo zaključiti da je kognitivna složenost, za obe metode, raltivno visoka.

# Neformalan pregled koda
Ovaj program je napisan java programskim jezikom. Sastoji se od dva fajla, a to su Calculator.java i Start.java. Ova dva fajla su dio istog programa. Start.java klasa  sadrži glavnu metodu "main" koja se izvršava prilikom pokretanja programa i putem nje se vrši interakcija sa korisnikoma, dok je "Calculator.java" klasa koja sadrži logiku za izvršavanje matematičkih operacija. Pored toga, program sadrži i MIT licencu.

# Statička Analiza

Za statičku analizu korišten je SonarLint u Visual Studio Code-u i IntelliJ IDEA razvojno okruženje. 
Prije pokretanje koda, pronađene su sljedeće greške :
1) Fajl : Calculator.java, broj linije koda: 18, - zapažanje: Potrebno preimenovati metodu ‘ToString’ kako bi se izbjegla zamjena sa metodom ‘toString’ iz super klase "java.lang.Object". Sonarlint ovo kategoriše u veći Code smell.
2) Fajl : Calculator.java, broj linije koda: 24, zapažanje: Potrebno preimenovati naziv metode ‘Run’ kako bi odgovarala regularnom izrazu.
3) Fajl : Calculator.java, broj linije koda: 53, zapažanje: petlja ‘for’ se može zamijeniti sa naprednom ‘for’ petljom, odnosno for-each petljom.
4) Fajl : Calculator.java, broj linije koda: 70, zapažanje: promjenjljiva ‘textResult’ je suvišna.
5) Fajl : Calculator.java, broj linije koda: 74, zapažanje: Potrebno preimenovati naziv metode ‘Calculate’ da odgovara regularnom izrazu.
6) Fajl : Calculator.java, broj linije koda: 183, zapažanje: Potrebno je ukloniti ‘return’, iz razloga što je suvišan













