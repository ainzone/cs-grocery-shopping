# Case Study Grocery Shopping
This case study is specifically designed to provide valuable insights to third semester students pursuing Business Informatics at Pforzheim University.

## Background
The online grocery shopping company that you are working for is called "Fresh N' Easy". The company was founded two years ago and has since grown rapidly, with hundreds of thousands of customers using their services each month. Fresh N' Easy offers a wide range of fresh produce, meats, dairy, and pantry items, as well as household and personal care products.

To keep up with the growing demand, Fresh N' Easy has decided to invest in a comprehensive database system that will allow them to efficiently manage their inventory, orders, customers, and employees. They have chosen PostgreSQL as their preferred database management system. As a database administrator, your task is to design and implement a PostgreSQL database system that can efficiently store and manage the company's data.

## Database Information
The database system will consist of multiple tables that will store different types of data. The main tables include:
1. Customers: This table will store information about each customer, including their `name`, `email address`, `phone number`, and `home address`. It will also store the customer's account information, such as their `login credentials` and `payment details`.
2. Products: This table will store information about each product that Fresh N' Easy offers, including the `product name`, `description`, `price`, and `category`. It will also store information about the `supplier` and the `inventory level` of each product.
3. Orders: This table will store information about each order placed by a customer, including the `order number`, `date`, `status`, and `total cost`. It will also store `information` about the products ordered and the `quantity` of each product.
4. Inventory: This table will store information about the `current inventory level` of each product. It will include the `product ID`, the `quantity in stock`, and the `location` in the warehouse.
5. Employees: This table will store information about each employee working for Fresh N' Easy, including their `name`, `job title`, `contact information`, and `login credentials`.

With this database system in place, Fresh N' Easy will be able to efficiently manage their inventory, fulfill orders quickly and accurately, and provide their customers with a seamless shopping experience.

# Tasks
**Hint:** It is important to remember that ERD and UML are modeling languages, not prescriptive instructions. Different solutions may arise because they are dependent on the specific context, requirements, and constraints of the project at hand. What works well for one project may not work for another, so there is no "best" or "general" solution. The goal is to create a solution that accurately models the system being designed and meets the needs of the stakeholders involved. So, when different solutions arise, it is totally fine as long as they are valid and fulfill the requirements of the project. All tasks should connect to each other and build upon each other to create a comprehensive database system.
