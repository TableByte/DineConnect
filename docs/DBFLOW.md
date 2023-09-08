# User login and management 
![dbdesignf](https://github.com/TableByte/DineConnect/assets/96981272/ececef0e-abdc-4eb1-a32d-155be1fe7215)

### Table 1: User_details
This table contains primary key Phone_no and Foreign key as User_Role_id which connects to user_roles(Table 2) table.

### Table 2: User_Roles
This table contains PK as User_role_id and two FK User_Phone_no which connects to User_details (table 1) and Role_id which connects according to the roles i.e Owner_table(Table 3), Manager(Table 4), Employee(Table 5)  table respectively 

### Table 3: Hotel_Details
This table conatains hotel details like hotel name and Location.

### Table 4: Jobs_posted
This table stores the information regarding the jobs available.

### Table 5: Application
This table can be used to store the details of the applications applied for the job.

# Create Orders
![dbdesign3](https://github.com/TableByte/DineConnect/assets/96981272/5a4ffd83-5287-43e6-a822-01b628185d24)

### Table 9: Billing_table
This table will conatin the details of the each order by the custormer.

### Table 10: Menu_table
This table contains information of all the menu items present in the hotel.

### Table 11: Menu_item_table
This table contains the details of all the single items orders in what quantity.
