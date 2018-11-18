---
name: Artisan Template
subtitle: Artigiano / template per Jekyll
external_url: http://potasiepe.com/
image_path: /images/clients/potasiepe.png
---
Not for profit themed template for Jekyll. Browse through a [live demo](http://potasiepe.com).
Increase the web presence of a not for profit or cause website with this configurable theme.

Artisan è stato realizzto da [SitiWeb_FVG](/), il Cloud CMS per Jekyll.

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

Artisan è stato costruito con [Jekyll](http://jekyllrb.com/) versione 3.7.2 e supporta le future versioni.

Installa le dipendenze con [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Esegui `jekyll` tramite Bundler per assicurarti di stare usando la versione corretta:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

Artisan è già ottimizzato per poter aggiornare facilmente le pagine, i dettagli della tua attività, i membri dello staff e i vari elementi che compongono il sito, come ad esempio la barra di navigazione ed il footer.

## SEO Tag

Questo sito usa il plugin [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag). Devi inserire per lo meno un titolo nel front matter di ogni pagina. Guarda la [pagina del progetto](https://github.com/jekyll/jekyll-seo-tag) per maggiori opzioni.

## Google Analytics

[Google Analytics](https://www.google.com/analytics/) è uno strumento di analisi di terze parti. Per installarlo:

1. Aggiungi la tua Google Analytics key al file `_config.yml`.
2. Esegui il tuo sito in produzione `JEKYLL_ENV = production` (di default per SitiWeb_FVG e GitHub Pages).

### Dettagli attività

* Riutilizzato in tutto il sito per tempo ed evitare ripetizioni.
* Da impostare nella sezione *Data* / *Company*.

### Contact Form

* Preconfigurato per lavorare con SitiWeb_FVG ma può essere facilmente indirizzato verso altri provider (ad es. [FormSpree](https://formspree.io/)).
* Invia le email all'indirizzo indicato in *company details*.
