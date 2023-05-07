Download Link: https://assignmentchef.com/product/solved-int2005-lab02
<br>
Database Management System

<strong> </strong>

<h1>LAB02: SQL Review</h1>

__________________________________________________________________________ <strong>Submission</strong>:

<ul>

 <li>Submit a lab file named “int205_lab02_xxxxxxxxxxx.docx/.pdf” into the LEB2 system. xxxxxxxxxxx = your student id</li>

 <li><strong><u>Do NOT submit</u></strong> both a PNG file and a MWB file.</li>

</ul>




<strong>Due Date &amp; Time</strong>:

<ul>

 <li>Lecturer will inform the LAB02 due date and time in lab class.</li>

</ul>

__________________________________________________________________________

<strong>Task 1: Using MySQL Workbench to create an ER-diagram for the “classicmodels”.</strong>




1.1  Use the script named “classicmodels” to generate ER diagram (Reverse         Engineering technique).




<ul>

 <li>Open the MySQL Workbench program</li>

 <li>Select the menu “Database” =&gt; “Reverse Engineer…”.</li>

 <li>Please follow the step by step instructions below:</li>

</ul>




<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

























<strong> </strong>

<strong>   </strong>      The example ER diagram for the classicmodels.

<strong> </strong>

<strong> </strong>

<strong> </strong>

1.2  Re-arrange the ER diagram for readability and review the tables, columns, data         types and relationships among the tables.

<ul>

 <li>Save a model named “classicmodels.mwb” (the default extension file is .mwb) and export a model as a .png file named  “classicmodels_er.png” stored in your computer.</li>

</ul>




<ul>

 <li>Place your ER image (the png file) here.</li>

</ul>




<table width="623">

 <tbody>

  <tr>

   <td width="623">                   </td>

  </tr>

 </tbody>

</table>




<u> Note:</u> The MSRP is “Manufacturer’s suggested retail price” (ราคาขายปลกี แนะน าของผผู้ ลติ). <strong> </strong>

<strong>Task 2: Using the “classicmodels” schema and write SQL statements to answer the following questions. </strong>

<strong> </strong>

<strong>The Syntax of SELECT statement</strong>:

Documentation: <a href="https://dev.mysql.com/doc/refman/8.0/en/select.html">https://dev.mysql.com/doc/refman/8.0/en/select.html</a>




<u>Note:</u> The MySQL error code 1064 is a syntax error. This means the reason there’s a problem is because MySQL doesn’t understand what you’re asking it to do.




<h2> Switch to SQL Editor</h2>

– You should specify the classicmodels database before writing SQL statements using the following command:

USE db_name;




The <a href="https://dev.mysql.com/doc/refman/8.0/en/use.html">USE</a>statement tells MySQL to use the named database as the default (current) database for subsequent statements. This statement requires some privilege for the database or some object within it.




2.1 List the product name and quantity in stock of all products that classified in the “Classic Cars” product line (กลุ่มของสนิ คา้/ผลติ ภณั ฑ์) and their buy prices are more than 80.

— Capture the SQL statement + Result Screen and place here




2.2 List the customer name, city and country of all customers who live in the country named: Japan, Germany or Canada. Sort the results in descending order by country and ascending order by customer name.




2.3 List the order number and the total amount of sales for all orders. Name the total amount of sales column to “total_amount”.




2.4 List the order number and the total amount of sales of all orders that their total amount of sales is more than 55000. Name the total amount of sales column to “total_amount”.




2.5 List the customer name and the number of sales orders of all customers whose name start with the letter ‘D’. Name the number of sales orders column to “num_orders”.




2.6 List the customer name, the sales rep employee last name, and the check number of all customers who made the payment in year 2005. Name the sales rep employee last name column to “salesempname”.




2.7 List the manager last name (the employee who were reported to) and the number of employees of all managers. Name the manager last name and the number of employees columns to “mgrname” and “num_emp”, respectively.




2.8 Create your own question and the answered SQL statement should have SELECT,         FROM, WHERE, GROUP BY and HAVING clauses.




2.9 Create your own question and the answered SQL statement should have SELECT,         FROM 3 tables, WHERE and ORDER BY clauses.