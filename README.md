# Sistema_intel-ligent_mobilitat_BCN
# Dashboard de mobilitat urbana sostenible de Barcelona

## 1. Descripció del projecte

Aquest projecte consisteix en desenvolupar una dashboard web interactiva que permeti als usuaris consultar alternatives de mobilitat sostenible dins de la ciutat de Barcelona. L'aplicació identificarà la ubicació actual de l'usuari, amb el seu consentiment, i li permetrà introduir una destinació per comparar diferents opcions de desplaçament en funció de diferents paràmetres.

Les alternatives inclouran els desplaçaments a peu, en bicicleta i amb transport públic, com ara autobús, metro i tramvia. Per a cada alternativa, es mostrarà el temps estimat de trajecte i, quan correspongui, el cost aproximat d'un viatge d'anada.

També es possible que ens faci fer una combinació de transport, de totes maneres, si es així l'aplicació indicarà la opció més sostenible per a viatgar per Barcelona.

## 2. Objectius i finalitats

### Objectiu general

Dissenyar i desenvolupar un prototip funcional de dashboard web que faciliti la planificació de desplaçaments urbans a Barcelona, prioritzant alternatives al vehicle privat i promovent una mobilitat més sostenible a partir dels serveis públics que ofereix la ciutat de Barcelona.

### Objectius específics

- Permetre obtenir la ubicació actual de l'usuari mitjançant la geolocalització del navegador.
- Permetre introduir una destinació situada dins dels límits municipals de Barcelona.
- Mostrar diverses alternatives de trajecte sense utilitzar el cotxe.
- Comparar els temps estimats i els costos dels diferents mitjans de transport.
- Visualitzar els trajectes en un mapa interactiu.
- Utilitzar fonts de dades i serveis de mobilitat per obtenir informació actualitzada sempre que sigui possible.
- Desenvolupar una interfície intuïtiva, accessible i fàcil d'utilitzar.
- Organitzar el desenvolupament mitjançant una planificació temporal, una assignació de rols i una metodologia Kanban.

### Finalitats del projecte

El projecte pretén facilitar la presa de decisions dels ciutadans, reduir les barreres per utilitzar el transport públic i els modes actius, i donar visibilitat a les alternatives de mobilitat més sostenibles. També permetrà aplicar coneixements de gestió urbana, dades obertes, desenvolupament web i planificació de projectes.

## 3. Abast del projecte

El prototip se centrarà exclusivament en els desplaçaments amb origen i destinació dins del municipi de Barcelona.

**Funcionalitats principals:**
- Geolocalització de l'usuari amb permís explícit.
- Introducció i validació de la destinació.
- Consulta d'alternatives a peu, en bicicleta i amb transport públic.
- Visualització dels trajectes en un mapa.
- Comparació del temps estimat i del cost del trajecte.
- Indicació de la font i de les limitacions de les estimacions.

**Funcionalitats fora de l'abast inicial:**
- Reserva o compra de bitllets.
- Seguiment en temps real de l'usuari durant el trajecte.
- Planificació de trajectes amb cotxe.
- Integració de totes les operadores o sistemes de mobilitat existents.

## 4. Criteris mínims d'èxit

El projecte es considerarà satisfactori si compleix els criteris següents:

1. **Pàgina web funcional:** disposar d'una dashboard accessible des d'un navegador.
2. **Geolocalització:** poder obtenir la posició de l'usuari quan aquest concedeixi el permís, i oferir una alternativa manual si el rebutja.
3. **Cerca de destinacions:** permetre introduir una destinació i comprovar que sigui dins de Barcelona.
4. **Alternatives de mobilitat:** mostrar almenys dues alternatives de trajecte sense cotxe, sempre que les dades i els serveis disponibles ho permetin.
5. **Temps i costos:** presentar una estimació del temps per a cada alternativa i el cost del bitllet senzill quan sigui aplicable.
6. **Mapa interactiu:** representar la ubicació d'origen, la destinació i els trajectes disponibles.
7. **Fiabilitat de les dades:** documentar les fonts utilitzades, les tarifes consultades i les limitacions de les estimacions.
8. **Prototip demostrable:** preparar una demostració amb diversos exemples d'origen i destinació.
9. **Gestió del projecte:** disposar d'un README, un diagrama de Gantt, un tauler general de tasques i un Kanban actualitzat.
10. **Treball en equip:** assignar responsabilitats als cinc membres, mantenir un registre de les tasques i integrar les contribucions individuals.

## 5. Organització de l'equip

L'equip està format per cinc estudiants. Es proposa una distribució inicial de responsabilitats:

| Rol | Responsabilitats principals |
|---|---|
| 1. Coordinació del projecte | Planificació, seguiment del Gantt, reunions i documentació |
| 2. Dades i geolocalització | Ubicació de l'usuari, cerca d'adreces i validació dels límits municipals |
| 3. Rutes i mobilitat | Integració dels serveis de rutes i consulta de transport públic |
| 4. Desenvolupament de la interfície | Disseny de la dashboard, mapa i visualització de resultats |
| 5. Integració i qualitat | Proves, verificació de dades, integració del codi i documentació tècnica |

Els rols són responsabilitats principals, no compartiments exclusius. Tots els membres participaran en la definició dels requisits, la revisió del prototip i la presentació final.

## 6. Metodologia de treball

S'utilitzarà una metodologia àgil basada en Kanban. Les tasques es registraran en un tauler compartit i es mouran entre les columnes «Per fer», «En curs», «En revisió» i «Fet».

Es proposa fer una reunió setmanal breu per revisar els avenços, detectar bloquejos i actualitzar la planificació. El codi i la documentació es mantindran en un repositori compartit, preferiblement GitHub.

## 7. Lliurables finals

- Repositori de codi amb un README actualitzat.
- Dashboard web funcional o prototip navegable.
- Diagrama de Gantt i tauler de seguiment.
- Kanban amb l'estat de les tasques.
- Documentació de les fonts de dades, els serveis utilitzats i les limitacions.
- Presentació i demostració del funcionament del prototip.

## 8. Limitacions i riscos

La disponibilitat de rutes, horaris, temps estimats i tarifes dependrà dels serveis i les fonts de dades seleccionats. Abans d'iniciar el desenvolupament, caldrà verificar quines API o conjunts de dades permeten obtenir aquesta informació i quines condicions d'ús tenen.

La geolocalització dependrà del permís de l'usuari i de les capacitats del dispositiu. En cas de no disposar d'alguna dada en temps real, es podrà utilitzar una estimació o una dada de referència, sempre que s'identifiqui clarament com a tal.

El projecte és acadèmic i té com a prioritat demostrar la viabilitat de la solució mitjançant un prototip, sense exigir una plataforma comercial completa.
