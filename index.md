<!-- HEADER -->
<div id="header_wrap" class="outer">
    <header class="inner">
      <a id="forkme_banner" href="{{ site.github.repository_url }}">View on GitHub</a>
      <h1 id="project_title">{{ site.title | default: site.github.repository_name }}</h1>
      <h2 id="project_tagline">{{ site.description | default: site.github.project_tagline }}</h2>
      {% if site.show_downloads %}
        <section id="downloads">
            
            <p style="text-align: center; background-color: white;">
  <a href="{{site.baseurl}}/">Home</a> |
  <a href="{{site.baseurl}}/admin/">Admin</a> | 
  <a href="{{site.baseurl}}/schedule/week_1/">Week 1</a> | 
  <a href="{{site.baseurl}}/schedule/week_2/">Week 2</a> | 
  <a href="{{site.baseurl}}/schedule/week_3/">Week 3</a> | 
  <a href="{{site.baseurl}}/general/">Misc</a>
</p>
        </section>
      {% endif %}
      {% include nav.html %}
    </header>
</div>
