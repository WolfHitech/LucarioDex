<p align="center">
  <img src="assets/readme/banner.png" alt="LucarioDex — BETA" width="100%">
</p>

<h1 align="center">LucarioDex</h1>
<p align="center"><b>BETA PUBBLICA — APERTA PER 2 SETTIMANE</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/versione-0.1.0-red" alt="versione">
  <img src="https://img.shields.io/badge/stato-beta-orange" alt="stato">
  <img src="https://img.shields.io/badge/gioco-PokeMMO-purple" alt="gioco">
</p>

---

## Benvenuto nella Beta

Grazie per essere qui. **LucarioDex** è l'overlay intelligente per PokeMMO:
legge la tua schermata di gioco in tempo reale e ti mostra le informazioni che
contano durante la cattura e la lotta, senza mai coprirti il gioco.

> **La beta resta aperta per 2 settimane.** Durante questo periodo il software
> è in evoluzione: segnala bug, proponi idee e racconta la tua esperienza.
> Ogni feedback aiuta a rendere la versione finale più stabile e completa.

**Data apertura:** `14/10/2026` · **Data chiusura prevista:** `28/10/2026`

<table>
<tr>
<td width="50%">

**Cosa puoi fare in beta**
- Provare tutte le funzioni senza limiti
- Usare profili, temi e scorciatoie personalizzate
- Segnalare bug e suggerire miglioramenti

</td>
<td width="50%">

**Cosa sto cercando**
- Report di riconoscimento errato (OCR)
- Problemi di posizionamento/overlay
- Idee per nuove funzioni

</td>
</tr>
</table>

---

## Cos'è LucarioDex

LucarioDex è un'applicazione desktop per **Windows** che affianca PokeMMO come
**overlay trasparente e "sempre in primo piano"**. Analizza la finestra di gioco
con tecniche di **Computer Vision + OCR** e presenta subito:

- l'**avversario** riconosciuto, con tipi, **debolezze, resistenze e immunità**;
- il **danno stimato** delle tue mosse e qual è la **mossa migliore**;
- la **probabilità di cattura** con la ball consigliata, aggiornata in tempo reale;
- il **confronto di Velocità** con il nemico;
- gli **incontri della zona** in cui ti trovi;
- un **Pokédex interno** completo, sempre a portata di ricerca.

Nasce per togliere le distrazioni: niente alt-tab, niente tabelle da consultare.
Metti l'overlay dove vuoi e gioca.

---

## Funzioni principali

### 1) Riconoscimento avversario in tempo reale
Un click su **Scansiona** (o la scansione automatica) legge la barra del nemico:
nome e specie, **livello**, **PS** residui e **stato**. Il pannello mostra i tipi
e la **tabella di efficacia** con debolezze, resistenze e immunità.

- Supporto **orde** (horde) e **doppio incontro** (2 nemici);
- riconoscimento automatico del genere quando serve (es. Nidoran);
- tutto derivato dai dati reali del gioco.

### 2) Stima dei danni e mossa migliore
Per ogni mossa del tuo Pokémon calcola il **danno medio** (formula Gen 5) usando
**IV/EV/natura** reali, applicando **STAB** ed **efficacia di tipo**. Le mosse
vengono **ordinate**: in cima trovi la migliore, con la percentuale stimata sui
PS del nemico.

- Barra colorata immediata: verde / gialla / rossa;
- tooltip con danno medio, moltiplicatore STAB e moltiplicatore di efficacia.

### 3) Calcolo cattura e ball consigliata
La **probabilità di cattura** usa la formula Gen III/IV di PokeMMO e tiene conto
di PS, stato, ball e contesto. L'elenco delle ball viene **riordinato** mettendo
in alto la migliore. Gestisce le ball condizionali: **Repeat, Net, Nest, Dusk,
Quick, Timer, Dream**, oltre a livello, grotta, notte e catena di catture.

### 4) Confronto Velocità
Confronta la Velocità del tuo Pokémon con l'intervallo del nemico e ti dice
subito se lo **superi**, se **forse lo superi** o se sei **più lento**.

### 5) Pannello Zona (incontri)
Mentre cammini, LucarioDex legge l'area corrente e mostra **cosa può apparire**:
specie, **metodo** (erba, grotta, acqua, pesca, bottintesta...), **livelli**,
**rarità** e **EV** che assegna. Clicca una riga per segnarla come **catturata**;
i contatori "mancano qui / presi / orde" si aggiornano da soli.

### 6) Pokédex interno
Cerca qualsiasi specie e apri la sua scheda completa: **statistiche base** (con
barre), **abilità**, **altezza/peso**, tasso di cattura, genere, gruppi uovo,
**tier**, **evoluzioni**, **mosse per livello** e sprite animato. Flag
**Leggendario** incluso.

### 7) Scansione automatica e turno
Attiva la **scansione automatica** a intervalli regolari (anche **solo in
battaglia**) per aggiornare i dati senza premere nulla. Il **turno** viene
tracciato automaticamente — o letto dal log con l'opzione "Leggi turno (lento)"
— così Quick Ball e Timer Ball restano sempre precisi.

---

## Esperienza d'uso

- **Overlay trasparente**: regola opacità, dimensione e posizione; resta sopra il gioco.
- **Click-through**: in modalità non-modifica i click passano direttamente a PokeMMO.
- **Ancoraggio al gioco**: l'overlay segue la finestra di PokeMMO in un angolo scelto.
- **Guide magnetiche e snap**: trascinando, l'overlay si allinea a schermo e finestra di gioco.
- **Modalità compatta**: riduci tutto a una barra quando vuoi più spazio.
- **Notifiche toast**: conferme rapide e non invasive.
- **Icona nel vassoio** con menu rapido (scansione, impostazioni, zona, esci).
- **Lingue**: Italiano ed English.

### Personalizzazione
- **Tema** Scuro/Chiaro, **colore accento** (Rosso scuro, Cremisi, Scarlatto, Brace);
- **Alto contrasto** e **scala del testo**;
- **Sfondo** personalizzato: scegli una tua foto (o ripristina quella di default);
- **Profili**: salva, carica ed elimina configurazioni complete (anche i dati del Pokédex).

---

## Scorciatoie da tastiera

| Scorciatoia       | Azione                      |
|-------------------|-----------------------------|
| `Ctrl + Alt + H`  | Mostra / nascondi overlay   |
| `Ctrl + Alt + C`  | Modalità modifica ON/OFF    |
| `Ctrl + Alt + S`  | Apri impostazioni           |

> Le scorciatoie sono personalizzabili dalle Impostazioni. **Modalità modifica
> OFF** = i click passano al gioco.

---

## Avvio rapido

1. Avvia **PokeMMO**.
2. Fai doppio click su **`LucarioDex.exe`** .
3. Lascia l'overlay sopra il gioco: premi **Scansiona** o attiva la scansione automatica.

Requisiti: **Windows 10/11** e **Python 3** con le dipendenze dell'app
(interfaccia Qt, elaborazione immagini e motore OCR).

---

## Come dare feedback (durante la beta)

Aiutaci a migliorare! Quando apri una segnalazione, includi:

- cosa stavi facendo e cosa ti aspettavi;
- uno **screenshot** dell'overlay e del gioco nello stesso momento;
- **zona/luogo** e **Pokémon** coinvolti;
- versione mostrata in basso nell'app (`v0.1.0`).

**Canale ufficiale:** `[ t.me/lndefinizione ]`

---

## Note e limiti della beta

- Il riconoscimento si basa su OCR/CV: **errori occasionali sono attesi**.
- Funziona con PokeMMO in **finestra** o **borderless** (schermo intero sconsigliato).
- Alcune ball condizionali richiedono il turno corretto: attiva "Leggi turno"
  se noti valori imprecisi.
- Il software è in evoluzione: **funzioni e interfaccia possono cambiare** durante le 2 settimane.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyQt6-UI-41CD52?style=flat&logo=qt&logoColor=white" alt="PyQt6">
  <img src="https://img.shields.io/badge/OpenCV-Computer%2520Vision-5C3EE8?style=flat&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=flat&logo=windows&logoColor=white" alt="Windows">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
  <img src="https://img.shields.io/badge/Version-1.0.0-blueviolet" alt="Version">
</p>

---

<p align="center">
  <b>LucarioDex</b> — made by <b>@WolfHitech</b><br>
  <sub>Beta v0.1.0 · Grazie per giocare e testare assieme a me.</sub>
</p>
