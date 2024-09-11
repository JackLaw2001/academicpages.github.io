---
title: "Geographic visualization of user IP data in a WeChat mini-program"
excerpt: "Completed during my freshman year, 2020<br/><img src='/images/heat1.jpg'>"
collection: projects
---

**Backgroud**: During the coronavirus, most Chinese students were not allowed to return back to university and had to take online class. They all had to use a WeChat mini-program called "Youth Learning" (青年大学习). In order to count students' attendance, a form with student check-in records and corresponding IP addresses was sent to a WeChat group. 

**Description**:
IP geolocation can usually be accurate down to the city level. However, I learned that some IP addresses may be more likely to be assigned to specific neighborhoods. Amap is a widely used navigation app in China. This app has recorded a large amount of user IPs along with their corresponding precise locations. Through the API provided by this platform, I obtained a large number of addresses. Since students were staying home during the pandemic, these addresses are likely their home addresses.   
I used python and related packages to obtain the students' home addresses and conducted analysis. I plotted these addresses into a heat map.

<div align=center>
<table><tr>
<td><img src="/images/heat0.jpg"></td>
<td><img src="/images/heat1.jpg" ></td>
</tr></table>
</div>
<div align=center>
<table><tr>
<td><img src="/images/heat2.jpg"></td>
<td><img src="/images/heat3.jpg" ></td>
</tr></table>
</div>





