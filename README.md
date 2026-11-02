# LucarioDex 1.1

LucarioDex is a Windows overlay for PokeMMO. It reads the game image while you play and shows battle information, catch odds, area spawns, Pokédex pages, PvE guides and PvP calculations in a panel that stays above the game.

Version 1.1 fixes the shortcut that shows and hides the overlay.

LucarioDex keeps the information you need on screen, without opening a browser, checking a wiki or moving to another monitor. It is informational only: it does not play the game, click for you, send inputs or automate any action.

## Requirements

- Windows 10 or 11, 64-bit.
- PokeMMO running in windowed or borderless mode.
- The installer includes everything needed.

## Installation

Download `LucarioDex-Setup-1.1.exe` from the [releases page](https://github.com/WolfHitech/LucarioDex/releases).

Run the installer. If Windows SmartScreen warns about an unknown publisher, choose **More info** and then **Run anyway**. The installation is per user, does not require administrator rights and places the program in `%LOCALAPPDATA%\LucarioDex`.

To remove it, use **Settings → Apps → LucarioDex → Uninstall**. Your settings and personal data remain in `%APPDATA%\LucarioDex`; delete that folder if you also want to remove them.

## Quick start

1. Open PokeMMO and show the screen you want to read: an encounter, a battle or a route.
2. Start LucarioDex. The overlay appears above the game.
3. Press **Scan** for a manual reading, or enable **Auto** for automatic scanning.
4. Adjust position and size in edit mode, then press `Ctrl + Alt + C` to let clicks reach the game.

## Features

### Battle analysis

The enemy card shows species, level, HP, status, types and base speed, plus badges for Alpha Pokémon, hordes and a second opponent. Four tabs summarise the fight:

- **Matchup**: weaknesses, resistances and immunities.
- **Moves**: your moves read from the screen, ranked by estimated damage.
- **Danger**: how much damage the opposing Pokémon can deal to you.
- **Catch**: catch probability, recommended ball and expected cost.

You can fill one or two slots for your own Pokémon, which enables damage estimates in singles and doubles. LucarioDex can also detect them from the screen.

### Catching

Catch odds are recalculated from current HP, status, species and ball. The recommended ball is the one with the best chance for its price, not simply the strongest ball. Conditional balls such as Repeat, Net, Nest, Dusk, Quick, Timer and Dream are considered when they help.

The panel also estimates the number of throws and the total cost in Poké Yen. Consecutive catches of the same species build a chain, shown by a **Chain** badge; the Repeat Ball uses that count.

### Areas and Pokédex

The **Zone** panel lists the Pokémon that can appear in the current area, with encounter method, rarity, level range, EVs and hordes. It tracks which species you have already caught and which are still missing. When an area name exists in more than one region, a region selector appears.

The Pokédex search opens a full page with base stats, types, abilities, height, weight, catch rate, gender, egg groups, tier, legendary status, evolutions, level-up moves, locations and sprite.

### PvE guide

The **PvE** panel collects four kinds of content:

- **Rerun**: gym rematch strategies with team, turns, cost and income, safe and skipped gyms, an optimised travel route and a checklist.
- **Story**: the five regions with eight badges each, level caps, gym leaders and tips. Badge progress is saved.
- **Leagues**: Elite Four and champion for each region, cooldown, base and charm payout, preparations and counters. League clears are saved.
- **Events**: Ho-Oh, Pumpking, Red and the Christmas routine, with facts, checklist, team, procedure and rewards. Seasonal details follow the current edition.

All tabs also show community teams from BattGuide when available, with roster, notes and Pokepaste links. The full turn-by-turn guide remains on BattGuide; LucarioDex shows the team card and credits the authors.

A strategy, league or event can be opened in the **Turn guide** with one button. PvE guide content is currently written in Italian; the interface follows the selected language.

### Turn guide

The **Guide** panel steps through a route one turn at a time. Use **Next** or `Ctrl + Shift + N`, go back with **Back**, and restart with **Reset**. If a route declares a roster, the panel narrows the possible opposing team as species appear. When turn reading is enabled, routes with turn markers advance by themselves.

### Ditto Farm

The **Ditto Farm** panel estimates damage against a normal Ditto and against a transformed Ditto, which copies your defences but keeps its HP. Enter your Pokémon, the move you use, and Ditto's level and HP. The panel warns when the move risks a knockout and suggests the best ball at full HP and at 1 HP with sleep. A capture counter keeps track of catches.

### PvP and StratDex

PvP mode replaces the PvE battle panel with four tabs:

- **Team**: six slots with species, level, nature, item, ability, moves, IVs, EVs and boosts. Slots can be saved in boxes, reloaded, imported from Showdown sets or exported back to Showdown. Presets provide a starting point.
- **Opponent**: the opposing set, even partial. Moves read from the screen remain until the Pokémon changes or the battle ends.
- **Field**: weather, Trick Room, Reflect, Light Screen, Tailwind, Stealth Rock, Spikes and Toxic Spikes for both sides.
- **Damage**: turn order, effective speed, damage ranges, remaining HP, accuracy, hits needed for a knockout and a combined row for your two best moves.

StratDex adds community usage data from mmoshowdown.com: tiers, most-used moves and items, spreads, common teammates, an **Apply most-used set** action, and a **Speed benchmark** table for level 50. Usage data describes probabilities, not official ladder statistics.

### Interface

The interface is available in Italian and English. You can change theme and accent colour, overlay opacity, text scale, high contrast, background image, header visibility, always-on-top behaviour, position locking and game anchoring. While dragging, alignment guides appear and the overlay snaps to screen or game edges. Profiles store a complete layout, including Pokédex progress and panel settings. Global hotkeys and a notification-area menu provide quick access.

### Updates

The installed build checks GitHub for a newer release at startup and from the settings panel. If an update exists, it shows the release notes and offers **Update now** or **Skip**. Updating downloads the installer, verifies the file when the release provides a checksum, closes LucarioDex and starts the setup. Settings and personal data are preserved. A skipped version is remembered.

## Privacy

Settings, profiles, Pokédex progress, PvE progress and PvP teams are stored locally in `%APPDATA%\LucarioDex`. LucarioDex does not collect analytics, telemetry or game data. The only network request is the update check against GitHub, and it sends no information about your game or configuration.

## Legal

LucarioDex is an informational overlay. It reads the visible game window and its title to locate the game. It does not modify the PokeMMO client, inject code, read game memory, network traffic or game files, and it does not send inputs or automate gameplay. It is not a bot and not a cheat.

Use of the software is at your own responsibility. Check the PokeMMO rules that apply to you. If the game interface changes, some readings may stop working until an update is released.

LucarioDex is not affiliated with, endorsed by or sponsored by Nintendo, Creatures Inc., GAME FREAK, The Pokémon Company, PokeMMO, Pokémon Showdown, mmoshowdown or BattGuide. Pokémon and Pokémon character names are trademarks of their respective owners. PokeMMO, Showdown and BattGuide are mentioned only to describe compatibility and data sources.

Data about Pokémon, moves and encounters comes from PokeMMO community projects and is adapted for PokeMMO. Usage data comes from mmoshowdown.com. Community teams and Pokepaste links belong to their authors and are credited in the app; the full BattGuide content is not copied into LucarioDex.

The software is provided as is, without warranty of any kind. The authors are not liable for data loss, account restrictions or any other damage resulting from its use.

---

# Guida in italiano

La versione 1.1 corregge la scorciatoia che mostra e nasconde l'overlay. Questa parte descrive installazione, uso e soluzione dei problemi in italiano. I nomi dei pulsanti corrispondono all'interfaccia italiana.

## Installazione

Scarica `LucarioDex-Setup-1.1.exe` dalla [pagina delle release](https://github.com/WolfHitech/LucarioDex/releases).

Apri il file. Se Windows mostra l'avviso di SmartScreen, scegli **Ulteriori informazioni** e poi **Esegui comunque**. L'installazione è per utente, non richiede permessi da amministratore e installa il programma in `%LOCALAPPDATA%\LucarioDex`.

Al termine trovi LucarioDex nel menu Start. Il collegamento sul desktop è opzionale.

Per disinstallarlo usa **Impostazioni → App → LucarioDex → Disinstalla**. Le impostazioni e i dati personali restano in `%APPDATA%\LucarioDex`; cancella quella cartella se vuoi rimuoverli.

## Primo avvio

1. Apri PokeMMO e mettiti nella schermata che vuoi leggere: un incontro, una battaglia o un percorso.
2. Avvia LucarioDex. L'overlay compare sopra il gioco.
3. In basso leggi `Gioco: connesso` quando la finestra di PokeMMO viene riconosciuta.
4. Premi **Scansiona** per una lettura manuale, oppure attiva **Auto** per la scansione automatica.
5. Sistema posizione e dimensioni, poi disattiva la modalità modifica con `Ctrl + Alt + C`.

Mentre trascini l'overlay compaiono le guide di allineamento e, al rilascio, la finestra si aggancia ai bordi dello schermo o della finestra di gioco. Blocca la posizione con il lucchetto nella barra del titolo quando hai finito.

Se avvii LucarioDex due volte, la seconda istanza riporta in primo piano la finestra già aperta.

## Schermata principale

La finestra contiene sempre le stesse zone:

- barra del titolo, con i pulsanti per compattare, bloccare la posizione e aprire le impostazioni;
- barra di ricerca del Pokédex;
- scheda del nemico, con nome, livello, PS, stato, tipi, velocità base e badge per Alpha, orde e secondo avversario;
- quattro schede: **Efficacia**, **Mosse**, **Pericolo** e **Cattura**;
- scheda **Il mio Pokémon**, con uno o due slot per le lotte in singolo e in doppio;
- pulsanti **Scansiona** e **Auto**;
- riga strumenti con **Zona**, **Guida**, **Ditto**, **PvP** e **PvE**;
- riga di stato con connessione, versione, ora dell'ultima scansione e badge **Catena** quando è attiva.

### Scheda Mosse

La mossa in cima è quella con il danno medio più alto secondo i dati inseriti. Accanto compaiono la percentuale stimata sui PS del nemico e una barra colorata: verde per una situazione favorevole, gialla per una intermedia, rossa per un colpo pesante.

I selettori di stadio vicino alle statistiche servono per danze e debuff. Se il nemico ha abbassato la difesa o tu hai potenziato l'attacco, aggiornali: la stima cambia.

Se non hai compilato il tuo Pokémon, il danno non può essere calcolato. Bastano specie, livello e natura per ottenere una prima stima.

### Cattura

La probabilità dipende da PS attuali, stato, specie e ball. La ball consigliata è quella con il miglior rapporto tra probabilità e costo. Le ball condizionali vengono considerate quando la situazione le rende convenienti.

Il pannello mostra anche i lanci stimati e il costo complessivo in Poké Yen. Se stai catturando la stessa specie di fila, il badge **Catena** mostra il conteggio e la Repeat Ball ne tiene conto.

## Scansione

La scansione automatica legge lo schermo a intervalli regolari. È utile per gli incontri di fila, ma consuma più risorse quanto più è frequente.

- **Solo in battaglia** limita la scansione ai combattimenti e risparmia lavoro mentre cammini.
- **Leggi turno (lento)** riconosce il numero di turno. Serve all'avanzamento automatico della Guida ed è l'opzione più pesante.

Se la scansione non riconosce nulla, controlla che il gioco sia in primo piano, non minimizzato e non coperto da menu. Verifica anche che la modalità della finestra nelle impostazioni corrisponda a come stai giocando.

## Zona

Il pannello **Zona** mostra la zona corrente e i Pokémon che vi compaiono, con metodo di incontro, rarità, livelli, EV e orde. Clicca una riga per segnarla come catturata: il contatore si aggiorna e resta salvato.

La zona viene ricavata dal testo a schermo, quindi fai la scansione quando il nome dell'area è visibile. Se lo stesso nome esiste in più regioni, compare un selettore per scegliere quella giusta.

## Pokédex

La barra di ricerca apre la scheda di qualsiasi specie presente nei dati. La pagina mostra statistiche base e totale, tipi, abilità (compresa quella nascosta quando disponibile), altezza, peso, tasso di cattura, genere, gruppi uovo, tier, leggendari, evoluzioni, mosse per livello, zone di cattura e sprite.

Con **Indietro** torni al pannello precedente. Lo stato di visto e catturato viene ricordato e salvato nei profili.

## Guida PvE

Il pulsante **PvE** apre un pannello con quattro schede. Il contenuto delle guide è in italiano anche quando l'interfaccia è in inglese.

### Rerun

La scheda **Rerun** raccoglie strategie per rifare le palestre. Per ogni strategia trovi squadra, ruoli, mosse, oggetti, costo, guadagno stimato, turni, palestre sicure e palestre da saltare.

Sotto trovi il percorso ottimizzato per regione e una checklist. La strategia può essere aperta nella **Guida** con il pulsante dedicato, così i turni diventano un percorso passo-passo.

### Storia

La scheda **Storia** copre Kanto, Johto, Hoenn, Sinnoh e Unova. Per ogni regione elenca gli otto badge con città, capopalestra, tipo, livello del Pokémon principale e consiglio, oltre ai limiti di livello progressivi.

Spunta un badge per segnare il progresso. Il conteggio resta salvato e puoi azzerarlo con **Azzera**.

### Leghe

La scheda **Leghe** mostra per ogni regione i quattro membri dell'Elite Four e il campione, con tipo, Pokémon principale, livello, difficoltà, contromosse e consigli. In alto leggi cooldown e premio base o con charm.

Anche qui puoi segnare i membri già battuti e aprire la lega nella **Guida** come percorso.

### Eventi

La scheda **Eventi** contiene Ho-Oh, Pumpking, Red e la routine di Natale. Ogni guida mostra scheda, checklist, squadra consigliata, procedura, ricompense e consigli. I dettagli stagionali seguono l'edizione corrente.

Le checklist salvano il progresso. La procedura può essere aperta nella **Guida** quando sono presenti i passi.

### Team della community

In tutte le schede compare, quando disponibile, la card **Team della community** con roster, note e collegamenti Pokepaste. I team provengono da BattGuide e restano attribuiti ai rispettivi autori; la guida turno completa è su BattGuide, non dentro LucarioDex.

La scelta del team viene ricordata per la scheda e la regione o evento corrispondente.

## Guida turni

Il pannello **Guida** segue un percorso un turno alla volta. Usa **Avanti** o `Ctrl + Shift + N`, torna indietro con **Indietro** e riparti con **Azzera**.

Se il percorso dichiara un roster, il pannello mostra il team avversario possibile e lo restringe man mano che le specie compaiono. Quando sono state viste tutte, scrive `Tutte le specie osservate`.

Con **Leggi turno** attivo, i percorsi che hanno un numero di turno avanzano da soli quando la lettura raggiunge quel valore. Se un passo non scatta, controlla che il numero di turno sia visibile a schermo e che l'opzione sia attiva.

## Ditto Farm

Il pannello **Ditto Farm** aiuta a catturare Ditto senza mandarlo KO. Inserisci il Pokémon che usi, la mossa, il livello e i PS di Ditto.

Il pannello mostra il danno stimato su un Ditto normale e su un Ditto dopo **Transform**, che copia le tue difese ma mantiene i suoi PS. Ti avvisa se rischi il KO e suggerisce la ball migliore a PS pieni e a 1 PS con sonno. Il contatore **+1 cattura** tiene il conto delle prese.

False Swipe riduce quasi a zero il rischio di KO; un attacco normale a PS bassi può chiudere lo scontro prima della cattura.

## PvP

Il pulsante **PvP** sostituisce il pannello PvE con quattro schede:

- **Squadra**: sei slot con specie, livello, natura, oggetto, abilità, mosse, IV, EV e boost. Puoi salvare gli slot nei box, ricaricarli, eliminarli e importare o esportare set in formato Showdown. I preset offrono un punto di partenza.
- **Avversario**: il set del Pokémon che hai davanti, anche parziale. Le mosse lette restano compilate finché non cambia il Pokémon o finisce la battaglia.
- **Campo**: meteo, Trick Room, Riflesso, Schermo Luce, Venti Rapidi, Stealth Rock, Spikes e Toxic Spikes per entrambi i lati.
- **Danno**: ordine di turno, velocità effettiva, danno, PS rimasti, precisione, colpi necessari al KO e riga combinata delle due mosse migliori.

Le stime dipendono dai dati inseriti. Se il set avversario è incompleto, anche il risultato lo sarà.

### StratDex

StratDex è attivo quando i dati inclusi sono validi. Mostra l'uso comune dei Pokémon nel tier scelto:

- mosse più usate, oggetto, abilità, spread e compagni frequenti nella scheda **Avversario**;
- set disponibili nel menu **Preset**;
- **Benchmark velocità** nella scheda **Danno**, con velocità effettive a livello 50 e confronto con il tuo Pokémon.

I dati provengono da mmoshowdown.com e descrivono probabilità d'uso, non statistiche ufficiali della ladder.

## Impostazioni

Apri le impostazioni con l'ingranaggio o con `Ctrl + Alt + S`.

**Aspetto** comprende opacità, intestazione, sempre in primo piano, modalità modifica, tema e colore accento, scansione automatica, **Solo in battaglia**, rilevamento dei tuoi Pokémon, blocco posizione, scala del testo, alto contrasto e sfondo personalizzato.

**Gioco** comprende ancoraggio e posizione, modalità della finestra (finestra, borderless, schermo intero), lettura automatica o manuale e lingua.

**Scorciatoie** permette di cambiare i tasti per overlay, modalità modifica, impostazioni e passo avanti della Guida.

**Profili** salva e richiama una configurazione completa: tema, posizione, dimensione, stato del Pokédex e impostazioni dei pannelli.

**Aggiornamenti** mostra la versione installata e il pulsante **Cerca aggiornamenti**.

## Aggiornamenti

La versione installata controlla GitHub all'avvio e dal pannello delle impostazioni. Se trova una versione più recente, mostra le novità e due scelte:

- **Aggiorna ora** scarica il programma di installazione, verifica il file quando la release fornisce un controllo di integrità, chiude LucarioDex e avvia l'installazione. Impostazioni e dati personali restano.
- **Salta (non consigliato)** avvia la versione attuale e ricorda la scelta, così lo stesso avviso non compare a ogni avvio.

Se il controllo non riesce, per esempio senza connessione, il programma si avvia normalmente.

## Scorciatoie

- `Ctrl + Alt + H`: mostra o nasconde l'overlay.
- `Ctrl + Alt + C`: attiva o disattiva la modalità modifica.
- `Ctrl + Alt + S`: apre le impostazioni.
- `Ctrl + Shift + N`: passo successivo nella Guida.
- `Ctrl + Shift + D`: apre o chiude Ditto Farm.

Le prime quattro si possono cambiare dalle impostazioni. `Ctrl + Shift + D` è la scorciatoia predefinita di Ditto Farm e non compare tra quelle modificabili.

## Icona nell'area di notifica

Il menu dell'area di notifica contiene **Scansiona**, **Impostazioni**, **Zona**, **Guida turni**, **Ditto Farm**, **PvE**, **Modalità modifica**, **Leggi turno**, **Scansione automatica** ed **Esci**.

La X chiude il programma e salva le impostazioni. Per nascondere solo l'overlay usa `Ctrl + Alt + H` o la modalità compatta. Il pannello PvP si apre dal pulsante **PvP** nell'overlay.

## Dati, backup e log

Impostazioni, profili, progressi del Pokédex e del PvE e squadre PvP stanno in:

```text
%APPDATA%\LucarioDex
```

Per un backup copia questa cartella. Per ripartire da zero cancellala: il programma la ricrea al successivo avvio.

Il log degli errori viene scritto in:

```text
%TEMP%\LucarioDex_error.log
```

Se il programma si chiude da solo, allega quel file quando chiedi assistenza.

## Problemi comuni

**L'overlay dice `Gioco: assente`.**
PokeMMO non è aperto, è minimizzato o il titolo della finestra non viene riconosciuto. Metti il gioco in primo piano e premi **Scansiona**.

**Non riconosce il Pokémon.**
Fai una scansione manuale con il gioco in primo piano. Controlla che la risoluzione non sia troppo diversa da quella standard e che menu o finestre non coprano nome e barra dei PS.

**Non riesco a cliccare il gioco.**
La modalità modifica è attiva. Premi `Ctrl + Alt + C` o disattivala dalle impostazioni o dalla tray.

**La scansione automatica è lenta.**
Attiva **Solo in battaglia** se non ti serve la lettura della zona, oppure usa la scansione manuale. Se hai attivato **Leggi turno**, tienilo presente.

**I danni non tornano.**
Controlla specie, livello, natura, IV, EV e selettori di stadio. Una natura sbagliata o un boost non aggiornato cambia molto la stima.

**Ho cambiato risoluzione o monitor.**
Riposiziona l'overlay e bloccalo di nuovo. Se usi l'ancoraggio, verifica che la modalità della finestra corrisponda al gioco.

**La Guida non avanza da sola.**
Attiva **Leggi turno** e assicurati che il numero di turno sia visibile. I percorsi senza turni si avanzano con **Avanti**.

**StratDex o la Guida PvE non mostrano dati.**
Installa l'ultima versione. Se il problema resta, scrivi nel canale di feedback indicando la versione e la parte che manca.

**L'aggiornamento non parte.**
Controlla la connessione e riprova con **Cerca aggiornamenti**. Se il download non supera la verifica di integrità, viene annullato. Puoi sempre scaricare il programma di installazione dalla pagina delle release.

**Il programma non parte.**
Apri `%TEMP%\LucarioDex_error.log` e allega il file quando chiedi assistenza.

## Note legali

LucarioDex è un overlay informativo. Legge la finestra visibile del gioco e il suo titolo per individuarla. Non modifica il client di PokeMMO, non inietta codice, non legge memoria, traffico di rete o file di gioco e non invia input né automatizza azioni. Non è un bot e non è un cheat.

L'uso è a tuo rischio. Verifica le regole di PokeMMO che ti riguardano. Se l'interfaccia del gioco cambia, alcune letture possono smettere di funzionare fino a un aggiornamento.

LucarioDex non è affiliato, approvato o sponsorizzato da Nintendo, Creatures Inc., GAME FREAK, The Pokémon Company, PokeMMO, Pokémon Showdown, mmoshowdown o BattGuide. Pokémon e i nomi dei personaggi sono marchi dei rispettivi proprietari. PokeMMO, Showdown e BattGuide sono citati solo per descrivere compatibilità e fonti dei dati.

I dati su Pokémon, mosse e incontri provengono da progetti della community PokeMMO e sono adattati a PokeMMO. I dati d'uso provengono da mmoshowdown.com. I team della community e i collegamenti Pokepaste appartengono ai rispettivi autori e sono attribuiti nell'app; il contenuto completo di BattGuide non viene copiato in LucarioDex.

Il software viene fornito così com'è, senza garanzie. Gli autori non rispondono di perdita di dati, restrizioni sull'account o altri danni derivanti dall'uso.

## Feedback

Per segnalare un problema indica cosa stavi facendo, cosa ti aspettavi, la zona e il Pokémon coinvolti e la versione che leggi in basso nell'app. Allega uno screenshot dell'overlay e del gioco nello stesso momento e, se c'è stato un errore, il file `%TEMP%\LucarioDex_error.log`.

Canale ufficiale: `t.me/lndefinizione`

---

Versione 1.1 · novembre 2026 · creato da @WolfHitech
