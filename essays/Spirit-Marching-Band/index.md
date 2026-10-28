---
# Change these five lines as soon as you copy this starter.
title: Spirit Marching Band
author: Jeremiah Agrusa
category: Athletics             # change to a category from the student guide
header-image: Trumpets.2023.gif   # the filename of your own image
header-caption: UNM bands homepage

# Fill these in later, once your research is under way.
card-description: Replace this with two sentences that summarize the story your essay tells and why it matters.
start:                                   # the year your story begins, shown on the map

# Leave this line as it is.
layout: essay
---
A Brief History of the University of New Mexico Spirit Marching Band

The Spirit Marching Band at the University of New Mexico (UNM) is one of the university's oldest and most visible student organizations. According to the UNM Bands program, the ensemble has served the university continuously since 1917, making it more than a century old. Throughout its history, the band has functioned as both a musical ensemble and a public ambassador for the university, supporting athletics, school traditions, and community events.

The band's origins coincided with the growth of intercollegiate athletics at UNM in the early twentieth century. While detailed records of its earliest directors are not readily available through current university sources, UNM officially identifies 1917 as the beginning of the Spirit Marching Band's history. Since then, the group has become a fixture at football games, pep rallies, and university ceremonies.

A major element of the band's identity is its performance of"Hail, New Mexico!", the university's official fight song. The song was composed in 1931 by UNM music professor Lena Clauve, with lyrics written by English professor George St. Clair. Since its creation, the fight song has been performed by the Spirit Marching Band at athletic events and ceremonial occasions, helping to define the sound of UNM school spirit.

By the late twentieth century, the ensemble had developed into a full collegiate marching band. Evidence of this period can be seen in a documented 1988 performance by the University of New Mexico Marching Band, then known simply as "The Spirit." At that time, the band was directed by Gregory G. Clemons, assisted by Doug Nottingham and Timothy Dressel. The performance repertoire included traditional university music such as "Hail, New Mexico" and "Fight On, Lobos," along with concert and popular selections.

In the modern era, the Spirit Marching Band has become an integral component of UNM athletics. The band performs at all home football games, taking part in pregame and halftime shows while also leading crowd engagement throughout the game. Members perform for fans in tailgate areas before kickoff and support the student section inside the stadium. The ensemble accompanies the football team to postseason bowl appearances when invited.

The band's role extends beyond game-day entertainment. It serves as a recruiting and outreach organization for the university and hosts the Zia Marching Band Fiesta, described by UNM as one of the largest marching-band competitions in the Southwest. This event brings together high school bands from across the region and strengthens UNM's connections with music programs throughout New Mexico and neighboring states.

Leadership of the Spirit Marching Band has evolved over time. As of the mid-2020s, the ensemble is directed by Dr. Geoffrey Harman, who serves as UNM's Director of Athletic Bands and Assistant Director of Bands. Harman's responsibilities include directing both the Spirit Marching Band and the university's basketball pep band, Soundpack. Under his leadership, the band continues its mission of representing UNM at athletic and public events.

Today, the Spirit Marching Band remains one of the most recognizable organizations on the UNM campus. The university describes its mission as serving as ambassadors for UNM, supporting the Lobos with enthusiasm, and providing high-quality musical performances. More than a century after its founding in 1917, the band continues to be a central part of university traditions and student life.

Sources
University of New Mexico Bands, “Spirit Marching Band.”
University of New Mexico Department of Music, “UNM Bands Ensembles.”
University of New Mexico Course Catalog, “Spirit Marching Band (MUSC 2735).”
University of New Mexico Bands Home Page.
University of New Mexico Department of Music, biography of Dr. Geoffrey Harman.
Wikipedia, “Hail, New Mexico.”
“University of New Mexico Marching Band ‘The Spirit’ 1988” (archival performance information).

This first paragraph should give readers a quick way into your topic. Start with a scene, a question, a surprising fact, or a problem your essay will explain. You do not need to summarize everything here. Help the reader understand why this campus place, person, organization, object, or event deserves attention.

Keep the above lead paragraph first. Do not put an image, a heading, or any other component above it.

## Main Story

Use this section to tell the most important part of the history. Keep paragraphs short enough for online reading. A good paragraph usually develops one idea, source, moment, or change over time.

Use specific evidence from the archive. Name dates, people, places, decisions, conflicts, renovations, controversies, or missing records when they matter. The goal is not just to list facts. The goal is to explain what those facts reveal about UNM and its history.

<!-- Full-width figure. This is the default for any landscape photo wider than about 700px.
     image-path is just the filename: upload your images into this essay's folder,
     next to index.md. -->

{% include images/figure.html
  class="img-center"
  width="100%"
  caption="Replace this caption. Say why the image matters, not just what it shows, then cite where you found it: [Center for Southwest Research](https://econtent.unm.edu/), collection and box number."
  image-path="sample-archive-photo.jpg"
%}

Every image needs a caption, including this one. A caption should explain what the reader should notice and where the image came from. Captions accept Markdown, so use `[source](https://example.com/)` to link to a digital collection whenever the image has an online home.

## What Changed

Use this section to explain change over time. What did your topic used to be? How did people use it, describe it, fund it, argue about it, rename it, neglect it, preserve it, or forget it?

This is a good place to connect your specific topic to a larger campus pattern: enrollment growth, architecture, student life, race, gender, labor, protest, public memory, administration, technology, or access.

<!-- Carousel: use when you have three or more images that belong together but do not
     each need their own paragraph. Images are split on commas, captions on the | character.
     Carousel captions are plain text: Markdown links will NOT work here, so write out
     the collection name and box number instead of linking. -->

{% assign images =
"sample-archive-photo.jpg,
sample-second-photo.jpg,
sample-primary-source.jpg" | split: ','
%}

{% assign headers =
"Replace with a short slide title,
Replace with a short slide title,
Replace with a short slide title" | split: ','
%}

{% assign captions =
"Replace this caption. Explain what this slide shows and why it matters. Center for Southwest Research, collection name, box number.|
Replace this caption. Every slide needs one. Center for Southwest Research, collection name, box number.|
Replace this caption. Plain text only in carousels, so spell out the source instead of linking. Center for Southwest Research, collection name, box number." | split: '|'
%}

{% include images/carousel.html
  images=images
  headers=headers
  captions=captions
%}

Delete the carousel if you do not have a set of images that works this way. Three related photographs, a series of floor plans, or a run of newspaper clippings are all good candidates. Two images that need to be compared directly are usually better as a pair than as a carousel.

## Evidence

Use this section to show readers a document, not just a photograph. Scanned letters, meeting minutes, ledgers, clippings, and blueprints all reward close looking, and they prove you spent time in the boxes.

<!-- Portrait documents are the exception to the full-width rule. A tall scan at 100%
     is over 1200px tall and swallows the screen, so center it and leave it near 55%.
     Keep it centered, not floated. -->

{% include images/figure.html
  class="img-center"
  width="55%"
  caption="Replace this caption. Tell readers what to notice in the document and why it changes how they should understand your topic. Cite the collection, box, and folder."
  image-path="sample-primary-source.jpg"
%}

Explain what the document says, what it does not say, and how it fits the story. A source you actually read and explain is worth more than three you only mention.

## Why This History Matters

End by returning to the present. How should readers see this campus place, person, organization, object, or event differently after reading your essay? Point to continued use, memory, loss, gaps in the archive, or campus change rather than announcing a conclusion.

{% capture bibliography %}
- Replace this with your first source. Include enough detail that someone else could find it: collection name, box, and folder for archival material.
- Replace this with your second source.
- Replace this with your third source.
{% endcapture %}

{% include typography/bibliography.html
  title="Bibliography"
  content=bibliography
%}
