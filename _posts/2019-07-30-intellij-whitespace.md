---
layout: post
title: add whitespace in intellij
date:   2019-07-30 09:41
description: 
comments: true
category: [ jetbrains ]
tags:
- 
---

jetbrains의 IDE는 글자 뒤에 여러 공백 문자를 기본적으로 추가할 수 없다. 

문자 뒤에 공백 문자를 추가할 수 있도록 설정하기 위해서는 IDE의 설정을 변경해야 한다.

변경하는 방법은 간단하며, 다음은 이에 대한 예제이다:

![IDE 설정 화면]( {{ "/assets/img/2019-07-30_09-46-33.png"  | absolute_url }})

위와 같은 화면은 `File > Settings... >  Editor > Genneral`로 이동한 상태이다.

설정 내용은 `Other` 항목에서 `Strip trailing spaces on Save:` 옵션을 `None`으로 변경한다.
