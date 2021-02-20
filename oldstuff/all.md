---
title: All Include Options
permalink: /para/all.html
layout: para
map-on: true
---

## Margin note 

Margin

### Options:

- "text" = text for the margin note -- this can be written in HTML to add links, etc. 
- "id" = a unique id (short phrase is best) to connect the location and note
- "text-link" = [optional] link for the entire note; you can also add links to certain words via writing the text in HTML
- "color" = [optional] a Bootstrap color (primary, secondary, success, danger, warning, info, light, dark)

### Example

```{% raw %}{% include feature/marginnote.html id="marginnote-3" text="This is a margin note that is linked to the end of the sentence or even placed in the middle of a sentence."%}{% endraw %} ```

This is a fake paragraph so that we can demonstrate the margin note. 
{% include feature/marginnote.html id="marginnote-3" text="This is a margin note that is linked to the end of the sentence or even placed in the middle of a sentence."%} The margin note is a note that goes in the margin, so it is well named. 


## Sidenote 

There are three levels of quote to use, and examples are below. 

### Options:

- "text" = text for the side note -- this can be written in HTML to add links, etc. 
- "id" = a unique id (short phrase is best) to connect the location and note
- "text-link" = [optional] link for the entire note; you can also add links to certain words via writing the text in HTML
- "color" = [optional] a Bootstrap color (primary, secondary, success, danger, warning, info, light, dark)

### Example


```{% raw %}{% include feature/sidenote.html id="note2" text="This is a sidenote that is linked to the end of the sentence ending turips over there."%}{% endraw %} ```

This is a fake paragraph so that we can demonstrate the side note. 
{% include feature/sidenote.html id="note2" text="This is a sidenote that is linked to the end of the sentence ending turips over there."%} The sidenote is a note that goes on the side, so it is well named. 


## Quotes

There are three levels of quote to use, and examples are below. 

### Options:

- "text" = text from the quote or source
- "source" = [optional] who said the quote / where the quoted text is coming from 
- "source-link" = [optional]  link to the source (center, right, left)
- "color" = [optional] a Bootstrap color (primary, secondary, success, danger, warning, info, light, dark)
- "align" = [optional] text alignment (center, right, left)


### Example

#### quote.html

{% include feature/quote.md text="Our last day in camp. The order to get ready for an early start tomorrow has gone forth, and we must leave our delightful wild life and return to the land of boiled shirts and stovepipe hats." objectid="beinecke-pdf" source="Page 28"%}


*Code for quote:* 

```{% raw %}{% include feature/quote.md text="Our last day in camp. The order to get ready for an early start tomorrow has gone forth, and we must leave our delightful wild life and return to the land of boiled shirts and stovepipe hats." objectid="beinecke-pdf" source="Page 28"%}{% endraw %} ```

#### quote-medium.html

{% include feature/quote-medium.md text="Rhythm is a recurring movement of notes and rests (silences) in time. It’s the human perception of time." source="iconcollective.edu" source-link="https://iconcollective.edu/basic-music-theory/"  align="right" color="info" %}


*Code for big quote:* 

```{% raw %}{% include feature/quote-medium.md text="Rhythm is a recurring movement of notes and rests (silences) in time. It’s the human perception of time." source="iconcollective.edu" source-link="https://iconcollective.edu/basic-music-theory/"  align="right" color="info" %}{% endraw %} ```

#### quote-big.html

{% include feature/quote-big.md text="Rhythm is a recurring movement of notes and rests (silences) in time. It’s the human perception of time." source="iconcollective.edu" source-link="https://iconcollective.edu/basic-music-theory/"  align="right" color="info" %}


*Code for big quote:* 

```{% raw %}{% include feature/quote-big.md text="Rhythm is a recurring movement of notes and rests (silences) in time. It’s the human perception of time." source="iconcollective.edu" source-link="https://iconcollective.edu/basic-music-theory/"  align="right" color="info" %}{% endraw %} ```