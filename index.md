---
layout: default
title: Home
---
# BackMeUp.net
### Foolproof 3-2-1 backups made easy

#### What is **3-2-1** backup?
![3-2-1 Graphic](images/321GraphicNoTitle.svg)

## Quick Start
#### What devices do you want to back up?
##### Select all that apply

<div class="selection-card-container">
{% for item in site.data.devices.devices %}
<div class="selection-card">
    <img src="{{ item.icon }}" alt="{{ item.title }} icon">
    {{ item.title }}
</div>
{% endfor %}
</div>