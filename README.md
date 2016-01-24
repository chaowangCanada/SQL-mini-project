# SQL-mini-project
Montreal Cargo Shipping (MCS) 
The database schema includes the following tables/relations. In each relation, the
underlined attributes together form the primary key for that relation.
1. Customer=fcNumber, cName, cAddress, cPhoneg.
2. Manufacturer= fmNumber, mName, mAddress, mManager, mPhoneg.
3. Product=fpNumber, mNumber, pName, pUnitPriceg.
4. Shippment=foNumber, cNumber, sDate, receivedDateg.
5. OrderDetail=foNumber, oDate, detailNo, pNumber, oQuantity, Costg.

To produce meaningful outputs to the various queries, make sure the number of tuples in each relation is
reasonably large (about 10 to 20 tuples in each table).


Express the following queries in SQL
1. List those customers who ordered a product that contains the substring \ware"
in the product's name.
2. Given an order number, give details of the products ordered.
3. List the name of those ordered exactly 3 dierent kinds of products in an order.
4. List the pair of name-manufacturer of every product with unit price above $100.
5. List the names of customers who have not ordered any product ordered by Frank,
who is a customer.
6. Find customers who ordered all the products.
7. For each customer, nd the highest and lowest number of products ordered.
Produce the output in the increasing order of the names of the customers.
