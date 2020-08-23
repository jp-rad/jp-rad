---
title:  "PlantUML"
permalink: /plantuml/
---

# マークダウン表記

{% raw %}
```
<div class="fitvidsignore"  markdown="1">
{% plantuml %}
Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response

Alice -> Bob: Another authentication Request
Alice <-- Bob: another authentication Response
{% endplantuml %}
</div>
```
{% endraw %}


# 出力例

<div class="fitvidsignore"  markdown="1">
{% plantuml %}
Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response

Alice -> Bob: Another authentication Request
Alice <-- Bob: another authentication Response
{% endplantuml %}
</div>

# リンク

- https://plantuml.com/
- https://github.com/yegor256/jekyll-plantuml
