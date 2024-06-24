---
layout: default
permalink: /
carousels:
  - images:
    - image: /images/barcode-readout.png
    - image: /images/lineages.png
    - image: /images/profile.jpeg
    - image: /images/dvc-infrastructure.png
---

![im](/images/profile.jpeg)

<div class="author__avatar">
    {% if author.avatar contains "://" %}
    	<img src="{{ author.avatar }}" alt="{{ author.name }}">
    {% else %}
    	<img src="{{ author.avatar | prepend: "/images/" | prepend: base_path }}" class="author__avatar" alt="{{ author.name }}">
    {% endif %}
</div>

<div class="author__avatar">
    <img src="{{base_path}}/images/{{ author.avatar }}" alt="{{ author.name }}">
</div>
<style>
author__avatar {
  display: table-cell;
  vertical-align: top;
  width: 36px;
  @include breakpoint($large) {
    display: block;
    width: auto;
    height: auto;
  }
  img {
    max-width: 175px;
    border-radius: 50%;
    @include breakpoint($large) {
      padding: 5px;
      border: 1px solid $border-color;
    }
  }
}
</style>