# PRAC2_Neteja-i-Analisi-de-Dades

**Membres**

* Lorena Casanova Lozano
* Sergio Costa Planells

## Descripció 

En aquesta pràctica s’elabora un cas pràctic orientat a aprendre a identificar les dades rellevants per un projecte analític i usar les eines d’integració, neteja, validació i anàlisi de les mateixes. S'ha triat un conjunt de dades extret de la plataforma Kaggle penjat en aquest repositori (indian_liver_patient.xlsx) i accessible a través de l'enllaç https://www.kaggle.com/uciml/indian-liver-patient-records. El joc de dades conté els resultats d’anàlsis de mostres biològiques d’un total de 583 individus, 416 pacients amb malaltíes hepàtiques i 167 sense patologia, procedents del nordest d’Andhra Pradesh, India. En total inclou 10 atributs, tots numérics menys el sexe de l’individu i un 11è atribut classe binari que indica si l’individu presenta o no patologia de fetge.

## Objectius

Atès que les malalties hepàtiques acostumen a ser greus l’interés del nostre objectiu rau en avaluar la capacitat que tenim de detectar aquestes patologies en pacients al més aviat possible. Plantegem la hipòtesis que els valors obtinguts a travès de les anàlisis de sang de què disposem poden ser suficients per a detectar individus malalts malgrat encara no hagin desenvolupat una simptomatologia evident o, si més no, podem desenvolupar un model que ens permeti fer una primera cribra dels pacients candidats a anàlisis posteriors. Volem donar resposta, doncs, a les següents preguntes:

• Existeix una diferencia estadísticament significativa en la proporció de malalts de fetge en funció del sexe?
• Existeix una diferència estadísticament significativa en la mitjana d’edat entre els malalts i els idividus sans?
• Quina és la influència dels diferents factors (atributs de què disposem) en la probabilitat de desenvolupar una
patologia de fetge?
• Quina capacitat tenim de predir si un individu pateix o no una malaltia de fetge a partir dels atributs que disposem?

## Metodologia


Per tal de donar resposta a aquestes preguntes s’apliquen diferents mètodes d’anàlisi estadístic sobre el conjunt de dades tot comprovant si es compleixen les condicions necessàries per a la validesa dels resultats. Atès que els objectius definits giren al voltant d’un problema de classificació i disposem d’una variable classe de control (Diesease) farem ús d’algoritmes d’aprenentatge supervisat per tal de construir el model final de classificació. Els diferents mètodes que s’utilitzaran per a realitzar l’anàlisi estadístic són els següents:
• Test d’hipòtesis -> Comparar mostres d’Homes/Dones i Malalts-Sans per donar resposta a les preguntes plantejades.
• Regressió logística -> Avaluar la influència de cada variable en la probabilitat de tenir afecció de fetge i predir el valor resultant.
• Random Forest -> Construir un model de classificació que ens permeti de predir la variable Disease a partir de la resta d’atributs.
