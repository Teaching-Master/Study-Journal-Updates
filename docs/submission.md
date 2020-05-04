---
layout: tabbed-assignment
---

# Submission Instructions

At the end of the week:

1. Make sure your journal is up to date.
1. Click on the share button.
1. Copy the link. 
1. Submit the link through Canvas.

{% include submission-boilerplate.html %}

<!-- Don't edit links here, change them in _data/assignment.yml instead, -->

{% if site.data.assignment.lesson   %}[lesson]: <{{site.data.assignment.lesson}}>     {% endif %}
{% if site.data.assignment.slides   %}[slides]:   <{{site.data.assignment.slides}}>   {% endif %}
{% if site.data.assignment.template %}[template]: <{{site.data.assignment.template}}> {% endif %}
{% if site.data.assignment.template %}[copy-template]: <{{site.data.assignment.template}}/copy> {% endif %}
