# Experiment 2: DDL Commands

## AIM
To study and implement DDL commands and different types of constraints.

## THEORY

### 1. CREATE
Used to create a new relation (table).

**Syntax:**
```sql
CREATE TABLE (
  field_1 data_type(size),
  field_2 data_type(size),
  ...
);
```
### 2. ALTER
Used to add, modify, drop, or rename fields in an existing relation.
(a) ADD
```sql
ALTER TABLE std ADD (Address CHAR(10));
```
(b) MODIFY
```sql
ALTER TABLE relation_name MODIFY (field_1 new_data_type(size));
```
(c) DROP
```sql
ALTER TABLE relation_name DROP COLUMN field_name;
```
(d) RENAME
```sql
ALTER TABLE relation_name RENAME COLUMN old_field_name TO new_field_name;
```
### 3. DROP TABLE
Used to permanently delete the structure and data of a table.
```sql
DROP TABLE relation_name;
```
### 4. RENAME
Used to rename an existing database object.
```sql
RENAME TABLE old_relation_name TO new_relation_name;
```
### CONSTRAINTS
Constraints are used to specify rules for the data in a table. If there is any violation between the constraint and the data action, the action is aborted by the constraint. It can be specified when the table is created (using CREATE TABLE) or after it is created (using ALTER TABLE).
### 1. NOT NULL
When a column is defined as NOT NULL, it becomes mandatory to enter a value in that column.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) NOT NULL
);
```
### 2. UNIQUE
Ensures that values in a column are unique.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) UNIQUE
);
```
### 3. CHECK
Specifies a condition that each row must satisfy.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) CHECK (logical_expression)
);
```
### 4. PRIMARY KEY
Used to uniquely identify each record in a table.
Properties:
Must contain unique values.
Cannot be null.
Should contain minimal fields.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) PRIMARY KEY
);
```
### 5. FOREIGN KEY
Used to reference the primary key of another table.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size),
  FOREIGN KEY (column_name) REFERENCES other_table(column)
);
```
### 6. DEFAULT
Used to insert a default value into a column if no value is specified.

Syntax:
```sql
CREATE TABLE Table_Name (
  col_name1 data_type,
  col_name2 data_type,
  col_name3 data_type DEFAULT 'default_value'
);
```

**Question 1**
--
<img width="1252" height="300" alt="image" src="https://github.com/user-attachments/assets/efd2c103-e97c-4eaa-9b45-1712bdd9a4ae" />

sql
<img width="938" height="122" alt="image" src="https://github.com/user-attachments/assets/070fe95e-a7d5-46d9-9592-c4063eaa7309" />




**Output:**

<img width="1245" height="308" alt="image" src="https://github.com/user-attachments/assets/3a21d557-63e9-42ec-8800-fd129f86a625" />
**Question 2**
---
<img width="1246" height="392" alt="image" src="https://github.com/user-attachments/assets/cfec6d1d-3e12-4deb-b596-594a0b645c40" />

sql
<img width="795" height="275" alt="image" src="https://github.com/user-attachments/assets/d74a7eaf-1b42-4cc9-9b99-d269b75d1f69" />


**Output:**

<img width="1336" height="473" alt="image" src="https://github.com/user-attachments/assets/e904bdbe-438c-4a65-9e57-1aadac2d8188" />

**Question 3**
---

sql
<img width="858" height="437" alt="image" src="https://github.com/user-attachments/assets/9b2804c1-5cd8-4f97-a169-c98c86195e25" />


**Output:**

<img width="1277" height="411" alt="image" src="https://github.com/user-attachments/assets/f4e77dab-934c-48e2-bee0-473742eb6de7" />

**Question 4**
---
<img width="1247" height="462" alt="image" src="https://github.com/user-attachments/assets/bf35acb5-d7ff-4187-9e78-98222fe75148" />

sql
<img width="1147" height="329" alt="image" src="https://github.com/user-attachments/assets/53c6e3e7-c9a8-486a-9b97-e19b9b60aa16" />

**Output:**

<img width="1233" height="487" alt="image" src="https://github.com/user-attachments/assets/f4640d44-2325-475e-a6e7-7c4141de1f52" />

**Question 5**
---
<img width="1268" height="402" alt="image" src="https://github.com/user-attachments/assets/5de12888-1259-419f-8d2b-605d2009a3da" />
sql

**Output:**
<img width="1316" height="413" alt="image" src="https://github.com/user-attachments/assets/f60f7786-8b68-4cdc-a304-c495090000ad" />



**Question 6**
---
<img width="1077" height="621" alt="image" src="https://github.com/user-attachments/assets/51697cd5-1750-4f52-9281-b2757528f038" />

sql
<img width="1007" height="309" alt="image" src="https://github.com/user-attachments/assets/ea375421-e6bd-46e9-aaa2-e426023ae478" />

**Output:**

<img width="1253" height="416" alt="image" src="https://github.com/user-attachments/assets/019f64df-a248-42d2-ab15-1f9d9fe2ce18" />

**Question 7**
---
<img width="1223" height="512" alt="image" src="https://github.com/user-attachments/assets/8cb9b36c-235e-4244-a1eb-d902dc3ae8af" />

sql
<img width="1112" height="370" alt="image" src="https://github.com/user-attachments/assets/1fe2c71b-43c3-4c67-8986-8e84206b747d" />


**Output:**

<img width="1302" height="371" alt="image" src="https://github.com/user-attachments/assets/f2e6072f-c83b-4050-af68-549b71173e69" />

**Question 8**
---
<img width="1248" height="610" alt="image" src="https://github.com/user-attachments/assets/43561ec7-4b30-493b-9c94-43ec64e345eb" />

sql


**Output:**

<img width="1276" height="420" alt="image" src="https://github.com/user-attachments/assets/58812ce9-e06d-42b7-84ea-a1f2845bf0a5" />

**Question 9**
---
<img width="910" height="396" alt="image" src="https://github.com/user-attachments/assets/76357e9a-9f8e-4ac5-86c3-9264057a7400" />

sql
<img width="947" height="265" alt="image" src="https://github.com/user-attachments/assets/fdf00ab5-90ee-40d5-9e4a-ffd51aa3a4dc" />


**Output:**

<img width="1255" height="278" alt="image" src="https://github.com/user-attachments/assets/61f403f7-5ae6-40a5-b0c8-246860c24ab1" />

**Question 10**
---
<img width="1247" height="461" alt="image" src="https://github.com/user-attachments/assets/0ad97718-7f7a-45cb-a329-602c261f8b5b" />

sql
<img width="931" height="358" alt="image" src="https://github.com/user-attachments/assets/54a72d75-0040-4834-9322-fcbdf4a8bb21" />


**Output:**

<img width="1271" height="401" alt="image" src="https://github.com/user-attachments/assets/db1206d1-5136-4058-b10b-38c7fb31760d" />


## RESULT
Thus, the SQL queries to implement different types of constraints and DDL commands have been executed successfully.
