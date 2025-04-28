# infs3200-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [INFS3200 Assignment 1 Solved](https://www.ankitcodinghub.com/product/infs3200-advanced-database-systems-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119976&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;INFS3200 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

Introduction

Important Notes:

1. As UQ has provided the Lab environment for this assignment, you don’t need to install the required software systems on your own machine. The software environment problems on your own computer machine cannot be used to ask for extension of submission.

3. You should complete Prac 3 before working on the coding part of this assignment (i.e., Part 4 of this assignment). Although the assignment is independent to the three practicals, the code introduced in Prac 3 can be a starting point of this assignment as the tasks are similar.

Submission Requirements:

Please include all your answers in a word/pdf document. Pack the documents with your code folder (which contains at least “src” and “data” folders, shown as below) into a .zip/.rar file and submit it to the Blackboard INFS3200 course Website. The name of both the zip file and the document should contain your student ID, your name and “Assignment”, shown as follows:

Please format your document nicely, in terms of consistent font, font size and spacing. The answers are suggested to follow the below structure (No need to repeat questions if not necessary, fonts and spacing are not limited):

…

Part 1.

Question 1: Your answers…

Question 2: Your answers… Part 2.

…

Preliminary: Dataset Description

In this assignment, we have four datasets about book information from four different sources. The data schemas are listed below:

Book1 (id, title, authors, pubyear, pubmonth, pubday, edition, publisher, isbn13, language, series, pages)

Book2 (id, book_title, authors, publication_year, publication_month, publication_day, edition, publisher_name, isbn13, language, series, pages)

ProductDimensions, SalesRank, RatingsCount, RatingValue, PaperbackPrice, HardcoverPrice, EbookPrice, AudiobookPrice)

Book4 (ID, Title, UsedPrice, NewPrice, Author, ISBN10, ISBN13, Publisher, Publication_Date, Pages, Dimensions)

Read the above schemas carefully and understand the meaning of the attributes. If you don’t know the meaning of a certain attribute, check the data under it or Google its meaning (especially for some abbreviations, like ISBN). Answer the following questions based on your understanding.

(1) Write an SQL query “Find the top 15 books that have the highest ratings and 10 books that have the lowest ratings, return their ranks (sorted in descending order), titles, publishers and number of pages”.

(2) Which table schema(s) is/are used to answer the above query?

• Find all books whose publisher name is “XXX” (or among multiple publishers), return their book titles and author info.

• Find all books that are published in a given year, return their book IDs, languages,number of pages, HardcoverPrice and EbookPrice.

Answer the following questions:

Fragment 1: pages ≤ 200

Fragment 2: 200 &lt; pages ≤ 600

Fragment 3: pages &gt; 800

Is this set of predicates valid? If so, please explain (using plain English) the insertion process if we want to insert a new record into Book1. If not, please generate a valid predicate set using minterm predicates (show the calculation process). Also, explain the insertion process for a new record after the valid predicate set is made.

In this part, we design a Data Warehouse on book sales w.r.t. the Book1, Book2, Book3, and Book4 datasets. Particularly, we need to use data from the given assignment datasets and create a Data Warehouse Schema. The designed Data Warehouse will contain summary data, such as the total sales of each publisher, for each day and each language. The following shows just an example:

Day Publisher Language Sales

07/15/1984 AAAI Press English 11

11/19/2012 Springer London Spanish 5

Question 3: Design a Data Warehouse Schema that can accommodate the above example, answer the following questions:

(1) [1 mark] Show the schema and point out the dimensions and fact table. Given that we have a dimension table for each dimension and there are 4000 records in the fact table. Among all dimension tables and the fact table, which table has the most records? Why?

Question 4: Now we want to the create bitmap indices for the given model:

“Language” only contains two, which are all shown in the above example. Please create bitmap indices for both “Publisher” and “Language”.

Given that the data warehouse loads data from the above four sources (Book 1,2,3,4), you are asked to integrate their data and address various data quality issues. In this part, those database sources (i.e., owners) only give you their schemas (shown in Preliminary part), and you are asked to design an integrated schema based on the given schemas (i.e., the data records within tables Book 1,2,3,4 are supposedly not available for you at this stages).

Question 5: Now you define a global schema (using the approach namely, Global as a View) which can integrate data from all four sources.

Now assume you are provided with the actual data from each source, namely “Book1.csv”,

“Book2.csv”, “Book3.csv” and “Book4.csv” (see the Assignment provided datasets). As it is very common that the same book is recorded by different sources, it is crucial to identify the redundant information by merging and eliminate the duplicated records during the data integration process, which relies on the data linkage techniques to be used. In this regard, we provide a human-labelled gold-standard dataset (refer to Prac 3 Part 2.2 for more information about gold-standard), named as “Book1and2_pair.csv”, which lists all correct matchings between Book1 and Book2. It will be used in the following tasks. Its schema is as follows:

Book1and2_pair (Book1_ID, Book2_ID)

In a CSV file, you need to note that the attributes are separated by comma (,). If two commas appear consecutively, it means the value in the corresponding field between two commas is NULL (i.e., absent). Furthermore, if an attribute field contains comma naturally, the field will be enclosed by a double quote (“”) to differentiate the actual comma notation inside attribute from the outside comma separator. For example, a record in Book2 is as follows:

1725,Informix Unleashed,”John McNally, Jose Fortuny, Jim Prajesh, Glenn Miller”,

97,6,28,1,Sams,9.78E+12,,Unleashed Series,1195

According to Book 2 schema, we can infer the following fields:

id=1725, book_title=Informix Unleashed, authors= John McNally, Jose Fortuny, Jim Prajesh, Glenn Miller,

… isbn13=9.78E+12 language=NULL, series=Unleashed Series, pages=1195.

Here, since there are commas in “authors” field, the whole field is enclosed by a notation of double quotes. Also, since there are two consecutive commas before “Unleashed Series”, it means that the language is NULL.

In this part, you are asked to answer the following questions by writing code to complete the tasks (if “code required” is specified) and provide your answers based on the code results. Please store all the code you wrote during this part and submit them to Blackboard Course Website as a part of your assignment submission.

Question 6: Sample records from “Book3.csv” to measure its data quality:

(1) [1 mark] By sampling the records whose id is the multiple of 100 (i.e. 0, 100, 200, 300, …), how many records are there in the sample set (code required)?

(2) [1 mark] Among the samples found in Question 6-(1), how many fields containing NULL values are presented (code required)?

Question 7: Perform data linkage on Book1 and Book2 using the methods mentioned in Prac 3:

a. “Richmond Shee, Kirtikumar Deshpande and K. Gopalakrishnan;”

b. “K. Gopalakrishnan, Kirtikumar Deshpande, and Richmond Shee”

Which distance function is more likely to regard them as similar (between two approaches of edit distance and Jaccard distance)? And Why?

— The End of Assignment —
