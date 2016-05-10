# BMS-Test
PLEASE NOTE: The content of this file and all test files included are properties of BMS and for your eyes only. We kindly request that you do not share/give any files or contained information to anyone else.

Hi!

You can choose to work on any one of the questions below, or more as time permits:<br>
<ol>
  <div style="display:none"><li><a href="#d3">Perl text parsing & implement d3.js visualization</a></li></div>
  <li><a href="#r">R</a></li>
  <li><a href="#java0">Java Question</a></li>
  <li><a href="#java">Java Question 1</a></li>
  <li><a href="#java1">Java Question 2</a></li>
  <li><a href="#p">Perl/Python - revcomp CDS</a></li>
  <li><a href="#p1">Perl/Python - longest ORF</a></li>
  <div style="display:none"><li><a href="#m">MySQL + SQL</a></li></div>
  <div><li><a href="#j">Javascript - phone # validator</a></li></div>
  <div style="display:none"><li><a href="#j1">Javascript - Ajax</a></li></div>
</ol>

<b>Note</b>:
<ul>
  <li>Tools needed are:<br>
    <pre>
      R: Version 3.2.x or later
      Perl: Version 5.8.x or later
      Python: Version 2.4.x or later
      Bioperl or Biopython: Any version
      Java: Version 1.6.0 or later
      Web browser: current Chrome/Firefox
      Text editor: your favorite
    </pre>
  </li>
  <li>Use search engine as much as you like. If you used external code, then please note it.</li>
  <li>Installation of external open source tools/package or other virus free tools are allowed but please note what you have installed.</li>
  <li>If you encountered unexpected issues please let us know.</li>
</ul>
<hr>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<div id="d3" style="display:none"><b>Perl + d3.js</b> The folowing quetion has three parts and needs the following files:<pre>

./d3.txt

the following urls:

&lt;script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js">
&lt;script src="http://d3js.org/d3.v3.min.js">&lt;/script>

using perl which can be located at:

/apps/sys/bin/perl 


A. Write a parser for the data contained in the tab delimeted file
d3.txt and create an html web page to visualize it using D3.js.

B. Create widgets in the html page above to enable ploting the
data in a scatter plot or bar chart using jQuery.js and D3.js.

C.Create additional widgets to chnage the color of the data points
based on the class of the data points using jQuery.js and D3.js.


</pre></div><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<div id="java0"><b>Java Question</b>: <br>
Read the Tab delimited file "taskDates.txt" and write a file called "dates.sql", which contains insert sql instructions to be run later by using sqlplus.  No need to connect to the database and run.  Just create the dat
es.sql file.

<pre>
Input: taskDates.txt
Columns:
        1. taskid
        2. Date

Output:
each line in the dates.sql output should be

insert into task ( taskid, createtime, user) values ( column1, column2, 'russo' );

taskid( taskid column 1 from taskDates.txt)
createtime(Date column 2 from taskDates.txt)
user(constant "russo" );
Must have the following:

1. Store the data in a hash with taskid as keys and date string as value
2. Iterate through the hash and print out the file with the insert sql string.
3. Open a file for reading using java methods. Open a file, read from file, etc.
4. Write a file using java APIs for writing to a file. Open a file, write to a file, etc.
5. Make count if any taskids are repeated.  Print count to console/stdout.
6. Hardcode the files in java.  Passing as arguments would be best.

</pre>
</div><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<div id="java"><b>Java Question 1</b>: <br>
Say that you want to define a new custom Java class, and have lists of objects of your custom class be sortable by your own custom sort function. How would you define your class to enable it to be sortable? Demonstrate 
by defining a simple "Person" class with fields first name, last name, and age and enable it to be sortable by age. Show how you would sort a list of these Person objects by age.


</div><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<div id="java1"><b>Java Question 2</b>: <br>
Write a Java method that finds "seed" hits in a genomic sequence, similar to how BLAST does. In other words, it takes a String representing a (long) genomic sequence to be searched, another string which is the "seed" to
 find matches of in the genomic sequence (perfect matches or with some limited mismatching positions allowed), and an integer telling how many mismatch positions at max are allowed in the "seed" matches. The method retu
rns all the positions in the genomic sequence where "seed" matches were found. What is the time complexity of your code?

</div><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<div id="r"><b>R Question</b>: The following question requieres the folowing file:<pre>

./expression.txt
./class.txt

A. Given the expression data contained in the file expression.txt and
its sample annotation contained in the file class.txt visualize the
data in a volcano plot


</pre>
</div>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<div id="p"><b>Perl question</b>: Write code to report the reverse complement of the CDS in each sequence (package like Bioperl is allowed).<pre>

The following file has two RNA sequences:

  CAV3_RB1.fa



</pre>
</div><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<div id="p1"><b>Perl question</b>: Write code to find the longest ORF in each of the sequences in the file below (package like Bioperl is allowed).</a><pre>

The following file has two RNA sequences:

  CAV3_RB1.fa

If needed, this file has codon to amino acid mappings:

  CodonTable.txt

</pre><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<div id="m" style="display:none"><b>MYSQL Questions</b></a><pre>

Given a mysql DB with the ER diagram described at http://gaia.hpw.pri.bms.com/html/mysql.html 
answer the questions below.

The mysql database is on host kraken, running on the standard mysql port
   the user login is employees and the database name is employees
   you can use commandline to login, or install free software on your own (let us know which software you installed).

Please construct queries (and write them down) to provide the following:
A. How many total employees?
B. How many male and female employees in each department?
C. What are the names of all the managers and what is their gender?
D. How many employees were hired before year 2000 per department?


</pre></div>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<div id="j"><b>Javascript question</b>: Using the file phonevalidate.html
and optionally any javascript libraries you have to implement a phone
number and zip code validator (and auto-jump). See rules further below.
If you use some JS library, doing a JSfiddle would be better for us to check your result.<pre>

Please enter your JS code in the phonevalidate.html.  Please make sure that:
  1. User can only enter digits into these input boxes (backspace, arrow keys should work fine)
  2. User cannot enter a phone # starting with a 0
  3. When user entered 3 digits in the input boxes "area" or "middle", the input caret should jump to "middle" or "last", respectively
  4. When user entered 5 digits in the input box "zip", the input caret should jump to "zip1"

</pre></div>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<div id="j1" style="display:none"><b>Javascript question</b>: <pre>

1. Read the file ./ht/html/testAXpressAPI.html and ./ht/html/AXpress.js.
2. Give it a test and see if you can retrieve data.  If you can retrieve data, then:
   a. Convert the file urls to hyperlinks.
   b. Extract the file type from the XML returned by the AJAX call and present it alongside the link.
3. If you can't retrieve data, explain why the data can't be retrieved.
</pre></div>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br
><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><b
r><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><
br><br><br><br><br><br>
