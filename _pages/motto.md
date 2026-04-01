---
layout: page
title: Motto
permalink: /motto/
nav: true
nav_order: 6
---

<style>
  .motto-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 60vh;
    padding: 4rem 2rem;
    text-align: center;
  }
  .motto-zh {
    font-size: 1.8rem;
    font-weight: 300;
    line-height: 2.2;
    color: var(--global-text-color);
    max-width: 700px;
    letter-spacing: 0.08em;
    margin-bottom: 2.5rem;
    position: relative;
  }
  .motto-zh::before {
    content: "\201C";
    font-size: 6rem;
    color: var(--global-theme-color);
    opacity: 0.2;
    position: absolute;
    top: -2.5rem;
    left: -1.5rem;
    font-family: Georgia, serif;
    line-height: 1;
  }
  .motto-zh::after {
    content: "\201D";
    font-size: 6rem;
    color: var(--global-theme-color);
    opacity: 0.2;
    position: absolute;
    bottom: -4rem;
    right: -1.5rem;
    font-family: Georgia, serif;
    line-height: 1;
  }
  .motto-divider {
    width: 60px;
    height: 1px;
    background: var(--global-theme-color);
    opacity: 0.4;
    margin-bottom: 2rem;
  }
  .motto-en {
    font-size: 1.1rem;
    font-style: italic;
    color: var(--global-text-color-light);
    max-width: 580px;
    line-height: 1.8;
    letter-spacing: 0.02em;
  }
  .motto-author {
    margin-top: 1.5rem;
    font-size: 0.95rem;
    color: var(--global-text-color-light);
    font-weight: 500;
    letter-spacing: 0.05em;
  }
</style>

<div class="motto-container">
  <div class="motto-zh">
    世界上只有一种真正的英雄主义，<br>那就是在认清生活的真相后依然热爱生活。
  </div>
  <div class="motto-divider"></div>
  <div class="motto-en">
    "There is only one true heroism in the world: to see the world as it is, and to love it."
  </div>
  <div class="motto-author">— Romain Rolland</div>
</div>
