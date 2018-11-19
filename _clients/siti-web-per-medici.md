---
title: Siti web per Medici
subtitle: Studio Medico
excerpt: Sito web di impatto professionale per medici, studio medico, dentisti, paramedici, medicina dello sport ecc. I pazienti potranno prenotare gli appuntamenti online.
external_url: http://www.studiomedicoaurorapinerolo.it/
image_path: /images/clients/medici.jpg
---
Sito web di impatto professionale per studio medico, paramedici, medicina dello sport ecc. Gurda la [live demo](http://www.studiomedicoaurorapinerolo.it/).
Rafforza la presenza web del tuo studio medico con questo tema altamente personalizzabile:
permette ai pazienti di prenotare gli appuntamenti online.

Medici è stato realizzto da [SitiWeb_FVG](/), il Cloud CMS per Jekyll.

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

Medici è stato costruito con [Jekyll](http://jekyllrb.com/) versione 3.7.2, ma supporta le future versioni.

Installa le dipendenze con [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Esegui `jekyll` tramite Bundler per assicurarti di stare usando la versione corretta:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

Medici è già ottimizzato per poter aggiornare facilmente le pagine, i dettagli della tua attività, i membri dello staff e i vari elementi che compongono il sito, come ad esempio la barra di navigazione ed il footer.

### Posts

* Add, update or remove a post in the *Posts* collection.
* The **Staff Author** field links to members in the **Staff** collection.
* Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs` folder.
* Change the defaults when new posts are created in `_posts/_defaults.md`.

### Contact Form

* Preconfigurato per lavorare con SitiWeb_FVG ma può essere facilmente indirizzato verso altri provider (ad es. [FormSpree](https://formspree.io/)).
* Invia le email all'indirizzo indicato in *company details*.

### Staff

* Reused around the site to save multiple editing locations.
* Add `excluded_in_search: true` to any documentation page's front matter to exclude that page in the search results.

### Footer

* Raccolto in un file sotto forma di una lista di dati per offrire semplicità di accesso e modifica.
* Da impostare nella sezione *Data* / *Footer*.

### Dettagli attività

* Riutilizzato in tutto il sito per tempo ed evitare ripetizioni.
* Da impostare nella sezione *Data* / *Company*.