<h2 id="selected-publications">Selected Publications · [<a href="{{ site.google_scholar }}" target="_blank" rel="noopener">Full List →</a>]</h2>

<h3>Journal Articles</h3>

<table>
{% for link in site.data.publications.main %}
<tr>
<td>
<b>{{ link.title }}</b><br />
{{ link.authors }}<br />
<i>{{ link.conference }}</i><br />
{% if link.pdf %}<a href="{{ link.pdf }}" target="_blank" rel="noopener">Paper</a>{% endif %}
{% if link.code %} · <a href="{{ link.code }}" target="_blank" rel="noopener">Code</a>{% endif %}
</td>
</tr>
{% endfor %}
</table>
