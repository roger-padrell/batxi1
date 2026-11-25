
## U1
- Enginyeria: aplicar mates i física per inventar, dissenyar i construir màquines.
- Competències:
	- emprenedoria: creació de productes, gestió d'equips
	- creativitat: solucions noves
	- perseverança: continuar malgrat problemes
	- resiliencia: adaptació a canvis, flexibilitat
- Modes RDI (recerca desenvolupament investigació)
	- projectius: predir tendències, estadística, modelatge i simulació
	- prospectius: idees, escenaris de futur, mètode Delphi (discussió d'experts)
- Design thinking: empatitzar, definir, idear, prototipar, provar
- Fases d'un projecte
	1. inici i definició
	2. disseny i planificació
	3. execució i control
	4. tancament i avaluació

## U2
- Costos de producció:
	- fixes
	- variables
- Ingressos: `I = P · Q = (preu unitat) · (n unitats)`
- Costos: `C = CF + CV = (costos fixos) + (costos variables)`
- Costos variables: `CV = CVu · Q = (cost variable unitat) · (n unitats)`
- Punt mort: `Q* = Q(C == I) = CF / (P-CVu)`
- En un gràfic, marcar inversió inicial com a recta horitzontal, ingressos com a funció, costos com a funció, punt mort com a punt (i indicar valor en el eix x), marcar zona de benefici i zona de pèrdues
<br>
- VAN: Valor Actual Net (VAN > 0 ⇒ rendible)
	- A = inversió inicial
	- Fx = guanys en el periode x (anual, mensual)
	- i = taxa de descompte (pérdua de valor adquisitiu dels diners)
	- `-A = sumatori_x(Fx / (1+i)^x)`

### Diagrama de Gantt
- Visualitzar les tasques de forma de gràfic de barres horitzontal.
- coll d'ampolla: retarda aquesta tasca es retarda TOT
- 8 h / dia laborable
![enter image description here](https://concepto.de/wp-content/uploads/2024/02/Diagrama-de-Gantt-EJEMPLO-TP-768x384.jpg)

### Diagrama de PERT (program evaluation review technique)
- relacions i dependències entre operacions
- mínim nombre de nodes
- temps
	- early/proper: moment més d'hora que es poden començar les tasques que surten a aquest node
	- last/llunyà: moment més tard que es poden acabar les tasques que finalitzen en aquest node (sense retardar el projecte sencer)
- Marge: `m_t = t_last_nfinal - t_early_ninicial - t_tasca`
- camí crític: aquelles tasques amb marge zero
- els camins penjats sempre acaben a l'últim node
![enter image description here](https://statorials.org/wp-content/uploads/2023/08/exemple-pert-graphique.png)

## U3
- Desenvolupament de productes:
	1. Disseny inicial i desenvolupament
	2. Desenvolupament del sistema de fabricació
	3. Disseny dels detalls tècnics (plànols, presició, toleràncies, normatives)
	4. Proves pilot
	5. Presèries
	6. Finalització i llançament
- Cadena de subministrament:
	1. proveïdors
	2. transport
	3. fabricació
	4. emmagatzematge
	5. transport
	6. venda a l'engros
	7. venda al detall

### Control de qualitat
- taxa de rebuig: `rebutjats / entrants * 100`
- taxa d'acceptació: `acceptats / entrants * 100`
- fiabilitat: probabilitat que una màquina funcioni sense avaries durant un cert temps

## Temps de màquines
- Tipus:
	-	En sèrie
	-	En paral·lel
-	temps de cicle = màxim temps en una màquina
-	afegir màquina en paral·lel = dividir temps en màquina entre num. maquines

## Bases i conversió
- Base 2: 01
- Base 16: 0123456789ABSDEF
- 235 base x ⇒ base 10:
	- 2x² * 3x¹ * 5x⁰
- 235 base 10 ⇒ base 16:
	- acumulació de residus i inversió
	1. 235/15 C=14 R=11=B
	2. 14/16 C=0 R=14=E
	3. inversió: EB

## Metrologia
- Mesurar: comparar una magnitud coneguda presa com a unitat
	- magnitud: tipus (naturalesa) de la mesura
	- valor: quantitat numèrica
	- unitat: referència a una quantitat patró en el S.I
		- bàsiques/derivades
- Correcció:
	- exactitud: grau d'aproximació al valor real (vertader vs convencional)
	- precisió: dispersió de les mesures
	- apreciació: valor de la mínima fracció d'unitat que pot llegir un instrument
- Error:
	- absolut: `obtingut - real`
	- relatiu: `e_absolut / real` 
- Instruments de mesura:
	- Tipus:
		- directe: es llegeix el valor a l'instrument
		- comparació: diferències entre valor conegut i desconegut
		- verificació: dins d'un rang de valors establert (passa - no passa)

### Instruments de mesura
#### Peu de rei
```
    mínim val. superior
a = -------------------
    numero d val infer
```
![El peu de rei | Restaura la moto!](https://restauralamoto.com/wp-content/uploads/2014/07/El-peu-de-rei.jpg)

#### Micròmetre
```
         pas de rosca
a = --------------------
    num divisions tambor
```
![Micrómetro en milésimas de pulgada - uso, lectura e interpretación | Prof.  Eduardo J. Stefanelli](https://www.stefanelli.eng.br/wp-content/uploads/2016/05/micrometro-bainha-revelada-polegada-milesimal.png)

#### Angles (goniòmetre)
```
    divisió min regle fix
a = ---------------------
     num de parts nònius
```
![Download - Goniómetro o Transportador de Ángulos | Prof. Eduardo J.  Stefanelli](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSschVK0jHQT5Px2x1_Nfkl7B5UvvI86Uuxwx0Lq9ouBA5lYoWviIEuLw&s=10)


## Normalització
- conjunt de prescripcions tècniques que especifiquen i unifiquen aspectes en processos industrials
- certificació: duta a terme per una identitat independent, normes o especificacions
- normes i sistemes de normes: especificacions tècniques pactades entre fabricants, tècnics i usuaris
- utilitzem:
	- ISO: internacional
	- aenor (une): espanyoles

## Toleràncies i ajustatges
- Toleràncies: quantitat dimensional que indica l'interval de dimensions on es pot fabricar una peça
- elements:
	- cota nominal (**C**): referència
	- cota màxima (**CM**)
	- cota mínima (**Cm**)
	- desviació superior (**ds**): CM - C
	- desviació inferior (**di**): Cm-C
	- Tolerància (**T**): CM-Cm = ds - di
- eix i forat:
	- eix: ds' i  di'
	- forat: ds i di
- ajustatge: relació eix-forat
	- amb joc: CM(eix) < Cm(forat)
		- JM = CMf - Cme = ds - di'
		- Jm = Cmf - CMe = di - ds'
	- amb serratge:
		- SM = CMe - Cmf = ds' - di = -Jm
		- Sm = Cme - CMf = di' - ds = -JM
	- indeterminat
- tolerància ajustatge: Te + Tf = (ds'-di')+(ds-di)
- quantitat de tolerància (grau de perfecció/precisió): grau IT (ISO)
	- majúscula: forat
	- minúscula: eix
	- de més precís (IT01) a més imprecís (IT18)
- operacions amb toleràncies:
	- L  = suma(cotes en positiu) - suma(cotes en negatiu)
	- ds = suma(ds pos) - suma(di neg)
	- di = suma(di pos) - suma(ds neg)

## Electrònica digital
### Aritmètica binària
- suma
	- 0+0=0
	- 0+1=1
	- 1+1=10
- resta
	- 0-0=0
	- 1-0=1
	- 10-1=1
	- 1-1=0
	- 0-1=1 (amb 10 negatiu)
### Àlgebra de bool
- OR
- AND
- NOT
- NAND
- NOR
- XOR
- NAND
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwNTk1MTY3NzUsNDEzNjI0ODY4LDczMD
k5ODExNl19
-->