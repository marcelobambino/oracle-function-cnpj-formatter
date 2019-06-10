# Oracle Function CNPJ Formatter using RegExp

Simple function that format CNPJ using RegExp.

# How to use

Run the CNPJ_FORMATTER.sql file to create the function on your database.

Then you can test with the command below:

<pre>
<code> select CNPJ_FORMATTER(22308268000128) as CNPJ from dual; </code>
</pre>

Output:
<pre>
<code> 22.308.268/0001-28 </code>
</pre> 
