# 早餐訂餐系統練習 (Breakfast Ordering Practice)

這是一個簡單的後端專案，用於實現早餐店的訂餐系統，使用 Spring Boot、Spring JDBC 以及 MySQL。此專案遵循 RESTful 設計原則，讓使用者能夠瀏覽菜單、下訂單，並管理菜單項目。

## 功能

- **顧客管理**：註冊、登入，並管理顧客資料。
- **菜單管理**：查看、添加、更新、刪除菜單項目，並依據分類如熱銷、吐司、漢堡、飲料、組合進行管理。
- **訂單管理**：顧客可以建立、查看、更新訂單狀態。
- **支付管理**：記錄支付狀態，並查看支付紀錄。

## 技術棧

- **Spring Boot**：後端框架
- **Spring JDBC**：資料庫連接
- **MySQL**：資料庫
- **JUnit**：單元測試框架

## 安裝與執行

### 1. clone 專案

```bash
git clone https://github.com/your-repo/breakfast-ordering-practice.git
cd breakfast-ordering-practice
