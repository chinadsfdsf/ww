---
weight: 11
bookCollapseSection: false
title: "timezone 时区表"
---


<script>
var TTTmyVar = setInterval(TTTmyTimer, 2700);
function TTTmyTimer() {

    var TTTdynTime00 = new Date();


    document.getElementById('TTTdynTime_0').innerHTML =
        TTTdynTime00.toLocaleString("en-US", {timeZone:"Asia/Hong_Kong"});

    document.getElementById('TTTdynTime_1').innerHTML =
        TTTdynTime00.toLocaleString("en-US", {timeZone:"America/Los_Angeles"});

    document.getElementById('TTTdynTime_2').innerHTML =
        TTTdynTime00.toLocaleString("en-US", {timeZone:"America/New_York"});

    document.getElementById('TTTdynTime_3').innerHTML =
        TTTdynTime00.toLocaleString("en-US", {timeZone:"Australia/Sydney"});

    document.getElementById('TTTdynTime_4').innerHTML =
        TTTdynTime00.toLocaleString("en-US", {timeZone:"Europe/London"});

    document.getElementById('TTTdynTime_5').innerHTML =
        TTTdynTime00.toLocaleString("en-US", {timeZone:"Japan"});

    document.getElementById('TTTdynTime_6').innerHTML =
        TTTdynTime00.toLocaleString("en-US", {timeZone:"Europe/Paris"});

    document.getElementById('TTTdynTime_7').innerHTML =
        TTTdynTime00.toLocaleString("en-US", {timeZone:"Africa/Nairobi"});


}
</script>

<style>
td , th {
padding:1px;
}
</style>


<table style="width:140%;" >
<tr>
<th style="padding:1px;">idx</th>
<th style="padding:1px;">Name</th>
<th style="padding:1px;">TimeZone</th>
<th style="padding:1px;">city</th>
<th style="padding:1px;">decription</th>
<th style="padding:1px;">Name2</th>
<th style="padding:1px;">localTime(now)</th>
</tr>
<tr>

<td style="padding:1px;"> 0 </td>
<td style="padding:1px;">HK</td>
<td style="padding:1px;">Asia/Hong_Kong</td>
<td style="padding:1px;">Hongkong</td>
<td style="padding:1px;">UTC&#43;8 </td>
<td style="padding:1px;"> 香港</td>

<td style="padding:1px;"> <a id="TTTdynTime_0"> </a> </td>
</tr>
<tr>

<td style="padding:1px;"> 1 </td>
<td style="padding:1px;">PDT</td>
<td style="padding:1px;">America/Los_Angeles</td>
<td style="padding:1px;">SanFrancisco(USA)</td>
<td style="padding:1px;">UTC-8/UTC-7 </td>
<td style="padding:1px;"> 美国三藩市 西岸</td>

<td style="padding:1px;"> <a id="TTTdynTime_1"> </a> </td>

</tr>
<tr  style="background: #ebe0e0">

<td style="padding:1px;"> 2 </td>
<td style="padding:1px;">EDT</td>
<td style="padding:1px;">America/New_York</td>
<td style="padding:1px;">Washington_DC(USA)</td>
<td style="padding:1px;">UTC-5/UTC-4 </td>
<td style="padding:1px;"> 美国首都DC 東岸</td>

<td style="padding:1px;"> <a id="TTTdynTime_2"> </a> </td>

</tr>
<tr>

<td style="padding:1px;"> 3 </td>
<td style="padding:1px;">AEDT</td>
<td style="padding:1px;">Australia/Sydney</td>
<td style="padding:1px;">Sydney(Australia)</td>
<td style="padding:1px;">UTC&#43;11 </td>
<td style="padding:1px;">澳洲    悉尼</td>

<td style="padding:1px;"> <a id="TTTdynTime_3"> </a> </td>

</tr>
<tr>

<td style="padding:1px;"> 4 </td>
<td style="padding:1px;">GMT</td>
<td style="padding:1px;">Europe/London</td>
<td style="padding:1px;">London(UK)</td>
<td style="padding:1px;">UTC&#43;0 </td>
<td style="padding:1px;">英国    伦敦</td>

<td style="padding:1px;"> <a id="TTTdynTime_4"> </a> </td>
</tr>
<tr  style="background: #ebe0e0">

<td style="padding:1px;"> 5 </td>
<td style="padding:1px;">JCT</td>
<td style="padding:1px;">Japan</td>
<td style="padding:1px;">Japan</td>
<td style="padding:1px;">UTC&#43;9 </td>
<td style="padding:1px;">日本</td>

<td style="padding:1px;"> <a id="TTTdynTime_5"> </a> </td>
</tr>
<tr>

<td style="padding:1px;"> 6 </td>
<td style="padding:1px;">CET</td>
<td style="padding:1px;">Europe/Paris</td>
<td style="padding:1px;">Paris(France)</td>
<td style="padding:1px;">UTC&#43;1 </td>
<td style="padding:1px;">法国    巴黎</td>

<td style="padding:1px;"> <a id="TTTdynTime_6"> </a> </td>
</tr>
<tr>

<td style="padding:1px;"> 7 </td>
<td style="padding:1px;">TZS</td>
<td style="padding:1px;">Africa/Nairobi</td>
<td style="padding:1px;">Tanzanian</td>
<td style="padding:1px;">UTC&#43;3 </td>
<td style="padding:1px;">坦桑尼亚</td>

<td style="padding:1px;"> <a id="TTTdynTime_7"> </a> </td>
</tr>
</table>

