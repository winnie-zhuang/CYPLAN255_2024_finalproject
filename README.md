Test



<div class="row g-5 mb-5">
  <div class="col-md-12">
    <h3 class="fw-bold border-bottom pb-3 mb-5">References</h3>
    {% for post in site.posts %}
      <p><a href="{{ site.github.url }}/{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %-d, %Y" }}</p>
    {% endfor %}
