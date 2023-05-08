---
title: 市區行程
layout: page
permalink: "/about/"
animals: 
  - name: kiwi1
    value: 1
  - name: Tui1
    value: 2 
  - name: Tui2
    value: 2 
  - name: Tui3
    value: 2 
  - name: kiwi2
    value: 1
  - name: Tui4
    value: 2 
  - name: kiwi3
    value: 1 
---

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

You can find the source code for Minima at GitHub:
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll


$$x^2+y^2=1$$

>花椒粉、鹽、黑胡椒粉

>小米椒、糖、生抽、檸檬汁、魚露、蒜末...調汁

>淋上調汁，撒上香菜即可上菜

```
let message = 'Hello world';
alert(message);
```


<style>
    .row>div {
        background: #ccc;
        }

    .row>div>div {
        background: salmon;
    }
</style>

<div class="container">
    <div class="row">
        <div class="col-md-6"><div>col-md-6</div></div>
        <div class="col-md-6"><div> col-md-6</div></div>
    </div>
    
</div>

{% for i in (1..2) %}
{% for animal in page.animals %}
{% if animal.value==i %}
{{animal.name}}
{% endif %}
{% endfor %}
{% endfor %}
