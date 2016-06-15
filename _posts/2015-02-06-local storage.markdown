---
layout: post
title: local storage
date: 2015-02-06T14:37:44.000Z
categories: update
---

<script type="text/javascript">
sessionStorage.lastname="abdur";
document.write(sessionStorage.lastname);
</script> 

<!--dan untuk melihat berapa kali user telah melihat web tersebut-->
<script type="text/javascript">
if (sessionStorage.pagecount)
  {
  sessionStorage.pagecount=Number(sessionStorage.pagecount) +1;
  }
else
  {
  sessionStorage.pagecount=1;
  }
document.write("Visits "+sessionStorage.pagecount+" time(s) this session.");
</script> 