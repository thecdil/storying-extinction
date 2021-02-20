---
title: Side Note
permalink: /para/sidennote.html
layout: para
---

## Sidenote 


### Example


```{% raw %}{% include feature/sidenote.html id="note2" text="This is a sidenote that is linked to the end of the sentence ending turips over there."%}{% endraw %} ```

This is a fake paragraph so that we can demonstrate the side note. 
{% include feature/sidenote.html id="note2" text="This is a sidenote that is linked to the end of the sentence ending turips over there."%} The sidenote is a note that goes on the side, so it is well named. 



### Options:

- "text" = text for the side note -- this can be written in HTML to add links, etc. 
- "id" = a unique id (short phrase is best) to connect the location and note
- "text-link" = [optional] link for the entire note; you can also add links to certain words via writing the text in HTML
- "color" = [optional] a Bootstrap color (primary, secondary, success, danger, warning, info, light, dark)
