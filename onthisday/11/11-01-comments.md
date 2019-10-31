---
layout: page
title: On This Day - 1 November 1963
description:
categories: [On This Day]
utterances: false
---

<span id="age1"></span> years ago Lena Hilda Zavaroni was born in Rankin Memorial Hospital, Greenock, Inverclyde, Scotland, United Kingdom to Victor Zavaroni (1939) and Hilda Catherine (Jordan) Zavaroni (c1940-1989).

<!-- Script for calculating number of years ago -->
<script>
var dob = '19631102';
var year = Number(dob.substr(0, 4));
var month = Number(dob.substr(4, 2)) - 1;
var day = Number(dob.substr(6, 2));
var today = new Date();
var age1 = today.getFullYear() - year;
if (today.getMonth() < month || (today.getMonth() == month && today.getDate() < day)) {
age1--;
}
document.getElementById("age1").innerHTML=age1;
</script>
