---
title: 朋友圈
layout: "friends"
description: 
date: 2022-08-18
---

<div class="post">
  <h2 class="post-title">{{.Title}}</h2>
  <div class="post-content">
    <!-- 挂载友链朋友圈的容器 -->
    <div id="cf-container">与主机通讯中……</div>
  </div>
</div>
<link rel="stylesheet" href="/fcircle-beta.css">
<script type="text/javascript" src='https://fastly.jsdelivr.net/npm/jquery@3/dist/jquery.min.js'></script>
<script type="text/javascript">
  var fdataUser = {
    jsonurl: 'https://cdn.edui.fun/lmm.json',  //【推荐】json 匹配模式
    // apiurl: 'https://hexo-circle-of-friends-lmm214.vercel.app/',  //自部署api
  }
</script>
<script type="text/javascript" src="/fcircle-beta.js"></script>

<style>.post:first-of-type{margin:0;padding-bottom: 0;}.content{margin-bottom: 0;}</style>

<script type="text/javascript" src="/theme-main-1.js"></script>
