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
  <a href="{{ site.baseurl }}/assets/phd_clean.xlsx" download 
     style="display:inline-block;padding:10px 20px;background:#0078D7;color:#fff;
            text-decoration:none;border-radius:5px;">
     Download The Data
  </a>
</div>



---


<!-- Power BI 报表嵌入 -->
<div style="position:relative; margin:0 auto; max-width:1200px; padding-top:56.25%;">
  <iframe 
    title="phd form"
    src="https://app.powerbigov.us/view?r=eyJrIjoiZGRkZTc2YzAtZTE2ZS00MWIyLTk5YTctNzFiODc5Y2U0ZmU3IiwidCI6Ijg1NTI4ODdjLWNiYzMtNGVlNS05ZmQzLWVhMjE3ZTMwMjZmYyJ9"
    style="position:absolute; top:0; left:0; width:100%; height:100%; border:0;"
    allowfullscreen="true">
  </iframe>
</div>
