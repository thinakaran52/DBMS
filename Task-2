create database ProductCategory;

use Productcategory;

create table Category(
     CategoryId int primary key,
     CategoryName varchar(100)
     );


Insert into Category
values(1,"Electronics"),
       (2,"Books"),
        (3,"Cloths");
        
        
create table product(
     ProductID int,
     ProductName varchar (50),
     CategoryID int,
     Price int,
     Stock int,
     foreign key (CategoryID) references Category (CategoryID));
     
     
insert into product
values(1,"Laptop", 1, 80000, 30),
      (2,"Mobile", 1, 20000, 10),
      (3,"Python Book", 2, 800, 35),
      (4,"Men's Pant", 3, 2000, 20),
      (5,"Men's Shirt", 3, 1000, 25),
      (6,"DBMS Book", 2, 1500, 8);


delete from product
WHERE ProductID = 5;


update product
set Price = 75000
where ProductID = 1;


select CategoryName, ProductName, Price, Stock
from category
join product
on category.CategoryID = product.CategoryID;

  
select * from Category;
select * from product;
