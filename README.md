# CYPLAN255_2024_finalproject
GitHub Page for CYPLAN 255 final project (Spring 2024)

#### People

The `_layouts/people.html` layout can be used to showcase and describe people in your research group. People are defined in the `_data/settings.yml` file, and markdown pages for each person with the `_layouts/page.html` layout can be placed in the `people` directory.

<div class="row g-5 mb-5">
  <div class="col-md-12">
    <h3 class="fw-bold border-bottom pb-3 mb-5">References</h3>
    {% for post in site.posts %}
      <p><a href="{{ site.github.url }}/{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %-d, %Y" }}</p>
    {% endfor %}
