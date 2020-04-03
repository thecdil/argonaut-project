---
title: Highlights
nav: true
---

# Argonaut highlights

The [front page of the Argonaut digital collection](https://www.lib.uidaho.edu/digital/argonaut/index.html) features a randomly generated "front page" made of snippets from Argo issues through the years.
This provides an engaging entry point to scan the weird and interesting contents of Argonaut and invite people to explore.
Users can click on a highlight to visit the related Argonaut issue.

## Choosing highlights

While working on metadata for Argonaut issues you will be browsing the contents of each PDF.
If you find a story, headline, ad, or image that is particularly interesting, you can create a highlight to be added to the front page feature.
Think about snippets that are:

- representative of the era (e.g. the common ads from the 1950s)
- represents important university events, places, history, or figures (e.g. fire in admin building)
- reflects important international events/news (e.g. students to WWII)
- fun, weird, wacky, and/or unexpected content

Every issue does *not* need a highlight, but we aim to have a handful of highlights from each year over all. 

## Create a highlight

Once you find an interesting highlight, use a [screenshot tool](#screenshot-tools) to grab an image directly from the PDF.

{% include card.md text="
1. Zoom in on the area of the PDF (*if necessary*).
2. Use a rectangular selection to closely outline the highlight (*close cropped*).
3. Save the screenshot as a PNG carefully following the naming convention: `objectid_size_title.png`.
4. Upload to your Google folder.
" %}

Getting the filename of the highlight correct is important since it provides the metadata that will link it to an Argonaut issue.
Please carefully create the filename following the naming convention, with no spaces or weird characters.
Each part of the name is joined by an underscore (`_`).
Every highlight image filename will follow the pattern:

`objectid_size_title.png`

Where:

- `objectid` is the ID of the PDF you captured it from (this follows the pattern `arg-yyyy-mm-dd` and can be found in the link to the PDF or PDF filename)
- `size` use sm, md, lg, or xl to indicate the number of columns the highlight should take up in the web page display (horizontal width). 
    - `sm` is 1 column (~25% of the news page)
    - `md` is 2 columns (a medium image, two column article, or ad, etc)
    - `lg` is 3 columns (a large image or ad, etc)
    - `xl` is 4 columns (typically a headline that crosses the full page width)
- `title` is a descriptive word to make your filename unique. Do not use spaces or weird characters. e.g. `frogs`, `play`, `cigs`. 

For example:

- `arg-1913-10-16_md_football.png` might be a medium photograph of the football team from the front page of [arg-1913-10-16](https://digital.lib.uidaho.edu/utils/getfile/collection/argonaut/id/1071/filename/arg-1913-10-16.pdf).
- `arg-1985-10-11_sm_jacket.png` might be a small ad for the "Miami Vice jacket" found on page 11 of [arg-1985-10-11](https://digital.lib.uidaho.edu/utils/getfile/collection/argonaut/id/9411/filename/arg-1985-10-11.pdf)

<div class="row my-3 h-100">
<div class="col-md-6 p-0 border">
<img src="{{ '/images/arg-1913-10-16_md_football.png' | relative_url }}" class="w-100" alt="football team photo">
<br>
<small>md = 2 column width, ~%50</small>
</div>
<div class="col-md-3 p-0 border">
<img src="{{ '/images/arg-1985-10-11_sm_jacket.png' | relative_url }}" class="w-100" alt="miami vice jacket">
<br>
<small>sm = 1 column width, ~%25</small>
</div>
</div>

## Screenshot Tools 

- Windows: "Snipping Tool", use the "Rectangular Snip" option.
- Mac: 
- Linux: "Screenshot", use "Select area to grab" option.
