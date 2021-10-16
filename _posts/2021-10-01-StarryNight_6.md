---
layout: post
title: "[Starry Night] SPUS (Site Photo Upload System) : 현장 사진 중앙 관리 및 DB"
author: StarryNgiht_CAS
date: 2021-10-01 00:00:00 +09:00
tags: [osk15, shjo01, yskim, StarryNight]
image: /files/2_StarryNight/Post/Posthead_4.png
discription: "SPUS(Site Photo Upload System)을 개발하였습니다. 실제로 현장 FE나 공사경험을 수행하면서 개인장비로 촬영하였던 현장 사진들이 파편화되어 관리되고, 나중에 사진 관련 정보들을 열람할 때 어떤 사진이었는지 알기 어려운 부분이 있었기에 그런 부분들을 편리하게 DB화 해서 그 Data들을 취합/관리할 수 있는 시스템을 개발하고자 하였습니다. 개인 스마트폰에서 현장사진을 촬영을 하면서 함께 촬영한 사진의 정보를 기입하면, SharePoint에 그 Data들이 업로드가 되고, 나중에 App을 통해서 열람/수정/메일발송 할 수 있고, 추가로 작업일보로 Publishing해서 여러 사람들에게 공유도 해주는 확장성도 있는 App입니다."
---


# 팀명 : 환경솔루션

> **소속 : G.E본부 / CAS설계팀 3명**

![](/files/2_StarryNight/Post/6/2_6_pic_T.jpg)

----------------------------------------------------------------------------------------

# 팀원

<center><img src="/files/2_StarryNight/Post/6/05-0.jpg" style="width:120px; height:120px; border-radius:50%; border: 1px solid #ccc; margin-bottom: 5px;"></center>
##### <center>온슬기 (osk15)</center>

>엔지니어링 Data base에 있어서 설계 도면이나 도서 뿐만 현장 사진이 매우 중요하다고 평소 생각했습니다. 글이나 말로 표현하는 것보다 더 큰 효과를 줄 수 있는게 바로 이미지인데, 개인PC에서  관리하고 있었던 사진들에 여러가지 정보를 넣어 가상공간에서 관리할 수 있고, 누구가 쉽게 접근할 수 있으면 얼마나 편리할까? 라는 생각에 답을 제공해 줄 수 있는 SPUS!~  개발 과정에서 Power Apps 코딩이 생각처럼 쉽게 되지 않아 계속해서 고민하고, 업로드 한 사진 이미지가 제대로 뜨지 않아 좌절했던 시간을 돌이켜 보면 무언가를 개발한다는 게 얼마나 많은 노력과 시간이 필요한 것인지 몸소 느낄 수 있었습니다. 그리고 이번에 경험한 Power Platform 이 앞으로 우리의 업무 방식을 바꾸어 줄 수 있다는 기대감을 갖게 되었습니다. 끝으로 너무나도 수고해 준 우리 팀원 김윤성 전임, 조성환 전임에게 감사의 인사를 전합니다^^

<br><br>

<center><img src="/files/2_StarryNight/Post/6/04-0.jpg" style="width:120px; height:120px; border-radius:50%; border: 1px solid #ccc; margin-bottom: 5px;"></center>
##### <center>조성환 (shjo01)</center>

>막연하게 코딩은 아무나 건드리는 분야가 아니다라고만 생각 했습니다. Power Platform 교육은 그 생각 자체를 바꾸는 트리거 였습니다. 누구든지 간단한 학습만 하면 접근이 가능한 Power Platform 세계, 확장성이 무궁무진한만큼 꾸준한 Study와 트렌드를 따라갈 수 있는 센스가 무엇보다 중요하다는 것도 알게 되었습니다. 교육과 경연을 통해 직접 찾아보고 실습하면서, 내 것으로 만드는 과정이 좋았고, 팀원과 머리를 맞대고 협의하면서 하나의 성과물을 만들어 냈다는 것도 뿌듯했습니다. 항상 어떤 것을 처음 받아 들일때는 Open Mind가 중요한 것 같습니다. Power Platform이 Common한 Tool이 될것이다라고 모두가 예상하고 있는 만큼, 다양한 User에게 동등한 교육기회가 부여되어 모든 직원들이 새로운 Tool을 자연스럽게 받아들일 수 있는 기회가 많아졌으면 좋겠습니다. 

<br><br>

<center><img src="/files/2_StarryNight/Post/6/03-0.jpg" style="width:120px; height:120px; border-radius:50%; border: 1px solid #ccc; margin-bottom: 5px;"></center>
##### <center>김윤성 (yskim)</center>

>2일간의 교육과 2일간의 경연을 통해서 집중해서 뭔가 하나를 개발할 수 있는 자리가 마련되었다는 것이 뜻깊고 좋은 시간이었던 것 같습니다. 그리고 실질적으로 전문분야에 있는 Engineer들도 IT에 대한 지식이 부족할 수 있는데, 이런 IT 관련 개발자들이나 IT지식이 있는 사람들과의 서로의 Insight를 교류하고 Develop된 Idea들이 도출될 수 있는 만남의 자리가 많아져야 할 것으로 생각됩니다. 앞으로도 이런 기회가 또 생긴다면 참석하도록 노력하고, 주변 사람들에게도 권하도록 하겠습니다.

<br><br>

----------------------------------------------------------------------------------------

![](/files/2_StarryNight/Teamlogo/Starry Night OP_5T.png)

# 주제 
> ##### : SPUS (Site Photo Upload System) : 현장 사진 중앙 관리 및 DB


# 설명
>SPUS(Site Photo Upload System)을 개발하였습니다. 실제로 현장 FE나 공사경험을 수행하면서 개인장비로 촬영하였던 현장 사진들이 파편화되어 관리되고, 나중에 사진 관련 정보들을 열람할 때 어떤 사진이었는지 알기 어려운 부분이 있었기에 그런 부분들을 편리하게 DB화 해서 그 Data들을 취합/관리할 수 있는 시스템을 개발하고자 하였습니다. 개인 스마트폰에서 현장사진을 촬영을 하면서 함께 촬영한 사진의 정보를 기입하면, SharePoint에 그 Data들이 업로드가 되고, 나중에 App을 통해서 열람/수정/메일발송 할 수 있고, 추가로 작업일보로 Publishing해서 여러 사람들에게 공유도 해주는 확장성도 있는 App입니다.


----------------------------------------------------------------------------------------

# 결과 및 발표

<div class="video-container" align="center">
	<iframe width="560" height="315" src="https://www.youtube.com/embed/KNFK26tiHZg" title="YouTube video player" frameborder="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div><br>

----------------------------------------------------------------------------------------

# 과정 사진

![](/files/2_StarryNight/Post/6/2_6_pic_A.jpg)

![](/files/2_StarryNight/Post/6/2_6_B.jpg)

![](/files/2_StarryNight/Post/6/2_6_pic_B.jpg)

![](/files/2_StarryNight/Post/6/2_6_pic_C.jpg)