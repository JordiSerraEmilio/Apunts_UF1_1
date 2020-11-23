# Apunts-M05
## 1.Introducció
### 1.1 Tipus de Software
- **De sistema** - (sistema operatiu, drivers)
- **De aplicació** - (aplicatius d'ofimàtica, navegador)
- **De desenvolupament** - (editors, complidors)

### 1.2 Relació "Hardware-Software"
- **Disc dur:** emmagatzema de forma permanent els arxius de dades i els d'execució.
- **RAM:** emmagatzema de forma temporal el codi binari dels arxius de dades i d'execució necessaris.
- **CPU:** llegeix i executa instruccions emmagatzemades en RAM, així com les dades necessàries.
- **Perifèrics d'entrada/sortida:** recull noves dades des de l'entrada, els mostren resultats, es guarden al disc...

### 1.3 Codi font, objecte i executable
- **Codi font:** arxiu de text llegible escrit en un llenguatge de programació.
- **Codi objecte:** fitxer binari **NO** executable.
- **Codi executable:** fitxer binari **EXECUTABLE**.

## 2. Cicle de la vida del Software

**Ingenieria de Software** →disciplina que estudia els principis i metodologies per al desenvolupament i manteniment dels sistemes de software.

### 2.1 Desenvolupament de Software
### Fases principals
|Anàlisis|
|--------|
|Es determina i defineix clarament les necessitats del client i s'especifica els requisits que ha de complir el software a desenvolupar.|

|Disseny|
|--------|
|Es descompon i organitza el sistema en elements components que poden ser desenvolupats per separat.|

|Codificació|
|--------|
|S'escriu el codi font de cada component i es poden utilitzar diversos llenguatges informàtics.|

|Proves|
|--------|
|El principal objectiu de les proves es aconseguir que el programa funcioni incorrectament i que es descobreixin els seus errors i defectes.|

|Manteniment|
|--------|
|Durant l'explotació del sistema Software és necessari realitzar canvis ocasionals.|
|**Tipus de manteniments:**|
|**Correctiu:** es corregeixen els defectes|
|**Perfectiu:** es milloren les funcionalitats|
|**Evolutiu:** s'afegeix funcionalitats noves|
|**Adaptatiu:** s'adapta a nous entorns|

### 2.2 Resultat de cada fase I
- **Ingenieria de sistemes**: especificació del sistema.
- **Anàlisis**: especificació de requisits del Software.
- **Disseny arquitectònic**: document d'arquitectura del Software.
- **Disseny detallat**: especifico de mòduls i funcions.
- **Codificació**: codi font.

### 2.3 Resultat de cada fase II
- **Proves d'unitats**: mòduls utilitzables.
- **Proves d'integració**: sistema utilitzable.
- **Proves del sistema**: sistema acceptat.
- **Documentació**: documentació tècnica i d'usuari.
- **Manteniment**: informes d'errors i control de canvis.

## 3. Models de desenvolupament de Software

- **Cascada**

És el model més antic.
Les fases és realitzen una darrera de l'altre, i fins que no s'acabi una fase, no es pasa a la següent.

- **V**

Aquest és un model jeràrquic amb diversos nivells.
El nivell d'a dalt de tot, es fan coses més abstractes com el disseny. I en el nivell d'baix coses més detallades com la codificació.

- **Prototips I**

Els requisits no estan especificats clarament:
-- per no existir algú previ
-- per falta d'informació del client.

- **Prototips II**

Procés:
Es crea un prototip durant la fase d'anàlisis i es prova per l'usuari o client per acabar de refinar els requisits del programa.
Es repeteix aquests passos fins que sigui necessari.

- **Prototips III**

Tipus de prototipus:
-- Prototipus ràpides
El prototip pot estar desenvolupat en un altre llenguatge.
Al final el prototip es llença.
-- Prototips evolutius
El prototip està d'assenyat en el mateix llenguatge.
El prototip s'utilitza per com a base per desenvolupar el projecte.

- **Espiral I**

Correspon a les fases dels models clàssics com anàlisis, disseny, codificació...
- **Espiral II**

Gran importància a la reutilització del codi.

## 4. Llenguatges de Programació

Primer de tot, tenim 2 opcions a l'hora d'obtenir codi binari executable.
- Compilats
- Interpretats

### 4.1 Procés de complicació/interpretació

Té dues fases:
-- 1. Anàlisis lèxic
-- 2. Anàlisis sintàctic
Si no existeixen errors, es genera el codi objecte.
Un codi font escrit correctament, no significa que faci el que nosaltres volem.
I no es realitza un anàlisis semàntic.

### 4.2 Llenguatges compilats i avantatges

Exemples: **C**, **C++**
Avantatge: Tenen una execució molt eficient.

### 4.3 Llenguatges interpretats i avantatges

Exemples: **PHP**, **Java**
Avantatge: El codi font s'interpreta directament per tant, té una execució més ràpida.

### 4.4 Tipus I

--**Declaratius:** indiquen o busquen el resultat sense importar els passos a seguir.
Lògics - Prolog
Funcionals - Lisp
Algebraics - SQL
--**Imperatius:** els importa els passos a seguir per obtindre el resultat.
Estructurats - C
Orientat a objectes - Java
Multiparadigma - C++, Javascript

### 4.5 Tipus IV
Baix nivell: **ensamblador**
Alt nivell: **C++, Java**

### 4.6 Evolució
-Codi binari
-Ensamblador
-Llenguatges estructurats
-Llenguatges orientats a objectes
