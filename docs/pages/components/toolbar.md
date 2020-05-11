---
title: Toolbar
id: toolbar
keywords: toolbar
sidebar: left-navigation-sidebar
toc: false
permalink: components/toolbar.html
folder: components
summary:
---
Toolbar
{: .docs-intro}


{% capture toolbar %}

<div dir="rtl">
  <h2>RTL mode - auto</h2>
  <div class="fd-toolbar fd-toolbar--clear fd-toolbar--active fd-toolbar--clear fd-toolbar--auto">
    <button class="fd-button fd-button--compact">Button</button>
    <button class="fd-button fd-button--compact">Button</button>
    <span class="fd-toolbar__spacer fd-toolbar__spacer--auto"> </span>
    <button class="fd-button fd-button--compact">Button</button>
    <button class="fd-button fd-button--compact">Button</button>
    <span class="fd-toolbar__separator"></span>
    <button class="fd-button fd-button--compact">Button</button>
    <span class="fd-toolbar__spacer fd-toolbar__spacer--auto"> </span>
    <button class="fd-button fd-button--compact">Button</button>
  </div>
</div>

<div dir="ltr">
  <h2>LTR mode - transparent</h2>
  <div class="fd-toolbar fd-toolbar--standard fd-toolbar--active fd-toolbar--transparent">
    <button class="fd-button fd-button--compact">Button</button>
    <button class="fd-button fd-button--compact">Button</button>
    <span class="fd-toolbar__spacer fd-toolbar__spacer--auto"> </span>
    <button class="fd-button fd-button--compact">Button</button>
    <button class="fd-button fd-button--compact">Button</button>
    <span class="fd-toolbar__separator"></span>
    <button class="fd-button fd-button--compact">Button</button>
    <span class="fd-toolbar__spacer fd-toolbar__spacer--auto"> </span>
    <button class="fd-button fd-button--compact">Button</button>
  </div>
</div>

<div dir="rtl">
  <h2>RTL mode - solid, standard</h2>
  <div class="fd-toolbar fd-toolbar--active fd-toolbar--solid">
    <button class="fd-button fd-button--compact">Button</button>
    <button class="fd-button fd-button--compact">Button</button>
    <span class="fd-toolbar__spacer fd-toolbar__spacer--auto"> </span>
    <button class="fd-button fd-button--compact">Button</button>
    <button class="fd-button fd-button--compact">Button</button>
    <span class="fd-toolbar__separator"></span>
    <button class="fd-button fd-button--compact">Button</button>
    <span class="fd-toolbar__spacer fd-toolbar__spacer--auto"> </span>
    <button class="fd-button fd-button--compact">Button</button>
  </div>
</div>

<div dir="ltr">
  <h2>LTR mode - info</h2>
  <div class="fd-toolbar fd-toolbar--active fd-toolbar--info">
    3 item selected
  </div>
</div>


{% endcapture %}
{% include display-component.html component=toolbar %}