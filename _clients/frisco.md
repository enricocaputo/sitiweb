---
name: Frisco Template
subtitle: App marketing / template per Jekyll
external_url: https://brave-submarine.cloudvent.net/
image_path: /images/clients/frisco.jpg
---
Un template Jekyll per promuovere una applicazione web e un app mobile. Naviga la [live demo](https://brave-submarine.cloudvent.net/).
Incrementa la presenza web della tua app con questo tema configurabile a piacere.

Frisco è stato realizzto da [SitiWeb_FVG](/), il Cloud CMS per Jekyll.

Impara Jekyll direttamente dal [sito ufficiale](https://jekyllrb.com/).

## Caratteristiche

* Contact form
* Componenti pre-stilizzati
* Ottimizzazione per l'editing
* SEO tags
* Google Analytics
* Blog con paginazione
* Categorizzazione dei post
* Disqus commenti utenti ai post
* Sistema autore - membri staff
* Footer Configurabile
* Ottimizzato per editing mezzo CMS
* RSS/Atom feed

## Setup

1. Aggiungi i dettagli del tuo sito in `_config.yml`.
2. Aggiungi il tuo account Google Analytics in `_config.yml`.
3. Testa il tuo sito sul nostro server oppure in locale.

## Sviluppo

Frisco è stato costruito con [Jekyll](http://jekyllrb.com/) versione 3.7.2, ma supporta le future versioni.

Installa le dipendenze con [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Esegui `jekyll` tramite Bundler per assicurarti di stare usando la versione corretta:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

Frisco è già ottimizzato per poter aggiornare facilmente le pagine, i dettagli della tua attività, i membri dello staff e i vari elementi che compongono il sito, come ad esempio la barra di navigazione ed il footer.

### Posts

* Aggiungi, aggiorna e rimuovi un post nella cartella collection *Post*.
* Il campo *Autore* dello staff si collega ai *membri* della *collection Membri dello staff*.
* Cambia il file *defaults* quando nuovi post sono creati in `_posts/_defaults.md`.

### Contact Form

* Preconfigurato per lavorare con SitiWeb_FVG ma può essere facilmente indirizzato verso altri provider (ad es. [FormSpree](https://formspree.io/)).

### Staff

* Riutilizzato nel sito per salvare tempo ed evitare di dover modificare gli stessi dati in diverse parti del sito .

### Bara di Navigazione / Menu

* Raccolto in un file sotto forma di una lista di dati per offrire semplicità di accesso e modifica.
* Da impostare nella sezione *Data* / *Navigation*.

### Footer

* Raccolto in un file sotto forma di una lista di dati per offrire semplicità di accesso e modifica.
* Da impostare nella sezione *Data* / *Footer*.
