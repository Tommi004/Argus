# Argus

Progetto del corso di **Complex Systems Design**
del corso di laurea magistrale in Informatica.

Argus è un assistente basato su intelligenza artificiale per
l'ispezione visiva di componenti elettronici. L'obiettivo è supportare
l'operatore nell'individuazione e nella revisione dei difetti.

## Obiettivi

Il sistema dovrà:

- distinguere componenti conformi, sospetti e difettosi;
- localizzare le anomalie nelle immagini;
- indicare il tipo di difetto probabile e una misura di confidenza;
- consentire la revisione dei risultati da parte dell'operatore;
- rendere disponibili risultati strutturati tramite un'API;
- conservare le informazioni necessarie alla tracciabilità.

## Gruppo di lavoro

| Membro | Responsabilità principale |
| --- | --- |
| Stefano Salvatori | Dati, baseline e valutazione sperimentale |
| Valerio Virgili | Modelli di intelligenza artificiale e architettura |
| Tommaso Leonardi | API, interfaccia e integrazione |

Le decisioni principali, la relazione e la demo sono condivise.

## Dataset

Il dataset scelto per le prime prove è **Real-IAD**,
partendo dalla categoria **PCB**.

Sono disponibili immagini multivista e maschere dei difetti.
Le viste dello stesso componente devono rimanere nello stesso
insieme durante la suddivisione dei dati.

Le immagini del dataset restano fuori dalla repository.
Saranno documentate le istruzioni per ottenere e preparare i dati.

- [Sito ufficiale Real-IAD](https://realiad4ad.github.io/Real-IAD/)
- [Dataset su Hugging Face](https://huggingface.co/datasets/Real-IAD/Real-IAD)

## Stato del progetto

Il progetto è nella fase iniziale di configurazione.

Le prossime attività sono:

- configurare gli ambienti di sviluppo;
- preparare il caricamento condiviso dei dati;
- eseguire una prima baseline;
- definire il formato di input e output;
- realizzare una prima API e un'interfaccia di revisione.

Le istruzioni di installazione ed esecuzione saranno aggiunte
dopo la verifica dei primi test.

## Gestione dei file

La repository contiene codice, configurazioni e documentazione.

Dataset, pesi dei modelli, ambienti virtuali e credenziali
devono essere conservati separatamente ed esclusi da Git.

Prova di collaborazione Git completata da Tommaso.