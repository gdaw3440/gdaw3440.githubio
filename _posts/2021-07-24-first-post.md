---
title: "Brief] 서버 강제 종료 cmd"
excerpt: "간혹 서버 종료가 되지 않을 경우 사용하면 유용하다."

categories:
- Brief
tags:
- 강제종료, taskkill
last_modified_at: 2021-07-24
---

##### C:\users\이지성>netstat -ano|findstr 8080
##### TCP 0.0.0.0:8080 0.0.0.0:0 LISTENING 21392
##### TCP [::]:8080 [::]:0 LISTENING 21392

##### C:\users\이지성>taskkill /f /pid 21392
##### 성공: 프로세스(PID 21392)가 종료되었습니다.
