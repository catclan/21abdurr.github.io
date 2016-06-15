---
layout: post
title: local storage
date: 2015-02-06T14:37:44.000Z
categories: update
---

<<!DOCTYPE html>
<html>
<body>

if (sessionStorage.clickcount) {
    sessionStorage.clickcount = Number(sessionStorage.clickcount) + 1;
} else {
    sessionStorage.clickcount = 1;
}
document.getElementById("result").innerHTML = "You have clicked the button " +
sessionStorage.clickcount + " time(s) in this session.";
Try it Yourself »

</body>
</html>
