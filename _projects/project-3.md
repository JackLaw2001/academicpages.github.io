---
title: "The User Demographics in Dating Platforms"
excerpt: "Completed in 2023<br/><img src='/images/r24.png' width='600'>"
collection: projects
---

**Backgroud**: There is a WeChat public account that has posted a lot of blind date posts. These posts contain a lot of user information, such as gender, occupation, income, etc. However, it is not easy to retrieve this data. Firstly, these texts are in images that are not copyable. Secondly, thse images are uploaded by different users and they are in different styles. Thirdly, their structure varies a lot since there is no unified format.

**Description**:
Images were obtained by Web crawler. OCR technique is used to extract texts. Before OCR, I used the *Opencv* package in python to enhance these images to make them more readable (increase contrast, etc.). The texts extracted were not structured and I used *Text Information Extraction* API in the Baidu AI cloud to extract information. Basically, I will provide a list of the information I am interested in, such as gender, income, etc. AI models will be used to find the corresponding answers and write them into a table. Finally, I can perform data analysis from the extracted information.

<div align=center>
<table><tr>
<td><img src="/images/r21.jpg"></td>
<td><img src="/images/r22.jpg" ></td>
</tr></table>
</div>
<div align=center><img src="/images/r23.png"></div>
<div align=center>
<table><tr>
<td><img src="/images/r25.png"></td>
<td><img src="/images/r26.png"></td>
<td><img src="/images/r27.png"></td>
</tr></table>
<!-- <div align=center>
<table><tr>
<td><img src="/images/heat2.jpg"></td>
<td><img src="/images/heat3.jpg" ></td>
</tr></table>
</div> -->





