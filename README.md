# Introduction to Relational Databases, SQL and Knex

Guided project for Node DB 1 module.

In this project we will cover the basics of `Structure Query Language (SQL)`, `Relational Databases`, and `Knex.js Queries`.

## Prerequisites

- [DB Browser for SQLite](https://sqlitebrowser.org) installed.

## Project Setup

- [ ] fork and clone this repository.
- [ ] **CD into the folder** where you cloned **your fork**.
- [ ] type `npm install` to download dependencies.

                        --This is (DQL) Data Query Language--

SELECT <columns>
FROM <table>
WHERE <column> = <value>;

<!-- Examples -->
<!-- Select "ShippedDate"
FROM "Order"
WHERE "id" = 19570;

SELECT * 
FROM "Product"
WHERE "UnitsInStock" >= 100
ORDER BY "UnitsInStock"
LIMIT 3;

SELECT *
FROM "Product"
ORDER BY "UnitPrice" DESC
LIMIT 1
OFFSET 3; -->


                    --This is Data Manipulation Language (DML)--

<!-- EDIT -->
INSERT INTO <Table> (<column1>, <column3>)
VALUES (<value1>, <value3>);

<!-- UPDATE -->
UPDATE <table>
SET <column> = <new value>
WHERE <column> = <value>;

<!-- DELETE -->
DELETE FROM <table>
WHERE <column> = <value>;


<!-- Examples -->
<!-- --INSERT INTO "Category" ("CategoryName", "Description")
--VALUES ("Frozen", "Ready to eat Meals");


--UPDATE "Category"
--SET "Description" = 'Deserts and ready to eat meals'
--WHERE "Id" =9;

DELETE FROM "Category"
WHERE "Id" =8; -->

