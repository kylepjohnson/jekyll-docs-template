---
layout: default
title: "Classical Language Toolkit"
---

The Classical Language Toolkit (CLTK) offers natural language processing support for Classical languages. In some areas, it extends the [NLTK](http://www.nltk.org/).

## Goals

*   compile analysis-friendly corpora in a variety of Classical languages (currently available for Chinese, Coptic, Greek, Latin, and Pali);
*   gather, improve, and generate linguistic data required for NLP (Greek and Latin are in progress, with [more in the pipeline](https://github.com/cltk/cltk/wiki/List-of-Classical-languages));
*   develop a free and open platform for generating reproducible, scientific research that advances the study of the languages and literatures of the ancient world.


## Academic Advisors

* Neil Coffee, University at Buffalo (Associate Professor of Classics); [Tesserae](http://tesserae.caset.buffalo.edu/) (Principal Investigator)
* Gregory Crane, Universität Leipzig (Humboldt Chair of Digital Humanities), Tufts University (Professor of Classics); [Perseus](http://www.perseus.tufts.edu) (Editor–in–Chief) and [Open Philology](http://www.dh.uni-leipzig.de/wo/open-philology-project/) (Director)
* Peter Meineck, New York University (Associate Professor of Classics); Aquila Theatre (Founder), Ancient Greeks/Modern Lives (Founder, Director)
* Leonard Muellner, Brandeis University (Professor Emeritus of Classical Studies); Center for Hellenic Studies (Director of Publications, Information Technology and Libraries)

### Get Started

Start by [creating a new post](http://jekyllrb.com/docs/posts/) one of the categories listed in `_config.yml`. It will appear in the navigation on the left once recompiled. Or use the supplied script to make creating pages easier:

```bash
ruby bin/jekyll-page "Some Page Title" ref
```

#### Don't Forget

- Add your own content to this page (i.e. `index.md`) and change the `title`
- Change `title` and `subtitle` defined in `config.yml` for your site
- Set the `baseurl` in `_config.yml` for your repo if deploying to GitHub pages
