---
title: Quotes
permalink: /para/quotes.html
layout: para
---

## Quotes

There are three levels of quote to use, and examples are below. 


### Examples

#### quote.html

{% include feature/quote.md text="Our last day in camp. The order to get ready for an early start tomorrow has gone forth, and we must leave our delightful wild life and return to the land of boiled shirts and stovepipe hats." objectid="beinecke-pdf" source="Page 28"%}


*Code for regular quote:* 

```{% raw %}{% include feature/quote.md text="Our last day in camp. The order to get ready for an early start tomorrow has gone forth, and we must leave our delightful wild life and return to the land of boiled shirts and stovepipe hats." objectid="beinecke-pdf" source="Page 28"%}{% endraw %} ```

#### quote-medium.html

{% include feature/quote-medium.md text="Rhythm is a recurring movement of notes and rests (silences) in time. It’s the human perception of time." source="iconcollective.edu" source-link="https://iconcollective.edu/basic-music-theory/"  align="right" color="info" %}

*Code for medium quote:* 

```{% raw %}{% include feature/quote-medium.md text="Rhythm is a recurring movement of notes and rests (silences) in time. It’s the human perception of time." source="iconcollective.edu" source-link="https://iconcollective.edu/basic-music-theory/"  align="right" color="info" %}{% endraw %} ```

#### quote-big.html

{% include feature/quote-big.md text="Rhythm is a recurring movement of notes and rests (silences) in time. It’s the human perception of time." source="iconcollective.edu" source-link="https://iconcollective.edu/basic-music-theory/"  align="right" color="info" %}


*Code for big quote:* 

```{% raw %}{% include feature/quote-big.md text="Rhythm is a recurring movement of notes and rests (silences) in time. It’s the human perception of time." source="iconcollective.edu" source-link="https://iconcollective.edu/basic-music-theory/"  align="right" color="info" %}{% endraw %} ```


### Options:

- "text" = text from the quote or source
- "source" = [optional] who said the quote / where the quoted text is coming from 
- "source-link" = [optional]  link to the source (center, right, left)
- "color" = [optional] a Bootstrap color (primary, secondary, success, danger, warning, info, light, dark)
- "align" = [optional] text alignment (center, right, left)

