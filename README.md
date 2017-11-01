![yassir]({{ site.url }}/assets/yassir.jpg)

{% for image in site.static_files %}
    {% if image.path contains 'assets/slider' %}
        ![yassir]({{ site.baseurl }}{{ image.path }})
    {% endif %}
{% endfor %}
