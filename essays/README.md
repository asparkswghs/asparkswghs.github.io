# Essays

A bunch of essays I've written for school. 

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.

# List of Essays

{% assign doclist = site.pages | sort: 'url'  %}
    <ul>
       {% for doc in doclist %}
            {% if doc.name contains '.md' or doc.name contains '.html' %}
                <li><a href="{{ site.baseurl }}{{ doc.url }}">{{ doc.url }}</a></li>
            {% endif %}
        {% endfor %}
    </ul>



