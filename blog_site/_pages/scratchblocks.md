---
title:  "Scratchblocks"
permalink: /scratchblocks/
---

# 出力例

{% scratchblocks { style: "scratch3", languages: ["en", "ja", "ja_Hira"] } %}
  @greenFlag が押されたとき
  x座標を (0) 、y座標を (0) にする
  ずっと
    (10)回繰り返す
      @turnright (10) 度回す
      (5) 歩動かす
    end
    次のコスチュームにする
  end
{% endscratchblocks %}


# マークダウン表記

{% raw %}
```html
{% scratchblocks { style: "scratch3", languages: ["en", "ja", "ja_Hira"] } %}
  @greenFlag が押されたとき
  x座標を (0) 、y座標を (0) にする
  ずっと
    (10)回繰り返す
      @turnright (10) 度回す
      (5) 歩動かす
    end
    次のコスチュームにする
  end
{% endscratchblocks %}
```
{% endraw %}


# リンク

- [https://github.com/scratchblocks/scratchblocks](https://github.com/scratchblocks/scratchblocks)
- [https://scratchblocks.github.io/](https://scratchblocks.github.io/#?style=scratch3&script=)
- [https://ja.scratch-wiki.info/wiki/ブロックプラグイン_(3.0)](https://ja.scratch-wiki.info/wiki/%E3%83%96%E3%83%AD%E3%83%83%E3%82%AF%E3%83%97%E3%83%A9%E3%82%B0%E3%82%A4%E3%83%B3_(3.0))
- [https://github.com/jp-rad/jekyll-scratchblocks](https://github.com/jp-rad/jekyll-scratchblocks)
