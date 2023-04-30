Download Link: https://assignmentchef.com/product/solved-eb103a-assignment-7
<br>
<ul>

 <li>This is the second of two assignments dealing with SQL. Both assignments use the same small database with very 56 similar instances.</li>

 <li>2 Assignments</li>

 <li>(a) You are already supposed to know how to run SQL queries/commands on the Oracle sys59             tems at CIMS. You were asked to familiarize yourself with and follow the instructions in</li>

 <li><sub>pdf</sub>.</li>

 <li>You were asked to do that earlier in order to save you time while working on this homework. 62 So it is assumed that you know how to do that.</li>

 <li>(b) Look at the files ER07.drawio and relational07.architect. They will help you understand the</li>

 <li>database schema defined in the files script07.sql and dataSetupScript07.sql. These files fully 65 specify the application.</li>

</ul>

66                  (c) Read script07.sql and dataSetupScript07.sql carefully. They both define and create the sample 67                   database and script07.sql serves as the placeholder for putting in your solutions.

68 Look carefully over ANSWER0 there. It shows you how to insert a result of a query into an empty 69 table. It also uses the temp table TEMP0, just to demonstrate the usage of temp tables.

<ul>

 <li>(d) Input your queries into script07.sql after doing what is requested in Item 1e of Section 2.2.</li>

 <li>For each query, <em>unless something else is required by the query </em>make sure to</li>

 <li>Remove duplicates from the answer (unless requested otherwise); that’s what DISTINCT does</li>

 <li>Sort the result in ascending order (unless requested otherwise); that’s what ORDER BY does</li>

 <li>This is <em>extremely important </em>to make the grading more manageable.</li>

 <li>So, for example, assuming that you are going to select a and b and rename b as c, you should actually 76 <em>explicitly </em>use:</li>

 <li>SELECT DISTINCT a, b AS c</li>

 <li>…</li>

</ul>

<h2>79                                                            ORDER BY a ASC, c ASC;</h2>

<ul>

 <li><em>Do not rely the on default removal of duplicates and sorting order.</em></li>

 <li>You may use temporary tables. If you choose to do that, use tables TEMP1, TEMP2, …, TEMP20.</li>

 <li>(e) Replace “zk1” in script07.sql with your NetID.</li>

 <li>(f) Do not remove the existing sample query.</li>

 <li>(g) Notice that the script07.sql internally executes dataSetupScript07.sql followed by the queries 85 you write in script07.sql, and produces a spool file spool07.txt that contains just the details of the 86 queries specified in the script script07.sql. The spool should only contain the details while running 87 sql and not the data setup script. The spool file created will be a part of the submission. 88 Do not be concerned that there are more placeholder ANSWERs that the queries that you are supposed</li>

 <li>to produce.</li>

 <li>For reference, spool07.txt corresponding to the given script07.sql (with one sample query) is</li>

 <li></li>

 <li>The requested queries are listed below. Your answers must work for every instance of</li>

 <li>the database and not only for the specific instance provided. Do not use subqueries to 94 produce your output. The tables are named AnswerX, where “X” stands for the item number below. 95 So, as the first item is item number 1, the first table is Answer1.</li>

 <li>Produce table AnswerX(RegNumber, TIN) that lists all the big companies that do not have a</li>

 <li></li>

 <li>Produce table AnswerX(TIN, SalaryRatio) that lists the TIN of the big companies that spend more 99 than 10 percent of their value on manager salary.</li>

</ul>

100                  3. Produce table AnswerX(TIN) that lists the TIN of companies that work in at least 3 domains and 101                 have a TIN greater than or equal to 20000000.

<ul>

 <li>Your answer should work if the question were phrased with 500 instead of 3 if you replace 3 by 500</li>

 <li>in your answer.</li>

 <li>Produce table AnswerX(TIN) that lists the companies that work at least in all the domains that 105 company with TIN ‘99448276’ works in.</li>

</ul>

106                  5. Write and execute a query to delete from table Company the company with TIN ‘74939103’. Please 107      do what’s requested in Item 1h of Section 2.2.

108 6. Company ‘95499546’ has hired a new manager with PersonalName ‘Mickey’, FamilyName ‘Aldrin’with 109 salary 100000. Write and execute a query to add/change the name of the store’s manager in our 110 records wherever necessary.

<ul>

 <li>Please do what’s requested in Item 1h of Section 2.2.</li>

 <li>Company ‘35983220’ has made huge mistakes in the recent past, and lost a lot of its value. As 113 a result, they have to fire their current manager. They would now be a small company. Write 114 and execute a query to remove the company from big companies, and make the company a small</li>

 <li></li>

 <li>Please do what’s requested in Item 1h of Section 2.2.</li>

 <li>Write and execute a query to create a record of company with TIN ‘74939103’ helping company 118 with TIN ‘90309251’.</li>

 <li>Please do what’s requested in Item 1h of Section 2.2.</li>

 <li>MySQL does not have a very useful operator we studied: MINUS. Review the definition of MINUS</li>

 <li>from Unit 05.</li>

 <li>Do not use MINUS for this question. Produce table AnswerX(A, B), which is R MINUS S. Use 123 LEFT OUTER JOIN in your answer. Tables R and S are defined in the script.</li>

</ul>

124 (h) Examine the database and fill out text07.txt. For each “AnswerX” (of course replacing “X” with the 125 correct value), supply the information requested between the two square brackets, in [ ]. The form is

126                  clear but to elaborate it is asking you to specify which tables (if any) were changed and why. You may 127      get an error message pertaining to this question. If you do get it,

<ul>

 <li>copy the error into text07.txt, and</li>

 <li>explain in <em>your own words what the error was</em>, and do not just copy the message that Oracle gave 130 you, though you can also quote it. You may consult the Web, if you like.</li>

 <li>If you do not get an error, state so.</li>

 <li>3 What to submit</li>

 <li>Please upload 3 files, named <em>exactly </em>as specified and in the format <em>exactly </em>as specified.</li>

 <li>script07.sql, the script with your answers</li>

 <li>spool07.txt, the resulting spool file</li>

 <li>text07.txt, the file requested in Item 1h of Section 2.2</li>

</ul>