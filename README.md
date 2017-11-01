![yassir]({{ site.url }}/assets/yassir.jpg)

{% for image in site.static_files %}
    {% if image.path contains 'assets/slider' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}
