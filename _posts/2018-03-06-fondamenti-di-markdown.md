---
title: Fondamenti di Markdown
excerpt: Formattazione di base
image: 'https://www.sitiweb.fvg.it/images/posts-images/love-markdown.png'
image_featured: true
author_staff_member: enrico
show_comments: true
date: 2018-10-29
---
## Formattazione di base

Questa nota **mostra** alcuni aspetti di ciò che il linguaggio *Markdown* è in grado di fare.

---

## Titoli
Ci sono sei livelli di titoli. Corrispondono ai sei livelli di intestazioni HTML. Probabilmente li hai già notati nella pagina. Ogni livello in basso utilizza un ulteriore carattere hash. Per brevità ne mostriamo solamente 4, da H1 ad H4 (escusi quindi H5 ed H6).

# I titoli possono essere piccoli

## I titoli possono essere piccoli

### I titoli possono essere piccoli

#### I titoli possono essere piccoli

{% highlight raw %}
# Heading
## Heading
### Heading
#### Heading
{% endhighlight %}

---

## Liste

### Liste ordinate

1. Item 1
2. Un secondo item
3. il numero 3

{% highlight raw %}
1. Item 1
2. Un secondo item
3. il numero 3
{% endhighlight %}

### Elenchi

* An item
* Another item
* Yet another item
* And there's more...

{% highlight raw %}
* An item
* Another item
* Yet another item
* And there's more...
{% endhighlight %}

---

## Modificatori di paragrafo

### Citazioni

> Ecco una citazione. L'esempio dovrebbe essere auto esplicativo. Le citazioni vengono rientrate automaticamente.

{% highlight raw %}

> Here is a quote.

{% endhighlight %}

---

## URLs

Gli URLs possono essere scritti in diversi modi:

* Named link to [Mark Down](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Sometimes you just want a URL like <https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet>.

{% highlight raw %}
* [MarkItDown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* <https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet>.
{% endhighlight %}

---

## Immagini

Markdown può anche contenere images. Ormai dovreste aver familiarizzato: semplice vero?

{% highlight raw %}
![Markdowm Image](/image/url)
{% endhighlight %}

![Markdowm Image]({{ site.url }}media/ghost-blog.jpg)
