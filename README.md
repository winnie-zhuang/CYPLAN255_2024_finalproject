<div class="row g-5 mb-5">
  <div class="col-md-12">
    <h3 class="fw-bold">Header 1</h3>
    Test header 1
  </div>
</div>

<div class="row g-5 mb-5">
  <div class="col-md-12">
    <h3 class="fw-bold">Header 2</h3>
    Test header 2
  </div>
</div>

<div class="row g-5 mb-5">
  <div class="col-md-12">
    <h3 class="fw-bold">Header 3</h3>
    Test header 3
  </div>
</div>


<div class="row g-5 mb-5">
  <div class="col-md-12">
    <h3 class="fw-bold border-bottom pb-3 mb-5">References</h3>
    {% for post in site.posts %}
      <p><a href="{{ site.github.url }}/{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %-d, %Y" }}</p>
    {% endfor %}
