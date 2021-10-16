---
layout: post
title: "[Starry Night] Insight 활동 자동화 Solution 개발"
author: StarryNgiht_환경솔루션
date: 2021-10-01 00:00:00 +09:00
tags: [kdshim, ktkim05, StarryNight]
image: /files/2_StarryNight/Post/Posthead_4.png
discription: "환경솔루션팀은 물과 폐기물. 바이오매스 등 환경 전반에 걸친 기술을 연구하고 있으며, 연구조직으로서 미래 먹거리를 찾는 Insight 활동을 활발히 하고 있습니다. 인터넷으로 최신 연구동향 및 소식들을 꾸준히 찾고 있으며 이러한 활동은 각 연구자들에게 많은 도움을 주고 있습니다. 이런 과정들은 단순한 업무지만 시간이 많이 소요되기 때문에 Insight 활동을 자동으로 해주는 솔루션을 개발하고자 하였습니다. 금회 개발한 솔루션은 각 연구자들의 관심 업무에 대한 키워드를 Power Automate의 RSS 기능을 적용한 자동검색을 통해 Google News의 최신 연구동향을 확인할 수 있습니다. 개발된 어플리케이션은 매일 주기적으로 검색어를 요청하는 모듈 및 검색어를 통해 Google News를 검색하여 파일로 저장하고 팀원에게 공유해 줄 수 있습ㄴ디ㅏ. 다양한 분야의 최신 기술동향을 공유함으로서 연구자들의 관심도 및 이해도 향상, 기술의 최신 트렌드 등을 확인하고 연구진행에 대한 방향성을 확인할 수 있어 팀 구성원 모두에게 그 가치를 제공하고자 하였습니다."
---


# 팀명 : 환경솔루션

> **소속 : G.E본부 / 환경솔루션팀 2명**

![](/files/2_StarryNight/Post/1/2_2_pic_T.jpg)

----------------------------------------------------------------------------------------

# 팀원

<center><img src="/files/2_StarryNight/Post/2/08-0.jpg" style="width:120px; height:120px; border-radius:50%; border: 1px solid #ccc; margin-bottom: 5px;"></center>
##### <center>심규대 (kdshim)</center>

>이번 교육을 통해 Digital Transformation(DT)이 경영진의 과제라고만 인식하던 개인적인 시각이 변하게 되었습니다. 업무에서 사용하는 상용 프로그램을 활용할때 이번에 교육한 Power Automate와 같은 Tool로 업무를 쉽고 빠르게 할 수 있으면 기존 업무방식에서 탈피해 개인별로도 다양한 DT가 이루어질 것이라 판단됩니다. 그리고 이러한 기회를 접할 수 있는 직원이 많아 질 수 있도록 다양한 교육 기회가 제공되었으면 하고, 회사에서도 DT의 구체적인 방향을 수립해 추진했으면 합니다. 마지막으로 본 강의를 준비하고 진행하신 강사님과 담당자분들게 감사드립니다!

<br><br>

<center><img src="/files/2_StarryNight/Post/2/09-0.jpg" style="width:120px; height:120px; border-radius:50%; border: 1px solid #ccc; margin-bottom: 5px;"></center>
##### <center>김기태 (ktkim05)</center>

>개인적으로 쉽게 접할 수 없는 IT분야의 최신 기술을 배우고, 이를 통해 프로그램을 개발할 수 있어서 정말 좋았습니다. 건설이라고 하면 옛날 기술이고 기술 개발도 많이 느리다고 생각하지만 금회 교육받았던 내용을 접목하여 실제 업무에 적용한다면 상당한 효과가 있을 것으로 생각됩니다. 실제로 몇몇 팀원분들은 저희가 개발한 “Insight 활동 자동화 솔루션 개발”에 관심을 보이고 계시며, 실제로 적용할 예정입니다. 앞으로도 이러한 기회가 개인적으로나 팀원들 모두에게 더 많이 제공되었으면 하는 바람이 있으며, 실제 업무에도 활용될 수 있도록 더 신경을 쓰려고 합니다. 이러한 교육을 기획하고 열정적으로 가르쳐 주신 강사님 및 담당자분들게 감사의 인사를 드립니다.

<br><br>

----------------------------------------------------------------------------------------

![](/files/2_StarryNight/Teamlogo/Starry Night OP_2T.png)

# 주제 
> ##### : Insight 활동 자동화 Solution 개발


# 설명
>환경솔루션팀은 물과 폐기물. 바이오매스 등 환경 전반에 걸친 기술을 연구하고 있으며, 연구조직으로서 미래 먹거리를 찾는 Insight 활동을 활발히 하고 있습니다. 인터넷으로 최신 연구동향 및 소식들을 꾸준히 찾고 있으며 이러한 활동은 각 연구자들에게 많은 도움을 주고 있습니다. 이런 과정들은 단순한 업무지만 시간이 많이 소요되기 때문에 Insight 활동을 자동으로 해주는 솔루션을 개발하고자 하였습니다. 금회 개발한 솔루션은 각 연구자들의 관심 업무에 대한 키워드를 Power Automate의 RSS 기능을 적용한 자동검색을 통해 Google News의 최신 연구동향을 확인할 수 있습니다. 개발된 어플리케이션은 매일 주기적으로 검색어를 요청하는 모듈 및 검색어를 통해 Google News를 검색하여 파일로 저장하고 팀원에게 공유해 줄 수 있습ㄴ디ㅏ. 다양한 분야의 최신 기술동향을 공유함으로서 연구자들의 관심도 및 이해도 향상, 기술의 최신 트렌드 등을 확인하고 연구진행에 대한 방향성을 확인할 수 있어 팀 구성원 모두에게 그 가치를 제공하고자 하였습니다.


----------------------------------------------------------------------------------------

# 결과 및 발표

<div class="video-container" align="center">
	<iframe width="560" height="315" src="https://www.youtube.com/embed/cx2Qd0x3nN0" title="YouTube video player" frameborder="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div><br>

----------------------------------------------------------------------------------------

# 과정 사진

![](/files/2_StarryNight/Post/1/2_2_pic_A.jpg)

![](/files/2_StarryNight/Post/1/2_2_B.jpg)

![](/files/2_StarryNight/Post/1/2_2_pic_B.jpg)
