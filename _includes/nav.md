 - {% if page.url contains 'index' %}{:.{{ site.css.active }}}Home{% else %}[Home]({{ site.absoluteurl }}{{ site.baseurl }}){% endif %}{% for i in (1..site.sections.size) %}{% for sec in site.sections %}{% if sec.order == i %}
 - {% if page.url contains sec.url %}{:.{{ site.css.active }}}{{ sec.name }}{% else %}[{{ sec.name }}]({{ site.absoluteurl }}{{ site.baseurl }}{{ sec.url }}){% endif %}{% break %}{% endif %}{% endfor %}{% endfor %}
^
 - [Email Us](mailto:gdavis@teletekinc.com)
^
* * *
