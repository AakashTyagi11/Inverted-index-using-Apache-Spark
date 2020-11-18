The project exhibits the functionality of the page-rank algorithm on 20,000 HTML input files using Apache spark (Map-reduce) and by computing cosine similarity of each file.


inverted-index-pyspark-post.ipynb :

- Performs mapper and reducer tasks for approx 20,000 HTML files (input files).

- generates inv_idx.txt and mag_doc.txt files as the final output of this python file.

- These text files hold the values required for computing cosine similarity of each file.

----------------------------------------------------------------------------------------------------------

CSC_502_project_DB_+_Interface.ipynb : 

Database: Contains code for generating tables out of text files generated in the above step (using sqlite3).

Interface : Contains HTML components like a text box to enter a search query, a search button, and a text area to display the results.

Onclick Functionality: a function that computes the cosine similarity on the click of a search button that takes the enter search query as input and returns the most relevant document(among the input HTML files) to the search query.

---------------------------------------------------------------------------------------------------------

Code_execution
![Result](https://github.com/AakashTyagi11/Inverted-index-using-Apache-Spark/blob/master/Search%20%26%20result.JPG?raw=true)

--------------------------------------------------------------------------------------------------------
