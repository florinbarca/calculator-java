# calculator-java

Calculator scris în Java; suportă adunarea, scăderea, înmulțirea și împărțirea
Atribuire - Metrici, prezentare generală și analiză statică
LOC - Numărul total de linii de cod pentru toate fișierele este 214 (Calculator.java și Start.java 188 + 26)

**Complexitatea ciclomatică a metodelor evaluateExpression și Calculate**

Folosind instrumentul Codalyze din Visual Studio Code, a fost calculată complexitatea ciclomatică pentru metoda evaluateExpression și este 12. 
De asemenea, a fost calculată și complexitatea ciclomatică pentru metoda Calculate și este tot 12.

**Complexitatea cognitivă a metodelor evaluateExpression și Calculate**

Complexitatea cognitivă a metodei evaluateExpression: putem concluziona că este relativ ridicată.
Metoda efectuează mai mulți pași pentru a calcula valoarea expresiei date ca parametru de intrare.
Complexitatea este sporită și mai mult de faptul că metoda trebuie să gestioneze cazuri diferite în funcție de prezența diferitelor operații aritmetice în expresie.
Acest lucru necesită o monitorizare atentă, ceea ce face codul dificil de înțeles.
Complexitatea cognitivă a metodei „Calculate” este de asemenea ridicata
Există mai multe blocuri if-else folosite pentru a determina ordinea în care sunt efectuate operațiile, ceea ce poate crește și mai mult complexitatea cognitivă a metodei.

Mediul de dezvoltare IntelliJ IDEA a semnalat următoarele erori înainte de a rula codul, în Calculator.java:
Fișier - numarul liniei de cod 4 - obserrvatie: clasa „IdentifCalculator” nu este niciodată folosită
Fișier - numarul liniei de cod 13 - observatie: nu se poate rezolva simbolul „sau”
Fișier - numarul liniei de cod 24 - observatie: metoda „Run(java.lang.String)” nu este niciodată folosită
Fișier - numarul liniei de cod 53 - observatie: bucla „for” poate fi înlocuită cu „for” îmbunătățită
Fișier - numarul liniei de cod 70 - observatie: variabila locală „textResult” este redundantă
Fișier: numarul liniei de cod 87 - observatie: partea comună poate fi extrasă din „if” ,Calculate(numbers, operations),deoarece nu afectează executarea condiţiei în sine
Fișier: numarul liniei de cod 138 - observatie: partea comună poate fi extrasă din „if” ,Calculate(numbers, operations),deoarece nu afectează executarea condiţiei în sine
Fișier: numarul liniei de cod 183 - observatie: „return” este inutilă ca ultima declarație dintr-o metodă „void”.













