{% if page.summary %}
### Summary
{{ page.summary }}
{% endif %}

{% if page.reports %}
### Reports and Formal Correspondance
{% for report in page.reports %}
{% for author in page.authors %}
{% if report.author == author.name %}
* {{ report.date }}, [{{ report.author }}]({{ author.link }}): [{{ report.title }}]({{ report.link }})
{% endif %}
{% endfor %}
{% endfor %}
{% endif %}

{% if page.headlines %}
### Headlines
{% for headline in page.headlines %}
{% for author in page.authors %}
{% if headline.author == author.name %}
* {{ headline.date }}, [{{ headline.author }}]({{ author.link }}): [{{ headline.title }}]({{ headline.link }})
{% endif %}
{% endfor %}
{% endfor %}
{% endif %}
