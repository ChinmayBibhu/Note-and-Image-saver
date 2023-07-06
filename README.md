# Speech-To-Text
It's a simple web page hosted locally on xamp apache server. The web page is for creating and saving notes as well as images. Speech to text functionality is also provided in this web page. Completely based on PHP, PDO is used instead of Mysql for database connection.
If you want to use this project, do the following:

step1: Download and install xampp
s2: open the xamp control, start the apache, mysql server
s3: then open your browser (Chrome is recommended, don't use brave)
s4: go to localhost/phpmyadmin
s5: create new databse, name it as "notes".
s6: Confirm the data in db/conn.php. make changes accordingly, but generally, there won't be any changes to do
s7: in the database "notes" you created, create two tables- "text_note" and "images"
s7: in table "text_note" add these following coloumns respectively: "Sr No" (this is the primary key), "Date", "Title", "Note"
s8: Just confirm the table nams, and the column names from db/crud.php file.
s9: When you download this project as zip file, extract the file in xamp/htdocs folder (this is important, make sure you are in htdocs directory)
s10: in your chrome browser, go to localhost/Mynotes/index.php and you are ready to go
