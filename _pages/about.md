---
permalink: /
title: "Alexander Kilpatrick"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Associate Professor in the [Center for Language Research](https://www.u-aizu.ac.jp/labs/clr/) at the University of Aizu, Japan, and director of the Language, Cognition, and Computation Laboratory.

My research explores language structure and cognition using computational and information-theoretic approaches. I am particularly interested in how surprisal, entropy, and phonological form shape the way we process and remember words.

## Research Interests
- Psycholinguistics and cognitive processing
- Information theory in language (surprisal, entropy)
- Phonetics and phonology
- Iconicity and sound symbolism
- Computational linguistics
- Machine Learning

## Selected Publications

{% for pub in site.publications limit:5 %}
- **{{ pub.title }}** — *{{ pub.citation }}* [DOI]({{ pub.doi }}) [PDF]({{ pub.pdf_url }})
{% endfor %}

[Full publication list →](/publications/)

## Recent News / Blog

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%Y-%m-%d" }})
{% endfor %}

[All posts →](/blog/)

## CV & Contact

[Download CV (PDF)](/files/cv.pdf) | [View CV](/cv/) | alex@u-aizu.ac.jp
  
## Prospective Students

I welcome enquiries from students interested in graduate supervision. My lab works at the intersection of linguistics, cognitive science, and computation, and I am always happy to hear from motivated students with genuine interest in these areas.

That said, I receive a high volume of enquiries and am not able to respond to generic or mass-sent emails. If you are seriously interested in working with me, please take the time to read some of my recent work and write to me explaining specifically how your research interests connect with mine. A thoughtful, targeted email will always get a response. A template will not.

## Contact
alex@u-aizu.ac.jp
