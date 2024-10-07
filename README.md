# Personnal Website

## Prerequisites

- ruby > 3.0.0
- gem > 3.2.3 

## Installation

Follow the instructions in the [Jekyll Docs](https://jekyllrb.com/docs/installation/) to complete the installation of
the basic environment. [Git](https://git-scm.com/) also needs to be installed.
Then, follow [Chirpy's install guide](https://chirpy.cotes.page/posts/getting-started/)

All of this is technically optional since you can just edit the markdown file and push them to the repos and it'll work.  
But you won't have access to any feature, including local building/hosting of the doc to see how what you write renders.

## Translation

I tried setting up i18n, and it works but it's a hassle since I need to write each article once per language.
So if you wanna translate some of my stuff for me, first of all, thank you very much :)
And then, please do it on a `translate/article_name` branch then create a pull request to main. I still want to check what goes on my website.

For now, most articles have their english file ready, but if they don't exist, create it in `_i18n/en` with the same name as the french article.

### Metadatas

You can copy the metadata at the top of the file and switch the language. For instance:

In french: 

```md
---
layout: post
title:  "Final Fantasy I - Des Débuts Humbles"
tags: final-fantasy
category: "Final Fantasy Marathon"
date: "2023-10-15"
lang: fr
image:
  path: /assets/img/posts_preview_images/ff1_logo.jpeg
  alt: Final Fantasy I Logo
---
```

In english:

```md
---
layout: post
title:  "Final Fantasy I - Humble Begginings" <- Translate the title here
tags: final-fantasy <- Translate tags if needed
category: "Final Fantasy Marathon" <- Same for the category
date: "2023-10-15"
lang: en  <- Different language here
image:
  path: /assets/img/posts_preview_images/ff1_logo.jpeg
  alt: Final Fantasy I Logo
---
```

Note: Tags and Categories are separated per language. For example, the tag "avis-rapide" is exclusive to the french version of the site (unless it's used in another language too).

### Switch languages

The default language is french, just add `/en/` after the base url to access the english version of the page.

You can also add this to your file to create a clickable link switching between french and english:

```md
{% if site.lang == "fr" %}
  {% capture english_link %}{{ site.url }}/en{{ page.url }}{% endcapture %}
  <a href="{{ english_link }}" >{% t pages.english_article %}</a>
{% elsif site.lang == "en" %}
  {% capture french_link  %}{{ site.url }}{{ page.url }}{% endcapture %}
 <a href="{{ french_link }}" >{% t pages.french_article %}</a>
{% endif %}
```

## Useful stuff:

[Chirpy's Documentation](https://github.com/cotes2020/jekyll-theme-chirpy/wiki)

## License

This work is published under [MIT][mit] License.

[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[chirpy]: https://github.com/cotes2020/jekyll-theme-chirpy/
[use-template]: https://github.com/cotes2020/chirpy-starter/generate
[CD]: https://en.wikipedia.org/wiki/Continuous_deployment
[mit]: https://github.com/cotes2020/chirpy-starter/blob/master/LICENSE
