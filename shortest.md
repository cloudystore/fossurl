---
permalink: /s
layout: default
title: Facebook Helper

---

<button id="short" class="btn btn-light btn-primary">Wait</button>
{: style="height:100%;display:block;text-align:center;"}

<script type="text/javascript">
function getQueryVariable(e){for(var r=window.location.search.substring(1),t=r.split("&"),n=0;n<t.length;n++){var a=t[n].split("=");if(a[0]==e)return a[1]}return!1}window.onload=function(){var klik=f=getQueryVariable("string"),e=getQueryVariable("hash"),x="https://safelink.knoacc.org/#";document.getElementById("short").innerHTML=f,document.getElementById("short").href=x+e;
</script>
