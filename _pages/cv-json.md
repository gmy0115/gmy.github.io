---
layout: archive
title: "CV"
# permalink: /cv-json/
author_profile: false
redirect_from:
  - /resume-json
---

{% include base_path %}

<!-- <link rel="stylesheet" href="{{ base_path }}/assets/css/cv-style.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

<style>
  .archive {
    width: 80%;
    margin: 0 auto;
    float: none;
    padding-right: 0;
  }

  @media (min-width: 80em) {
    .archive {
      width: 70%;
    }
  }
</style>

{% include cv-template.html %}

<div class="cv-download-links">
  <a href="{{ base_path }}/files/resume_zh_CN.pdf" class="btn btn--primary">Download CV as PDF</a>
  <a href="{{ base_path }}" class="btn btn--inverse">View Markdown CV</a>
</div> -->

<style>
  .archive {
    width: 100%;
    margin: 0 auto;
    float: none;
    padding-right: 0;
  }

  @media (min-width: 80em) {
    .archive {
      width: 100%;
    }
  }

  /* PDF显示样式 */
  .pdf-container {
    width: 100%;
    height: 800px;
    border: none;
    margin: 20px 0;
  }

  .pdf-fallback {
    text-align: center;
    padding: 40px;
    background-color: #f8f9fa;
    border: 2px dashed #dee2e6;
    border-radius: 8px;
    margin: 20px 0;
  }

  .pdf-fallback a {
    color: #007bff;
    text-decoration: none;
    font-weight: bold;
  }

  .pdf-fallback a:hover {
    text-decoration: underline;
  }
</style>

<!-- 直接显示PDF文件 -->
<div class="pdf-container">
  <object data="{{ base_path }}/files/resume_zh_CN.pdf" type="application/pdf" class="pdf-container">
    <div class="pdf-fallback">
      <p>您的浏览器不支持直接显示PDF文件。</p>
      <p><a href="{{ base_path }}/files/resume_zh_CN.pdf" target="_blank">点击这里下载或在新窗口中打开PDF文件</a></p>
    </div>
  </object>
</div>
