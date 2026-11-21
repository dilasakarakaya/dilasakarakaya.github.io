---
layout: page
permalink: /teaching/
title: Teaching
description: Course materials, schedules, and resources for classes taught.
nav: true
nav_order: 6
calendar: true
---

<style>
  :root {
    --global-theme-color: #6d2348 !important;
    --global-hover-color: #6d2348 !important;
  }
  html[data-theme="dark"] {
    --global-theme-color: #e0a3c4 !important;
    --global-hover-color: #e0a3c4 !important;
  }

    #search-toggle .nav-link {
    font-size: 0 !important;
  }
  #search-toggle .nav-link i {
    font-size: 1rem !important;
  }
</style>

This page displays a collection of courses with detailed schedules, materials, and resources. You can organize your courses by years, terms, or topics.

{% include calendar.liquid calendar_id='test@gmail.com' timezone='Asia/Shanghai' %}

{% include courses.liquid %}
