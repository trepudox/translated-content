---
title: homepage_url
slug: Mozilla/Add-ons/WebExtensions/manifest.json/homepage_url
tags:
  - 擴充套件
translation_of: Mozilla/Add-ons/WebExtensions/manifest.json/homepage_url
---
<div>
<div>{{AddonSidebar}}</div>

<table class="fullwidth-table standard-table">
 <tbody>
  <tr>
   <th scope="row">型別</th>
   <td><code>String</code></td>
  </tr>
  <tr>
   <th scope="row">強制</th>
   <td>No</td>
  </tr>
  <tr>
   <th scope="row">範例</th>
   <td>
    <pre class="brush: json">"homepage_url": "https://example.org/my-addon"</pre>
   </td>
  </tr>
 </tbody>
</table>

<p>套件首頁的URL。</p>

<p>如果有 <a href="/en-US/Add-ons/WebExtensions/manifest.json/developer">developer</a> 鍵且它包含 "url" 屬性，這會覆蓋 homepage_url 鍵。</p>

<p>這是一個<a href="/en-US/Add-ons/WebExtensions/Internationalization#Internationalizing_manifest.json">可侷限的屬性</a>。</p>

<h2 id="範例">範例</h2>

<pre class="brush: json">"homepage_url": "https://github.com/mdn/webextensions-examples/tree/master/beastify"</pre>

<h2 id="瀏覽器兼容性">瀏覽器兼容性</h2>
</div>

<p>{{Compat("webextensions.manifest.homepage_url")}}</p>