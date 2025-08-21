---
name: Postsecondary Education of Asians in the US
tools: [Power BI, HTML, Python]
image: assets/pngs/project.image.png
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# How is University life for Asians in the US?

As a rising senior, I understand the importance of having access to universities, and I'm looking forward to my undergraduate school life as well. Gradually growing up, I became increasingly curious about how university life would be like.
According to information presented to the public found in NCES and on the Internet, I investigated what university life would be like for Asians. 
In this little project, I collected data and other types of information, which include issues of financial aid, policy, and cultural differences.

# Dashboard


<!-- 按钮部分 -->
<div class="left">
   {% include elements/button.html link="{{ site.baseurl }}/assets/phd_clean.xlsx" text="The Data" %}
</div>

<div class="right">
   {% include elements/button.html link="{{ site.baseurl }}/assets/phd_clean.xlsx" text="The Analysis" %}
</div>

---

<!-- Power BI 报表嵌入 -->
<iframe title="phd form" width="1140" height="541.25" src="https://app.powerbigov.us/reportEmbed?reportId=0a705c93-20b8-4004-8915-06f1ace54e4f&autoAuth=true&ctid=8552887c-cbc3-4ee5-9fd3-ea217e3026fc" frameborder="0" allowFullScreen="true"></iframe>
