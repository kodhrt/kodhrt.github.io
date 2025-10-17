---
layout: single
title: "Yuma Oe"
date: 2025-10-03
permalink: /
header:
  overlay_image: "./assets/img/others/profile_header.jpg"
  overlay_filter: 0.5
  overlay_color: "#000"
#   actions:
#     - label: "ここがリンク"
#       url: https://qiita.com/
#       class: "btn--primary"
author_profile: true # これを追加
description: "本Webサイトでは、静岡大学大学院 総合科学技術研究科の大江 優真（Yuma Oe）に関する情報をまとめています。"
---

# About me
静岡大学大学院 総合科学技術研究科情報学専攻修士1年の大江 優真（おおえ ゆうま）です。ファッションに関する情報アクセス技術の研究をしています。趣味は服のリメイク、喫茶店探し、ひとり旅です。  

# About this site
本Webサイトは、自身のスキルや成果物をまとめるために作成されたものです。  
本Webサイトは静的サイトジェネレーター「[Jekyll](https://jekyllrb-ja.github.io/){:target="_blank"}」で作成されています。

# Related sites
- [所属研究室 公式Webサイト](https://shoji-lab.github.io/){:target="_blank"}  
- [Google Scholar](https://scholar.google.co.jp/citations?user=09eKYaIAAAAJ&hl=ja){:target="_blank"}  
- [Consese（旧Scrapbox）](https://scrapbox.io/shoji-lab-survey/Yuma_Oe){:target="_blank"}

# Latest news
<div class="news-list">
  {% assign count = 0 %}
  {% for post in site.posts %}
    {% if count < 3 %}
      {% if post.popopo contains 'news' %}
        <article class="news-post">
          <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
          <time datetime="{{ post.date | date: '%Y-%m-%d' }}">
            {{ post.date | date: '%Y年%m月%d日' }}
          </time>
          <!-- <p>{{ post.excerpt }}</p> -->
        </article>
        {% assign count = count | plus: 1 %}
      {% endif %}
    {% else %}
      {% break %}
    {% endif %}
  {% endfor %}
</div>
過去の記事は[こちら](https://kodhrt.github.io/news/)。

# Contact
メールアドレス：oe.yuma.21（a）shizuoka.ac.jp  
※（a）を@に変更してください。  
