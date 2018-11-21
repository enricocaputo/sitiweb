---
title: Siti web per Eventi, Sagre e Concerti
subtitle: Eventi, Sagre e Concerti
excerpt: Sito web ad alto impatto per eventi, sagre e concerti, è possibile effettuare anche la prevendita dei biglietti online, è possible aggiungere una sezione ecommerce.
external_url: https://whispering-boat.cloudvent.net/
image_path: /images/clients/malt.jpg
---
Sito web ad alto impatto per eventi, sagre e concerti, è possibile effettuare anche la prevendita dei biglietti online, è possible aggiungere una sezione ecommerce. Guarda una [live demo](https://whispering-boat.cloudvent.net/){: rel="nofollow"}. Il successo è assicurato!

Eventi è stato realizzto da [SitiWeb_FVG](/), il Cloud CMS per Jekyll.

Impara Jekyll direttamente dal [sito ufficiale](https://jekyllrb.com/){: rel="nofollow"}.

## Caratteristiche

* Pagine pre-costruite
* Componenti pre-stilizzati
* Ottimizzazione per l'editing
* SEO tags
* Google Analytics
* Blog con paginazione
* Categorizzazione dei post
* [EventBrite](https://www.eventbrite.com/){: rel="nofollow"}
* Contact Form
* Foto in primo piano e Carosello foto
* Image Gallery

## Setup

1. Aggiungi i dettagli del tuo sito in `_config.yml`.
2. Aggiungi il tuo account Google Analytics in `_config.yml`.
3. Testa il tuo sito sul nostro server oppure in locale.

## Sviluppo

Eventi è stato costruito con [Jekyll](http://jekyllrb.com/){: rel="nofollow"} versione 3.7.2, ma supporta le future versioni.

Installa le dipendenze con [Bundler](http://bundler.io/){: rel="nofollow"}:

~~~bash
$ bundle install
~~~

Esegui `jekyll` tramite Bundler per assicurarti di stare usando la versione corretta:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

Eventi è già ottimizzato per poter aggiornare facilmente le pagine, i dettagli della tua attività, i membri dello staff e i vari elementi che compongono il sito, come ad esempio la barra di navigazione ed il footer.

## SEO Tag

This site uses the [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag){: rel="nofollow"} plugin. You should at least set a title in front matter on each page. Have a look at the [project page](https://github.com/jekyll/jekyll-seo-tag){: rel="nofollow"} for more options.

## Google Analytics

[Google Analytics](https://www.google.com/analytics/){: rel="nofollow"} is a third party website analytics tool. To install:

1. Add your Google Analytics key to `_config.yml`.
2. Run your site in production `JEKYLL_ENV = production` (the default for CloudCannon and GitHub Pages).

## EventBrite

[EventBrite](https://www.eventbrite.com/){: rel="nofollow"} è un modulo eventi di terze parti che puoi inserire nel sito web. Per installarlo:

1. Crea un evento su EventBrite.
2. Copia il codice di incorporazione (embed) del Ticket Form dal Widgets menu item.
3. Copialo in `eventbrite_embed` in `_config.yml`.

## Image gallery / In primo piano

La galleria di immagini è popolata da un array nel fron matter in `index.html`. Per aggiungere foto ti basta copiare la struttura esistente.
