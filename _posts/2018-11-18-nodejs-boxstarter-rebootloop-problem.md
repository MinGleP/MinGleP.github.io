---
layout: post
current: post
cover:  assets/images/problem01.jpg
navigation: True
title: Nodejs boxstarter 무한 재부팅 문제해결
date: 2018-11-18 15:30:00
tags: [Solve Problem]
class: post-template
subclass: 'post boxstarter problem'
author: Min
---

Nodejs 설치시에 툴도 같이 설치하겠다고 체크하면
boxstarter가 같이 설치되고


CMD창이 뜨면서 무한 재부팅이 되는 문제가 발생




해결방안 :

C:\ProgramData\boxstarter << delete all

C:\Users\Usersname\AppData\
Roaming\Microsoft\Windows\
Start Menu\Programs\Startup for the boxstarter-post-restart.bat




boxstarter 폴더와 boxstarter-post-restart.bat 파일을 삭제
