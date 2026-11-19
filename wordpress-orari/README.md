# Nightfall RP — Orari delle lezioni (WordPress)

Plugin WordPress per gli orari della Scuola di Magia di Hogwarts, con 1° e 2° anno, settimana 1 e 2 e le quattro Case.

## Installazione

1. Scarica la cartella `nightfall-orari` con tutti i file (compresi `assets/` e `data/`) e comprimila in ZIP, oppure usa lo ZIP installabile fornito nella conversazione.
2. Su WordPress vai in **Plugin → Aggiungi nuovo → Carica plugin** e attiva il plugin.
3. Apri **Orari Nightfall** per aggiornare materie, fasce orarie e corpo docenti.
4. Nella scheda **Strumenti e pubblicazione** crea la pagina pubblica, oppure inserisci `[nightfall_orari]` in una pagina.

Le lezioni non assegnate sono indicate come **Tempo libero**. I docenti sono mostrati agli studenti per impostazione predefinita, ma la visibilità si può disattivare.

## Corpo docenti — dati iniziali

| Materia | Professore 1 | Professore 2 | Professore staff |
|---|---|---|---|
| DCAO | Stroud Warren | Silas Vane | — |
| Pozioni | Kailen Crimorv | — | — |
| Incantesimi | Da assegnare | — | Kassian Malakor |
| Cura delle Creature Magiche | Celeste Firechild | — | — |
| Erbologia | Da assegnare | — | — |
| Divinazione | Da assegnare | — | — |
| Trasfigurazione | Victor Olms | Arcan Draconis | Elias Valemont |
| Storia della Magia | Athanasius Quillivant | Alaric Whitmore | Kenneth Adebayo |
| Medimagia | Dorian Willow | — | — |

Questi nominativi sono tratti dal foglio Google di partenza e sono **modificabili dall'amministratore WordPress**. Il repository non si aggiorna da WordPress automaticamente.

## Importante

**GitHub Pages non esegue PHP né WordPress.** Questo repository conserva il codice sorgente. Per gestire gli orari online serve un'installazione WordPress su un hosting PHP/MySQL.

Il programma iniziale deriva dal foglio Google condiviso il 19 novembre 2026. La sincronizzazione con Google Sheets **non è automatica**; è disponibile l'importazione manuale CSV.

## Anteprima

Apri `anteprima/index.html` per consultare una **dimostrazione statica** degli orari e dei docenti. Non salva le modifiche e non si sincronizza con WordPress.
