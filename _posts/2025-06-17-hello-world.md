<!--
 * @FileName: ${file_name}
 * @Description: 
 * @Author: hywelstar hywelstar@163.com
 * @Version: v0.0.1
 * @Date: 2025-06-17 22:56:13
 * @LastEditTime: 2025-06-17 23:22:58
 * Copyright 2025 HywelStar, All Rights Reserved. 
 * 2025-06-17 22:56:13
-->
---
title: Welcome to my Blog! 👋
date: 2025-06-17
tags: [blog, introduction, embedded, bilingual]
---

<style>
  .lang-content { display: none; }
  .lang-btn { margin-bottom: 1em; }
</style>

<div class="lang-btn">
  <button onclick="showLang('zh')">中文</button>
  <button onclick="showLang('en')">English</button>
</div>

<div id="lang-en" class="lang-content">

<h1>Welcome to HywelStar's Blog! 🚀</h1>

<p>😄 Hi everyone! I'm <strong>HywelStar</strong>. Thanks for stopping by my personal tech blog!</p>

<p>This is my first post — a short introduction about myself and what this blog is about.</p>
<p>I'll be sharing content related to embedded systems development, with insights from real-world projects and hands-on experience.</p>

<h2>🔭 About Me</h2>
<ul>
  <li>💻 Embedded Software Engineer</li>
  <li>👨‍💻 Skilled in <strong>Linux driver development</strong>, <strong>Android system customization</strong>, <strong>SoC bring-up and debugging</strong></li>
  <li>🎥 Familiar with multimedia processing, codecs, and streaming protocols</li>
  <li>🛠️ Passionate about technology sharing and side projects</li>
</ul>

<h2>🚀 Blog Topics</h2>
<ul>
  <li><strong>Embedded Software Development</strong>: Microcontroller firmware design</li>
  <li><strong>Linux Drivers</strong>: Platform driver development and optimization</li>
  <li><strong>Android Low-level Development</strong>: System-level customization and optimization</li>
  <li><strong>SoC Bring-Up</strong>: Bootloader, Driver, and board bring-up</li>
  <li><strong>Audio/Video Technologies</strong>: Codec handling, streaming, GStreamer</li>
</ul>

<h2>📚 Articles and Sharing</h2>
<ul>
  <li>✍️ Regular posts on embedded software and system design</li>
  <li>📂 Sample code and project demos on my GitHub repository</li>
  <li>📢 You can also follow my WeChat public account: <strong>码思途远</strong></li>
</ul>

<h2>📫 Get in Touch</h2>
<p>Interested in embedded systems, Linux development, or multimedia streaming?</p>
<p>Feel free to connect, comment, or share ideas — let’s explore tech together!</p>

<p>Thanks for visiting, and stay tuned for more content! 🚢</p>

</div>

<script>
  function showLang(lang) {
    document.querySelectorAll('.lang-content').forEach(el => el.style.display = 'none');
    document.getElementById('lang-' + lang).style.display = 'block';
  }
  document.addEventListener('DOMContentLoaded', () => showLang('zh'));
</script>


<div id="lang-zh" class="lang-content">

<h1>HywelStar's Blog 正式上线啦！🚀</h1>

<p>😄 Hi，大家好！我是 <strong>HywelStar</strong>，欢迎来到我的个人技术博客！</p>

<p>这是我博客的第一篇文章，主要用于简单介绍我自己和这个博客的方向。</p>
<p>在未来的日子里，我将持续分享我在嵌入式开发领域的一些学习、实践与思考。</p>

<h2>🔭 关于我</h2>
<ul>
  <li>💻 嵌入式软件工程师</li>
  <li>👨‍💻 擅长 <strong>Linux 驱动开发</strong>、<strong>Android 系统定制</strong>、<strong>SoC Bring-up 与调试</strong></li>
  <li>🎥 熟悉音视频处理、编解码与流媒体技术</li>
  <li>🛠️ 热衷技术分享与项目实战</li>
</ul>

<h2>🚀 博客内容方向</h2>
<ul>
  <li><strong>Embedded Software Development</strong>：微控制器系统设计与固件开发</li>
  <li><strong>Linux Drivers</strong>：平台驱动开发、调试与优化</li>
  <li><strong>Android Low-level Development</strong>：系统层裁剪与功能定制</li>
  <li><strong>SoC Bring-Up</strong>：Bootloader、驱动、新平台调试实践</li>
  <li><strong>Audio/Video Technologies</strong>：音视频编解码、GStreamer 流媒体处理</li>
</ul>

<h2>📚 关于更新与分享</h2>
<ul>
  <li>✍️ 定期更新嵌入式开发相关技术文章</li>
  <li>📂 项目源码与示例代码将同步更新至我的 GitHub 仓库</li>
  <li>📢 欢迎关注微信公众号：<strong>码思途远</strong></li>
</ul>

<h2>📫 联系方式</h2>
<p>如果你对嵌入式系统、Linux 驱动、音视频流媒体等内容感兴趣，欢迎留言交流，一起探索技术的乐趣！</p>
<p>感谢你的访问，博客启航，敬请期待更多内容！🚢</p>

</div>

