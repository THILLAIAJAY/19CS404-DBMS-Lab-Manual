# Experiment 3: DML Commands

## AIM
To study and implement DML (Data Manipulation Language) commands.

## THEORY

### 1. INSERT INTO
Used to add records into a relation.
These are three type of INSERT INTO queries which are as
A)Inserting a single record
**Syntax (Single Row):**
```sql
INSERT INTO table_name (field_1, field_2, ...) VALUES (value_1, value_2, ...);
```
**Syntax (Multiple Rows):**
```sql
INSERT INTO table_name (field_1, field_2, ...) VALUES
(value_1, value_2, ...),
(value_3, value_4, ...);
```
**Syntax (Insert from another table):**
```sql
INSERT INTO table_name SELECT * FROM other_table WHERE condition;
```
### 2. UPDATE
Used to modify records in a relation.
Syntax:
```sql
UPDATE table_name SET column1 = value1, column2 = value2 WHERE condition;
```
### 3. DELETE
Used to delete records from a relation.
**Syntax (All rows):**
```sql
DELETE FROM table_name;
```
**Syntax (Specific condition):**
```sql
DELETE FROM table_name WHERE condition;
```
### 4. SELECT
Used to retrieve records from a table.
**Syntax:**
```sql
SELECT column1, column2 FROM table_name WHERE condition;
```
**Question 1**
<img width="965" height="650" alt="image" src="https://github.com/user-attachments/assets/b53641ac-fec5-4f5e-b12c-20683962a1a8" />

sql
<img width="610" height="128" alt="image" src="https://github.com/user-attachments/assets/98260733-8b12-4df3-9a2e-385bf2b5048f" />

**Output:**

<img width="1346" height="352" alt="image" src="https://github.com/user-attachments/assets/44606607-d63a-49b0-b003-7db97e1aeeaf" />

**Question 2**
---
<img width="992" height="672" alt="image" src="https://github.com/user-attachments/assets/1b41996c-a991-4e40-963c-3865fdea39f2" />

sql
<img width="560" height="115" alt="image" src="https://github.com/user-attachments/assets/dd435587-47ad-4906-a70b-386989f60aea" />

**Output:**

<img width="1303" height="442" alt="image" src="https://github.com/user-attachments/assets/37a6aff6-a38f-4908-a8a9-a3dc195fefb7" />

**Question 3**
---
<img width="1116" height="520" alt="image" src="https://github.com/user-attachments/assets/7ddf0b3d-055f-41df-b9ad-ce15d4b60097" />

sql
<img width="1040" height="207" alt="image" src="https://github.com/user-attachments/assets/06ddc561-0a0d-41d1-87f4-884cafe75e35" />


**Output:**

<img width="1342" height="642" alt="image" src="https://github.com/user-attachments/assets/62f53772-ba22-46af-a09f-f3134d323035" />

**Question 4**
---
<img width="1302" height="832" alt="image" src="https://github.com/user-attachments/assets/efc62017-85cf-4160-977c-0ea2147eeed1" />

sql
<img width="1053" height="242" alt="image" src="https://github.com/user-attachments/assets/cc785689-dec6-443e-bc6c-7a46b8edea14" />

**Output:**

<img width="1293" height="546" alt="image" src="https://github.com/user-attachments/assets/d8052f93-65d9-43e9-a7b2-82492830d62c" />

**Question 5**
---
<img width="1131" height="577" alt="image" src="https://github.com/user-attachments/assets/374a8903-9519-459f-ace5-e789d2e6632f" />

sql
<img width="847" height="158" alt="image" src="https://github.com/user-attachments/assets/beb34156-7cc4-4759-b36b-3aae00e7c134" />


**Output:**

<img width="1356" height="402" alt="image" src="https://github.com/user-attachments/assets/13428613-6324-4819-8d36-61463cc99999" />

**Question 6**
---
<img width="1282" height="597" alt="image" src="https://github.com/user-attachments/assets/7c990846-601d-4350-82b3-bd56c61660b5" />

sql
<img width="876" height="340" alt="image" src="https://github.com/user-attachments/assets/947f0c49-1b32-4d79-9212-e433c62f987a" />

**Output:**

<img width="1434" height="832" alt="image" src="https://github.com/user-attachments/assets/69fd89b6-cc6d-4d77-bdef-a277b11e1b1e" />

**Question 7**
---
<img width="1168" height="668" alt="image" src="https://github.com/user-attachments/assets/8338d63d-71ca-44db-8d33-545763b05de1" />

sql
<img width="477" height="143" alt="image" src="https://github.com/user-attachments/assets/a527f075-0f67-4dac-b6aa-5556858fec29" />

**Output:**

![Output7](output.png)

**Question 8**
---
<img width="902" height="442" alt="image" src="https://github.com/user-attachments/assets/495cbff9-d362-475f-996e-2e60b3cd4f06" />

sql
<img width="688" height="226" alt="image" src="https://github.com/user-attachments/assets/b11584f3-ad8d-4e48-87e9-1e345a55a313" />

**Output:**
<img width="1358" height="762" alt="image" src="https://github.com/user-attachments/assets/4f002371-1b4f-45cb-9393-df6ced87b6c4" />


**Question 9**
---
<img width="1217" height="715" alt="image" src="https://github.com/user-attachments/assets/b6a39425-d21c-41f1-b83c-aa70992734ae" />

sql
<img width="940" height="237" alt="image" src="https://github.com/user-attachments/assets/99b66970-4f51-4852-ae94-bccf484107d6" />

**Output:**

<img width="1232" height="815" alt="image" src="https://github.com/user-attachments/assets/c4f8ba60-f8af-4655-bc38-7dfff69c78e8" />

**Question 10**
---
<img width="1326" height="562" alt="image" src="https://github.com/user-attachments/assets/1485a697-c68c-4b4c-93fd-158a050ce5a4" />

sql
<img width="561" height="200" alt="image" src="https://github.com/user-attachments/assets/e69e299a-7eac-4133-9213-8033207319db" />

**Output:**

<img width="1103" height="348" alt="image" src="https://github.com/user-attachments/assets/a40f4904-fee8-49ab-9ee9-ffd6e13a1f56" />

## RESULT
Thus, the SQL queries to implement DML commands have been executed successfully.
