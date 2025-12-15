# Rule and structure

## Clean Architecture

Rstar 的後端採用 DDD + Clean Architecture, packeage 採用 maven-multi project.

由於專案為 Spring Cloud 微服務架構, 區分服務為 Backend For Frontend (BFF) 和 Business (Biz), 兩者各有相應的規則。

這裡先介紹 Class 的用途與規則, 依賴的方向, 再介紹共用 package 的管理, 最後呈現實際開發的專案資料夾結構。

## 核心 Class

### BFF




### Biz