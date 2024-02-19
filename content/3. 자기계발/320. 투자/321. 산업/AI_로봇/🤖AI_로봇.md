---
title: 🤖AI_로봇
Created: 2023-07-07 11:01
aliases: []
tags : [AI, 로봇]
---
***


***
### 키워드
***
[[AI]]
[[온디바이스 AI]]
[[로봇]]


***
### 기업
***


***
```dataviewjs
const cfile = dv.current().file;
const list = dv.pages(`"${cfile.folder}"`)
.filter(b => b.file.name != cfile.name)
.sort(b => b.file.cday)
.map(b => b.file.link);
dv.list(list);
```