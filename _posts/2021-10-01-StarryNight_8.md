---
layout: post
title: "[Starry Night-8] 팀 성과 기록 관리 & 공유 System"
author: StarryNgiht_기술지원팀
date: 2021-10-01 00:00:00 +09:00
tags: [khleem, wjshin, StarryNight]
image: /files/2_StarryNight/Post/Posthead_4.png
discription: "팀의 성과지표(TIMS 기술지원 성과 집계) 수시 Update 및 공유 App 개발 - 연중 팀원들의 성과지표를 작성하여 팀 차원의 Data로 집계하는 것은 간단한 작업이지만 의외로 상당한 시간과 Manhour 가 소모된다. 먼저 팀원들이 성과지표를 작성하고, 그 작성한 내용을 팀의 누군가가 취합하여 팀의 결제권자에게 보고하게 된다. 팀의 결제권자는 취합된 Data를 확인 하고 승인할 내용과 다시 작성해야 되는 내용을 확인 후 팀원 개개인에게 Feed Back을 줘야 하며 Feed Back을 받은 팀원들은 해당 성과지표를 재작성 하게 되고 일련의 Process들이 반복적으로 수행된다. 이러한 과정에서 누락분도 생기게 되고, 취합인원의 Manhour 가 상당량 소모되면서 소위 '업무의 질'이 하락하게 되는것을 종종 경험하게 되는데, 이러한 불필요한 반복 작업을 자동화하고 나아가 해당 내용을 실시간 Update 및 공유하여 업무성과에 대한 통계적 인사이트를 년중 수시로 확인할 수 있도록 Power Platform (Power Apps, Power Automate)으로 구현해 보았다."
---


# 팀명 : 기술지원팀

> **소속 : 선행기술본부 / 인프라구조팀 1명, 지반팀 1명**

![](/files/2_StarryNight/Post/8/2_8_pic_T.jpg)

----------------------------------------------------------------------------------------

# 팀원

<center><img src="/files/2_StarryNight/Post/8/10-0.jpg" style="width:120px; height:120px; border-radius:50%; border: 1px solid #ccc; margin-bottom: 5px;"></center>
##### <center>임경훈 (khleem)</center>

>이번 교육을 통해 약간은 멀게 느껴지는 ‘Digital Transformation’과 같은 변화가 그리 먼 곳에 있지 않다는 것을 체감하게 되었습니다. Power Platform은 업무의 자동화, 생산성 향상을 위해 IT 개발자가 아닌, 실무의 최전선에 있는 직원들이 직접 쉽게 자신들의 업무에 필요한 App을 만들고 업무(본연의 업무이든 단순 반복적인 업무이든)를 자동화 함으로써 업무 생산성을 높이는 것을 골자로 하고 있습니다. 이를 시민 개발자(Citizen Developer)라는 개념으로 설명하고 있는데요, 이러한 흐름이 소수에만 국한되는 것이 아니라 전반적인 업무환경에 도입될 가능성이 있어 보이고, 이러한 변화를 우리도 차근차근 대비해 나가야 되겠다는 생각이 들었습니다.

<br><br>

<center><img src="/files/2_StarryNight/Post/8/11-0.jpg" style="width:120px; height:120px; border-radius:50%; border: 1px solid #ccc; margin-bottom: 5px;"></center>
##### <center>신원재 (wjshin)</center>

>입사 후 근 9년을 일하면서 단순 반복 작업을 달고 살았던 것 같습니다. 사무 업무를 하면서 어쩔 수 없는 부분이라고 생각은 했지만 그래도 언젠간 불필요한 업무를 모두 자동화 할 수 있는 날이 오지 않을까 하는 생각을 해왔습니다. 그러던 중 이번 기회에 Power Platform(Power Apps, Power Automate)이라는 Tool를 접하게 되었고, 교육을 듣고 경연실습을 해보면서 어쩌면 오랜기간 소망했던 업무 자동화가 실현될 수 있지 않을까 하는 생각이 들었습니다. Power Platform 은 높은 코딩지식이 요구되지도 않아 일반 Citizen Developer 수준에서도 사용이 용이하니 앞으로는 엑셀이나 파워포인트처럼 보편적으로 쓰게 되는 어플리케이션 될 것으로 전망하며, 아직은 부족하지만 추가적인 학습을 통해 이 '강력한' tool을 이용하여 불필요한 단순업무들은 자동화하고 하고 남는 업무 시간에는 제 본연에 업무에 좀 더 집중하여 고부가 가치를 창출하는 핵심인력이 되는 것이 저의 목표입니다. 사내 여러 사우여러분들께도 해당 교육기회가 많이 주어지고 해당 Tool에 익숙해 진다면 전사적으로 큰 도움이 될 것이라 믿어 의심치 않습니다.

<br><br>


----------------------------------------------------------------------------------------

![](/files/2_StarryNight/Teamlogo/Starry Night OP_8T.png)

# 주제 
> ##### : 팀 성과 기록 관리 & 공유 System


# 설명
>팀의 성과지표(TIMS 기술지원 성과 집계) 수시 Update 및 공유 App 개발 - 연중 팀원들의 성과지표를 작성하여 팀 차원의 Data로 집계하는 것은 간단한 작업이지만 의외로 상당한 시간과 Manhour 가 소모된다. 먼저 팀원들이 성과지표를 작성하고, 그 작성한 내용을 팀의 누군가가 취합하여 팀의 결제권자에게 보고하게 된다. 팀의 결제권자는 취합된 Data를 확인 하고 승인할 내용과 다시 작성해야 되는 내용을 확인 후 팀원 개개인에게 Feed Back을 줘야 하며 Feed Back을 받은 팀원들은 해당 성과지표를 재작성 하게 되고 일련의 Process들이 반복적으로 수행된다. 이러한 과정에서 누락분도 생기게 되고, 취합인원의 Manhour 가 상당량 소모되면서 소위 '업무의 질'이 하락하게 되는것을 종종 경험하게 되는데, 이러한 불필요한 반복 작업을 자동화하고 나아가 해당 내용을 실시간 Update 및 공유하여 업무성과에 대한 통계적 인사이트를 년중 수시로 확인할 수 있도록 Power Platform (Power Apps, Power Automate)으로 구현해 보았다.


----------------------------------------------------------------------------------------

# 결과 및 발표

<div class="video-container" align="center">
	<iframe width="560" height="315" src="https://www.youtube.com/embed/PW0RnaTeijw" title="YouTube video player" frameborder="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div><br>

----------------------------------------------------------------------------------------

# 과정 사진

![](/files/2_StarryNight/Post/8/2_8_pic_A.jpg)

![](/files/2_StarryNight/Post/8/2_8_B.jpg)

![](/files/2_StarryNight/Post/8/2_8_pic_B.jpg)
