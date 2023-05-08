Download Link: https://assignmentchef.com/product/solved-relationaldatabase-assignment-2a
<br>
You are now familiar with multi table database design and design principles aka Normal Forms to create a ‘good’ table structure. In a real life scenario, a database will most definitely consist of more than one table. Each table will store data about one entity of interest. Relationships will exist between the tables. In your first Assignment 1a, you had come up with a real life scenario where a database will work well.  You had created a relevant table to store information about an entity.

Continue working with the script you created for Assignment 1a. Ensure it is <strong>well-documented – </strong>include name(s), date and purpose of the script at the head of the script and comment all code sections.<strong> Use meaningful names and consistent naming conventions throughout the script. </strong>The script should execute correctly without any syntax or logical errors or warnings.

Start with the script you created in Assignment 1a. <strong>Add another relevant table to the database now</strong>. I am going to refer to the table you created in Assignment 1a as the ‘old’ table and this table as the ‘new’ table. Do a good job creating this new table and populating it with data. In the next sub assignment, you will need to retrieve data from the two tables, using joins and subqueries. The tables should satisfy the following requirements.

<ul>

 <li>The new table should at least have 5 relevant fields. Choose the CORRECT BEST FIT data types and other properties (not null, default etc) depending on the data to be stored in the fields. <strong>Comment the PURPOSE of each field.</strong></li>

 <li>Both tables must be in Second Normal Form/2NF. Put the definitions of First Normal Form/1NF and Second Normal Form/2NF in comments and justify that the two tables are in 2NF.</li>

 <li>The new table must have a foreign key that references a field (preferably primary key) of the old table. You can have more than one foreign keys in the new table, if required. You may ‘reverse’ this requirement. The old table can have a foreign key instead referring to a field (preferably primary key) of the new table. The aim is that the two tables are ‘related’ via foreign key(s). You will not be able to do the following sub assignments if the tables are not ‘related’.</li>

 <li>Clearly ‘comment’ the type of relationship (1-1, 1-m, m-m) between the two tables.</li>

 <li>Display the structure of the new table.</li>

 <li>Populate the table with <strong>relevant</strong> data, at least 10 records. Ensure that you have the set the sql_mode to “STRICT_ALL_TABLES” to catch data input errors. <strong>Important Note: Use literal text data in quotes, numeric data without quotes and date in a consistent format of your choice. You will lose marks if you do not follow this instruction.</strong></li>

 <li>Add a SELECT statement to display the records of the new table.</li>

</ul>

Provide an Entity Relationship Diagram (ERD) to depict the database structure- the entities and the relationship(s) between them. You can use any software program or do it by hand. The ERD must clearly show all tables, all the fields in the tables, clearly labeled primary keys and foreign key(s) and the relationship(s) labeled with the type of relationship (1-1, 1-m, m-m). I have covered all this in my videos starting Week 7. It must have a legend, if you are using colors or symbols to label the fields. I leave the ERD creativity to you but it must be clear, correct and complete. I need you to take a ‘Print Screen’ or a picture (if you drawing by hand) and paste it into a .doc file.