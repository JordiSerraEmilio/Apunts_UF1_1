# Apunts-M05
## 1.Introducció
### 1.1 Tipus de Software
- **De sistema** - (sistema operatiu, drivers)
- **De aplicació** - (aplicatius d'ofimàtica, navegador)
- **De desenvolupament** - (editors, complidors)

### 1.2 Relació "Hardware-Software"
- **Disc dur:** emmagatzema de forma permanent els arxius de dades i els d'execució.
- **RAM:** emmagatzema de forma temporal el códi binari dels arxius de dades i d'execució necessaris.
- **CPU:** llegeix i executa instruccions emmagatzemafes en RAM, així com les dades necessaries.
- **Perifèrics d'entrada/sortida:** recull noves dades des de l'entrada, els mostren resultats, es guarden al disc...

### 1.3 Codi font, objecte i executable
- **Codi font:** arxiu de text llegible escrit en un llengüatge de programació.
- **Codi objecte:** fitxer binari **NO** executable.
- **Codi executable:** fitxer binari **EXECUTABLE**.

## 2. Cicle de la vida del Software

**Ingenieria de Software** →disciplina que estudia els principis i metadologies per al desenvolupament i manteniment dels sistemes de software.

### 2.1 Desenvolupament de Software
### Fases principals
|Analisis|
|--------|
|Es determina i defineix clarament les necessitats del client i es especifica els requisits que ha de complir el software a desenvolupar.|

|Diseny|
|--------|
|Es descompon i organitza el sistema en elements components que poden ser desenvolupats per separat.|

|Codificació|
|--------|
|S'escriu el codi font de cada component i es poden utilitzar diversos llengüatges informàtics.|

|Proves|
|--------|
|El principal objectiu de les proves es aconseguir que el programa funcioni incorrectament i que es descobreixin els seus errors i defectes.|

|Manteniment|
|--------|
|Durant la explotació del sistema Software és necessari realitzar canvis ocasionals.|
|**Tipus de manteniments:**|
|**Correctiu:** es corregeixen els defectes|
|**Perfectiu:** es milloren les funcionalitats|
|**Evolutiu:** s'afegeix funcionalitats noves|
|**Adaptatiu:** s'adapta a nous entorns|

### 2.2 Resultat de cada fase I
- **Ingenieria de sistemes**: especificació del sistema.
-  **Anàlisis**: especificació de requisits del Software.
-  **Diseny arquitectònic**: document d'arquitectura del Software.
-  **Diseny detallat**: especifició de mòduls i funcions.
-  **Codificació**: codi font.

### 2.3 Resultat de cada fase II
- **Proves d'unitats**: mòduls utilitzables.
-  **Proves d'integració**: sistema utilitzable.
-  **Proves del sistema**: sistema acceptat.
-  **Documentació**: documentació tècnica i d'usuari.
-  **Manteniment**: informes d'errors i control de canvis.

## 3. Models de desenvolupament de Software

- **Cascada**

És el model més antic.   
Les fases és realitzen una darrera de l'altre, i fins que no s'acabi una fase, no es pasa a la següent.

- **V**

Aquest és un model jeràrquic amb diversos nivells.    
El nivell d'adalt de tot, es fan coses més abstractes com el diseny. I en el nivell d'abaix coses més detallades com la codificació.

- **Prototips I**

Els requisits no estan especificats clarament:  
-- per no existir algu prèvi  
-- per falta d'informació del client.  

- **Prototips II**

Proccés:  
Es crea un prototip durant la fase d'anàlisis i es proba per el usuari o client per acabar de refinar els requisits del programa.  
Es repeteix aquests pasos fins que sigui necessari.

- **Prototips III**

Tipos de prototipos:  
-- Prototipos rápidos  
El prototip pot estar desenvolupat en un altre llengüatge.  
Al final el prototip es llença.  
-- Prototips evolutius  
El prototip està disenyat en el mateix llengüatge.  
El prototip s'utilitza per com a base per desenvolupar el projecte.  

- **Espiral I**  

Correspon a les fases dels models clàsics com anàlisis, diseny, codificació...  
- **Espiral II**  

Gran importancia a la reutilització del codi.  

## 3. Llenguatges de Programació

Primer de tot, tenim 2 opcions a l'hora d'obtindre codi binari executable.
- Compilats
- Interpretats
