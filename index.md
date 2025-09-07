---
---

<!-- 顶部 hero 区域 -->
<div class="hero-section" style="text-align:center; padding:60px 20px; 
     background:#f8f9fa; border-radius:16px; box-shadow:0 10px 30px rgba(0,0,0,0.05);">

  <!-- 大标题 -->
  <h1 style="font-size:3em; font-weight:900; margin-bottom:20px; color:#222;">
    山东理工大学 <span style="color:#4facfe;">Vinci机器人队</span>
  </h1>

  <!-- 副标题卡片 -->
  <div style="display:inline-block; background:#ffffff; 
       padding:20px 30px; border-radius:12px; box-shadow:0 6px 20px rgba(0,0,0,0.08); 
       max-width:700px; font-size:1.2em; line-height:1.6em; color:#333;">
    山东理工大学Robocon团队（Vinci机器人队、机电创新学会）是山东理工大学创新团队之一。  
    以参加全国大学生机器人大赛Robocon为核心，其余竞赛为辅，旨在培养队员的综合能力。
  </div>

  <!-- 按钮组 -->
  <div class="hero-buttons" style="margin-top:30px; display:flex; justify-content:center; flex-wrap:wrap; gap:15px;">
    {% include button.html type="docs" text="Bilibili" icon="fa-brands fa-bilibili" link="https://space.bilibili.com/471524675" style="gradient" %}
    {% include button.html type="github" text="GitHub" link="https://github.com/SDUTVINCI" style="gradient" %}
    {% include button.html type="docs" text="微信公众号" icon="fa-brands fa-weixin" link="https://mp.weixin.qq.com/s/AAPWX2zOhJjA-s2MA-g2Ew" style="gradient" %}
    {% include button.html type="docs" text="2025迎新QQ群" icon="fa-brands fa-qq" link="https://qm.qq.com/q/heOyGXc35e" style="gradient" %}
    {% include button.html type="docs" text="加入我们-25级新队员招募" icon="fa-solid fa-user-plus" link="recruitment" style="gradient" %}
  </div>

</div>



{% include section.html %}

<!-- 大标题样式示例 -->
<h2 class="section-title"><i class="fa-solid fa-lightbulb"></i> 纳新专区</h2>

{% capture text %}
<div class="feature-card" style="padding:20px; border-radius:12px; box-shadow:0 6px 20px rgba(0,0,0,0.08); background:#fff; transition:all 0.3s;">
<h3 class="feature-title"><i class="fa-solid fa-user-plus"></i> 加入我们</h3>
<p style="font-size:1.1em; line-height:1.6em;">如果你热爱机器人、编程、机械设计，或者只是想和一群志同道合的小伙伴一起做点有趣的事，Vinci机器人队欢迎你！</p>
<p style="font-size:1.1em; line-height:1.6em;">在这里，你能接触前沿机器人技术，参与各类赛事与项目，并与优秀的伙伴们共同成长。</p>
<p style="font-size:1.1em; line-height:1.6em;">不论你是新手还是有经验的开发者，都能在这里找到属于自己的位置。</p>
<div style="margin-top:15px;">
  {% include button.html link="recruitment" text="点击了解更多资讯" icon="fa-solid fa-arrow-right" flip=true style="bare" %}
</div>
</div>
{% endcapture %}

{% include feature.html image="images/joinus.jpg" link="recruitment" title="" flip=true style="bare" text=text %}


<h2 class="section-title"><i class="fa-solid fa-star"></i> 高光时刻</h2>

{% capture text %}
<div class="feature-card" style="padding:20px; border-radius:12px; box-shadow:0 6px 20px rgba(0,0,0,0.08); background:#fff;">
<h3 class="feature-title"><i class="fa-solid fa-trophy"></i> 我们的成果</h3>
<ul style="list-style:none; padding-left:0; line-height:1.8em;">
  <li>🏆 2016年：全国大学生机器人大赛Robocon省赛一等奖，国赛二等奖</li>
  <li>🏆 2017年：全国大学生机器人大赛Robocon国赛三等奖；全国大学生机器人大赛RoboMaster国赛三等奖</li>
  <li>🏆 2018年：全国大学生机器人大赛Robocon省赛一等奖，国赛一等奖；同年获感动校园</li>
  <li>🏆 2019年：全国大学生机器人大赛Robocon省赛一等奖，国赛二等奖</li>
  <li>🏆 2020年：全国大学生机器人大赛Robocon省赛一等奖，国赛二等奖</li>
  <li>🏆 2021年：全国大学生机器人大赛Robocon省赛一等奖，国赛二等奖</li>
  <li>🏆 2022年：全国大学生机器人大赛Robocon省赛一等奖，国赛二等奖</li>
  <li>🏆 2023年：全国大学生机器人大赛Robocon正赛国赛三等奖，马术赛国赛三等奖</li>
  <li>🏆 2024年：全国大学生机器人大赛Robocon正赛国赛三等奖，技能赛国赛二等奖，马术赛国赛三等奖</li>
  <li>🏆 2025年：全国大学生机器人大赛Robocon正赛国赛三等奖，技能赛国赛二等奖，马术赛国赛二等奖，排球赛国赛二等奖</li>
</ul>
<div style="margin-top:15px;">
  {% include button.html link="research" text="我们的更多成果" icon="fa-solid fa-arrow-right" flip=true style="bare" %}
</div>
</div>
{% endcapture %}

{% include feature.html image="images/cheer.png" link="research" title="" flip=true style="bare" text=text %}


<h2 class="section-title"><i class="fa-solid fa-gear"></i> 我们的项目</h2>

{% capture text %}
<div class="feature-card" style="padding:20px; border-radius:12px; box-shadow:0 6px 20px rgba(0,0,0,0.08); background:#fff;">
<h3 class="feature-title"><i class="fa-solid fa-rocket"></i> 项目展示</h3>
<p style="font-size:1.1em; line-height:1.6em;">作为一个多学科交叉的机器人团队，我们与企业、学校等多方面展开合作，推动科技创新与人才培养。</p>
<div style="margin-top:15px;">
  {% include button.html link="projects" text="我们的所有项目" icon="fa-solid fa-arrow-right" flip=true style="bare" %}
</div>
</div>
{% endcapture %}

{% include feature.html image="images/cooporate.jpg" link="projects" title="" flip=true style="bare" text=text %}


<h2 class="section-title"><i class="fa-solid fa-users"></i> 我们的成员</h2>

{% capture text %}
<div class="feature-card" style="padding:20px; border-radius:12px; box-shadow:0 6px 20px rgba(0,0,0,0.08); background:#fff;">
<h3 class="feature-title"><i class="fa-solid fa-id-badge"></i> 团队介绍</h3>
<p style="font-size:1.1em; line-height:1.6em;">这里聚集了机械、电路、嵌软、算法、运营多方面的人才。</p>
<div style="margin-top:15px;">
  {% include button.html link="team" text="我们的所有成员" icon="fa-solid fa-arrow-right" flip=true style="bare" %}
</div>
</div>
{% endcapture %}

{% include feature.html image="images/background_footer.png" link="team" title="" text=text %}


<h2 class="section-title"><i class="fa-solid fa-newspaper"></i> 我们的新闻</h2>

{% capture text %}
<div class="feature-card" style="padding:20px; border-radius:12px; box-shadow:0 6px 20px rgba(0,0,0,0.08); background:#fff;">
<h3 class="feature-title"><i class="fa-solid fa-bullhorn"></i> 最新动态</h3>
<p style="font-size:1.1em; line-height:1.6em;">我们活跃于各种社会活动，积极展现芬奇风采。</p>
<div style="margin-top:15px;">
  {% include button.html link="news" text="我们的最近动态" icon="fa-solid fa-arrow-right" flip=true style="bare" %}
</div>
</div>
{% endcapture %}

{% include feature.html image="images/news.png" link="news" title="" flip=true style="bare" text=text %}
