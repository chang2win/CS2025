
# SQL
- online SQL
# Wide World Importers 範例資料庫
## [Northwind and pubs sample databases](https://github.com/microsoft/sql-server-samples/tree/master/samples/databases/northwind-pubs)
### [適用于 Microsoft SQL 的 Wide World Importers 範例資料庫](https://learn.microsoft.com/zh-tw/sql/samples/wide-world-importers-what-is?view=sql-server-ver16)
## [SQL 的 JOIN 查詢有哪幾種類型？](https://www.fooish.com/sql/join.html)
```
INNER JOIN 內部連接
LEFT (OUTER) JOIN 左外部連接
RIGHT (OUTER) JOIN 右外部連接
FULL (OUTER) JOIN 全部外部連接
CROSS JOIN 交叉連接
NATURAL JOIN 自然連接
```
## https://www.fooish.com/sql/
```
SQL (可以唸字母 S. Q. L. 或 sequel)
用來建立、操作及存取關聯式資料庫 (Relational Database) 的語言就是 SQL。
而對於 SQL 的標準化作業，主要是由 ANSI 與 ISO 這兩個組織所推動。

SQL 語言可大致分為幾個類別


Data definition 資料定義 (DDL)
用來定義資料庫、資料表、檢視表、索引、預存程序、觸發程序、函數等資料庫物件。

常見的指令有：
CREATE: 建立資料庫的物件
ALTER: 變更資料庫的物件
DROP: 刪除資料庫的物件



Data manipulation 資料操縱 (DML)
用來處理資料表裡的資料，常見的指令有：

INSERT: 新增資料到資料表中
UPDATE: 更改資料表中的資料
DELETE: 刪除資料表中的資料
Queries 資料查詢 (DQL)
用來查詢資料表裡的資料：

SELECT: 選取資料庫中的資料

Data control 資料控制 (DCL)
用來控制資料表、檢視表的存取權限，常見的指令有：

GRANT: 賦予使用者使用權限
REVOKE: 取消使用者的使用權限

Transaction controls 交易
交易是單一工作單元。 如果交易成功，便會確定交易期間所修改的所有資料，且會成為資料庫中永久的內容。 
如果交易發現錯誤，必須取消或回復，便會清除所有的資料修改。

COMMIT: 完成交易作業
ROLLBACK: 交易作業異常，將已變動的資料回復到交易開始的狀態
```
## DEMO 資料庫:Northwind sample database (included in MS Access and MS SQL Server)


# [SQL Joins](https://www.w3schools.com/sql/sql_join.asp)
```
Different Types of SQL JOINs
Here are the different types of the JOINs in SQL:

(INNER) JOIN: Returns records that have matching values in both tables
LEFT (OUTER) JOIN: Returns all records from the left table, and the matched records from the right table
RIGHT (OUTER) JOIN: Returns all records from the right table, and the matched records from the left table
FULL (OUTER) JOIN: Returns all records when there is a match in either left or right table
```
## [Different Types of SQL JOINs]()
