---
layout: post
title: local storage
date: 2015-02-06T14:37:44.000Z
categories: update
---

<script type="text/javascript">
localStorage.lastname="Smith";
document.write(localStorage.lastname);
</script> 


<!--dan untuk melihat berapa kali user telah melihat web tersebut-->
<script type="text/javascript">
if (localStorage.pagecount)
  {
  localStorage.pagecount=Number(localStorage.pagecount) +1;
  }
else
  {
  localStorage.pagecount=1;
  }
document.write("Visits "+ localStorage.pagecount + " time(s).");
</script> 

