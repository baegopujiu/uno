---
title: 📶IT
Created: 2023-10-20 14:01
aliases: 
tags:
---
***


***
### 키워드
***

***
### 분류
[[인터넷]]
[[보안]]
	[[정보 보안]]
	[[보안 서비스]]
[[솔루션]]
	[[금융 솔루션]]
	[[업무 솔루션]]
	[[자동화 솔루션]]
[[서비스]]
	[[신용정보 서비스]]
	[[IT 인프라]]
	[[IT 플랫폼]]
	[[서비스 결제]]
[[SI]]
***
### 기업
***
![[보안 기업]]
![[SI 기업]]
![[솔루션 기업]]
IT플랫폼 기업
- [[카페24]]
![[서비스 결제 기업]]
***
```dataviewjs
const cfile = dv.current().file;
const list = dv.pages(`"${cfile.folder}"`)
.filter(b => b.file.name != cfile.name)
.sort(b => b.file.cday)
.map(b => b.file.link);
dv.list(list);
```