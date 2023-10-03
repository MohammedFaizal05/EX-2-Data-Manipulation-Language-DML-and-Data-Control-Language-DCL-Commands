# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/d1cfd2e5-2ff3-4ddc-9c7f-b69b97ae8269)

### OUTPUT:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/2541479b-bdf4-4835-9e38-e38b66f10a13)

### Q2) Delete the records from manager table where the salary less than 2750.
## QUERY:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/c0b77777-c20a-42a0-8d10-8d52d1f9a36e)

## OUTPUT:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/6d2dd7a5-adee-44da-8dc6-86c7d6a628a2)

### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)
### QUERY:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/1df93a94-73fc-423a-a7a5-d9c084cabe6f)

### OUTPUT:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/05e8593b-621a-488f-bb1b-5b657663cdab)

### Q5)	List the names of Clerks from emp table.
## QUERY:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/a527a98c-eb73-4c44-aba8-267aa9bdc8fc)

### OUTPUT:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/07411149-269e-4d30-97ea-83cb7d8cf167)

### Q6)	List the names of employee who are not Managers.
### QUERY:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/b7308848-97ac-44c7-8a82-907170d27918)

### OUTPUT:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/d7e26672-55ed-4ca5-aeb3-55ff5a85398f)

### Q7)	List the names of employees not eligible for commission.
### QUERY:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/30b4b0a2-4106-41ce-8e0a-f5ae7a14761a)

### OUTPUT:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/00f33a4a-f0ca-4112-a0db-d88efafc199d)


### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/ede4b0be-604e-49a9-9678-02e59444fd09)

### OUTPUT:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/96452e5f-c061-4053-bedc-9de5eb9d78c2)


### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/65bdf744-9c70-43c2-b521-c1ce4e748e4c)


### OUTPUT:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/b5275e5f-be6c-4e54-b8e4-e554f530badd)


### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/7e558d5c-0cf6-44f4-8fbc-733eeda79a43)


### OUTPUT:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/68ab520d-5950-41f6-a3e3-7a06c7f8ccad)


### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:

![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/122f5a2f-0125-4af6-9948-ae788e30b656)

### OUTPUT:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/05f2ba89-8d1f-4c35-ac66-f8e610ff193b)


### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/949a552e-b10f-44f3-a95f-d251d4fee673)


### OUTPUT:

![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/46dd8238-2e83-4c6a-8964-292af24f767c)

### Q13) Find number of rows in the table EMP

### QUERY:

![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/fe34fb51-ab61-4919-9029-662006e270d9)

### OUTPUT:

![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/996bb3fd-1bc8-4c3f-bda7-10bb1d5f4615)


### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:

![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/bb0bbbe3-de7b-40bc-80e1-61d06f4b8c0f)


### OUTPUT:

![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/8ecdf6c2-3041-4cea-b277-69a5abcc1f8e)


### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:

![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/210cf0f5-df1d-4150-af28-77b9999f6a17)


### OUTPUT:

![image](https://github.com/MohammedFaizal05/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120553195/05ba95f9-0955-4b47-b292-75c08cc14f3e)
### RESULT:
Thus the Data Manipulation Language (DML) Commands and built in functions in SQL
