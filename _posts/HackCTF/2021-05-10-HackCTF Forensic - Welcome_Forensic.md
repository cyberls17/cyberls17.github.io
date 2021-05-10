---
layout: post
title: [HackCTF Forensic - Welcome_Forensics]
author: "cyberls17"
category: [Wargame Write-up, HackCTF]
tags: [Write-up]
---

# Welcome_Forensic

**HackCTF에 있는 Forensic 첫번째 문제, Welcome_Forensic**

![Welcome_Forensic_Prob](/images/Welcome_Forensic_Prob.PNG)<br>

먼저 문제를 살펴보면 글씨 쓰여있는 사진이 있다.<br>
사진에 나와있는 값이 Flag라고 생각되지만, 사진이 보기 힘들게 되어있다.<br>
그래서 사진을 다운로드 받아보았다.<br>

![forensics1](/images/forensics1.gif)<br>

사진에 Flag 값이 보인다.<br>
그대로 입력했더니 해결~

```Flag: HackCTF{w3lc0m3_70_f0r3n51c_w0rld!}```