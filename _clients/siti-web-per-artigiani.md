---
title: Siti web per Artigiani
subtitle: Artigiani
excerpt: Siti web per giardinieri, idraulici, falegnami, imbianchini, elettricisti, imprese edili. Incrementa i tuoi utili grazie a questo tema bello e semplice da configurare.
external_url: http://potasiepe.com/
image_path: /images/clients/artigiani.jpg
---
Questo sito web per artigiani è stato realizzato per essere particolarmente semplice da modificare e per poter mostrare ai tuoi clienti la qualità del tuo lavoro. Guarda una [live demo](http://www.potasiepe.com/).
Incrementa la presenza web della tua attività con questo tema configurabile a piacere.

Artigiani è stato realizzto da [SitiWeb_FVG](/), il Cloud CMS per Jekyll.
Qui puoi trovare altri esempi di temi per [Jekyll](https://jekyllrb.com/showcase/){: rel="nofollow"} da cui trarre ispirazione.

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

Artigiani è stato costruito con [Jekyll](http://jekyllrb.com/){: rel="nofollow"} versione 3.7.2, ma supporta le future versioni.

Installa le dipendenze con [Bundler](http://bundler.io/){: rel="nofollow"}:

~~~bash
$ bundle install
~~~

Esegui `jekyll` tramite Bundler per assicurarti di stare usando la versione corretta:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

Artigiani è già ottimizzato per poter aggiornare facilmente le pagine, i dettagli della tua attività, i membri dello staff e i vari elementi che compongono il sito, come ad esempio la barra di navigazione ed il footer.

## SEO Tag

Questo sito usa il plugin [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag){: rel="nofollow"}. Devi inserire per lo meno un titolo nel front matter di ogni pagina. Guarda la [pagina del progetto](https://github.com/jekyll/jekyll-seo-tag){: rel="nofollow"} per maggiori opzioni.

## Google Analytics

[Google Analytics](https://www.google.com/analytics/){: rel="nofollow"} è uno strumento di analisi di terze parti. Per installarlo:

1. Aggiungi la tua Google Analytics key al file `_config.yml`.
2. Esegui il tuo sito in produzione `JEKYLL_ENV = production` (di default per SitiWeb_FVG e GitHub Pages).

## EventBrite

[EventBrite](https://www.eventbrite.com/){: rel="nofollow"} è un modulo eventi di terze parti che puoi inserire nel sito web. Per installarlo:

1. Crea un evento su EventBrite.
2. Copia il codice di incorporazione (embed) del Ticket Form dal Widgets menu item.
3. Copialo in `eventbrite_embed` in `_config.yml`.

## Image gallery / In primo piano

La galleria di immagini è popolata da un array nel fron matter in `index.html`. Per aggiungere foto ti basta copiare la struttura esistente.
