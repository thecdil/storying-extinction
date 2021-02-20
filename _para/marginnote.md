---
title: Margin Note
permalink: /para/marginnote.html
layout: para
---

## Margin note 

### Example

This is a fake paragraph so that we can demonstrate the margin note. 
{% include feature/marginnote.html id="marginnote-3" text="This is a margin note that is linked to the end of the sentence or even placed in the middle of a sentence." %} The margin note is a note that goes in the margin, so it is well named. 

```{% raw %}{% include feature/marginnote.html id="marginnote-3" text="This is a margin note that is linked to the end of the sentence or even placed in the middle of a sentence. Note that nothing connects to the text (there is no marker) but if you are on a phone, a little bullseye thing shows up."%}{% endraw %} ```

### Options:

- "text" = text for the margin note -- this can be written in HTML to add links, etc. 
- "id" = a unique id (short phrase is best) to connect the location and note
- "text-link" = [optional] link for the entire note; you can also add links to certain words via writing the text in HTML
- "color" = [optional] a Bootstrap color (primary, secondary, success, danger, warning, info, light, dark)



