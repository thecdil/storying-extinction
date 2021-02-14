<div class="epigraph">
<blockquote class="h1 m-5" ><p style="font-size:2.5em !important; line-height:1.4em">{{ include.text |}}</p>
<footer>{% if include.objectid %}{%- assign item = site.data[site.metadata] | where: "objectid", include.objectid | first -%}<a href="{{ '/item.html' | relative_url | append: '?id=' | append: item.objectid }}">{{item.title}}</a>, {% endif %}{% if include.source-link %}<a href="{{include.source-link }}" target="_blank">{{include.source}}</a>{% else %}{include.source}}{% endif %}</footer></blockquote>
</div>  