# Essays

A some essays I've written for school. 

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.

# List of Essays


{% assign doclist = site.static_files | sort: 'url'  -%}
{%- for doc in doclist -%}
   {%- unless doc.name contains '[hide]' or doc.name contains 'README' -%}
      {%- if doc.path contains '/essays/' %}
            
   * [{{ doc.name }}]({{ doc.path }})
      {% endif -%}
   {%- endunless -%}
{%- endfor -%}



