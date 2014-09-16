 - [Home]({{ site.absoluteurl }}{{ site.baseurl }}){% for i in (1..site.sections.size) %}{% for sec in site.sections %}{% if sec.order == i %}
 - [{{ sec.name }}]({{ site.absoluteurl }}{{ site.baseurl }}{{ sec.url }}){% break %}{% endif %}{% endfor %}{% endfor %}
^
 - [Email Us](mailto:gdavis@teletekinc.com)
^
* * *
