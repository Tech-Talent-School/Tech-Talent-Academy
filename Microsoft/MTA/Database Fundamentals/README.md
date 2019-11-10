## MTA DATABASE FUNDAMENTALS | EXAM 98-364

**[Exam Details](https://www.microsoft.com/en-us/learning/exam-98-364.aspx)**

### **Prerequisites** 

- Install **SQL Server 2017 Express** Edition (Free) | [DOWNLOAD](https://www.microsoft.com/en-us/sql-server/sql-server-editions-express)
    - Choose the **Basic** Install
- Install **SQL Server Management Studio (SSMS)** | [DOWNLOAD](https://docs.microsoft.com/en-gb/sql/ssms/download-sql-server-management-studio-ssms)
    - [Introduction to SQL Server Management Studio (Video: 8 min)](https://www.youtube.com/watch?v=2WX32qWiFfw)

- Download and Import (Attach) the AdventureWorks 2012 sample database | [DOWNLOAD](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks2012/adventure-works-2012-oltp-data-file.mdf)

- Optional Download of SQL Server 2017 (180 Day Trial) | [DOWNLOAD](https://www.microsoft.com/en-us/sql-server/sql-server-downloads#)

- Enroll in the [Developing SQL Databases](https://www.edx.org/course/developing-sql-databases) EdX course which will be used as a complementary source of study material. 

### SYLLABUS

- Watch **Module 1**: [Introduction to Core Database Concepts (30 min)](https://openedx.microsoft.com/embed_player/block-v1:Microsoft+47076_DEU+2018_T3+type@azure_media_services+block@8ae67d1aec9a4061bda5ed3c50eb63a0) | [YouTube version](https://www.youtube.com/watch?v=GdeaqBCR5PQ&list=PLIoX3-mcY80hub9r9D9_ltMFW6mdRLLTw&index=2&t=0s)  

    - **Module Description:** Define databases, example of relational database tables, and introduce common database terminology

    - <details id="module1-video-contents">
        <summary>Video Contents</summary>
        <ul>
        <li>Course Modules [02:20]</li>
        <li>Core Concepts [03:30]</li>
        <li>Introduction to DB [05:20]</li>
        <li>Relational DBs [08:20]</li>
        <li>Common Terms [10:45]</li>
        <li>Database Management System [10:45]</li>
        <li>Database Server [12:30]</li>
        <li>SQL Management Studio [15:36]</li>
        <li>SSMS Demo [16:27]</li>
        <li>Small talk about Adventure Works 2012 DB [18:30] and about SQL Server Express [20:10]</li>
        <li>SSMS Demo basic query [20:58]</li>
        <li>Short Q&A: Schema [24:40] Data Modelling [25:26]</li>
        <li>Summary [27:50]</li>
        </ul>  
      </details>

    - Read: [Basic Information about Databases](https://docs.microsoft.com/en-us/sql/relational-databases/databases/databases?view=sql-server-ver15)
    
    - <details>
      <summary>
          <a href="https://www.youtube.com/watch?v=-mVDfFDWcqg">Microsoft MTA Database Administration Fundamentals (26 min)</a>
      </summary>
          <strong>A quick overview of the following concepts:</strong>
          <ul>
            <li>Understand how data is stored in tables</li>
            <li>Understand columns and fields</li>
            <li>Understand rows and records</li>
            <li>What is a database</li>
            <li>What is a DBMS</li>
            <li>What is a Table</li>
            <li>What is a Query</li>
            <li>What is an Index</li>
            <li>What is a Database Server</li>
            <li>How is data stored</li>
            <li>Types of Databases</li>
            <li>What is a relational database?</li>
          </ul>
    </details>
    

- Watch **Module 2**: [Relational Concepts: (50 min)](https://openedx.microsoft.com/embed_player/block-v1:Microsoft+47076+2018_T3+type@azure_media_services+block@4f5faa408afa472cb1537046f8575259) | [YouTube version](https://www.youtube.com/watch?v=JHUfFyioVQw&list=PLIoX3-mcY80hub9r9D9_ltMFW6mdRLLTw&index=2)

    - **Module Description:** Normalization, referential integrity and constraints

    - <details id="module1-video-contents">
        <summary>Video Contents (Waiting for reviewers...)</summary>
        <ul>
        <li>Course Modules</li>
        <li>Normalization [01:42]</li>
        <li>(Waiting for reviewers...)</li>
        </ul>  
      </details>

    - <details id="normalization">
        <summary><strong>Normalization</strong></summary>
        <p>
        <ul>
           <li><a href="https://www.youtube.com/watch?v=UDFRhj_K508">How to do Database Normalization | 22 min</a></li>
         <li><a href="https://courses.edx.org/courses/course-v1:Microsoft+DAT251x+3T2018/courseware/5241e25a-45c2-52a9-df7a-a1621e919280/4794d76a-6a83-b553-09c2-5c27d47f4119/1?activate_block_id=block-v1%3AMicrosoft%2BDAT251x%2B3T2018%2Btype%40vertical%2Bblock%403488a9ea-d4c5-7a5f-32f3-248cf49c5e7d">Why Normalization (Video) | 7 min</a></li>
         <li><a href="https://courses.edx.org/courses/course-v1:Microsoft+DAT251x+3T2018/courseware/5241e25a-45c2-52a9-df7a-a1621e919280/4794d76a-6a83-b553-09c2-5c27d47f4119/2?activate_block_id=block-v1%3AMicrosoft%2BDAT251x%2B3T2018%2Btype%40vertical%2Bblock%40b5b2a18e-bfea-f81d-41a8-a300f00adf07">Getting to First Normal Form (1NF) (Video) | 3 min</a></li>
         <li><a href="https://courses.edx.org/courses/course-v1:Microsoft+DAT251x+3T2018/courseware/5241e25a-45c2-52a9-df7a-a1621e919280/4794d76a-6a83-b553-09c2-5c27d47f4119/3?activate_block_id=block-v1%3AMicrosoft%2BDAT251x%2B3T2018%2Btype%40vertical%2Bblock%40de8234b6-cc5c-a9dd-fced-97f26850e1a8">Getting to Second and Third Normal Form (2NF, 3NF) (Video) | 10 min</a></li>
        </ul>
        </p>
    </details>

    - <details id="referential-integrity">
        <summary>Referential Integrity</summary>
        <ul>
        <li><a href="https://www.youtube.com/watch?v=pCZwo99uHXQ&list=PLsrZV8shpwjM71pXuhXu9dSM2QL5kZIoh&index=14">SQL Database Fundamentals: Referential Integrity</a></li>
        </ul>
    </details>

- Watch **Module 3**: [Creating Databases and Database Objects: (50 min)](https://openedx.microsoft.com/embed_player/block-v1:Microsoft+47076+2018_T3+type@azure_media_services+block@fd16d42768ee47de8e1294191fb3ed07) | [YouTube version](https://www.youtube.com/watch?v=tKGCeXRyBmk&list=PLIoX3-mcY80hub9r9D9_ltMFW6mdRLLTw&index=3)

    - **Module Description:** Data types, database objects, DDL statements and creating scripts

    - <details id="creating-tables">
        <summary>Creating and Updating Tables</summary>
        <ul>
        <li><a href="https://www.youtube.com/watch?v=D6DDgRjwUYU&list=PLsrZV8shpwjM71pXuhXu9dSM2QL5kZIoh&index=10">SQL Database Fundamentals: 03.1 Demo: Creating Tables</a></li>
        </ul>
    </details>

    - <details id="data-types">
        <summary>Data Types</summary>
        <ul>
        <li><a href="https://www.youtube.com/watch?v=_yzzn0fUmi8&list=PLsrZV8shpwjM71pXuhXu9dSM2QL5kZIoh&index=11">Data Types (23 min)</a></li>
        <li><a href="https://www.youtube.com/watch?v=9KB2U5eYQeM&list=PLsrZV8shpwjM71pXuhXu9dSM2QL5kZIoh&index=12">Working with Data Types (10 min)</a></li>
        </ul>
    </details>

- Watch **Module 4**: [Using DML Statements: (50 min)](https://openedx.microsoft.com/embed_player/block-v1:Microsoft+47076+2018_T3+type@azure_media_services+block@bdd0cbd838ec4e5db8b20b6d88d31ad5) | [YouTube version](https://www.youtube.com/watch?v=oTut_4zXXWI&list=PLIoX3-mcY80hub9r9D9_ltMFW6mdRLLTw&index=4)     

    - **Module Description:** DML statements, using the SELECT statement, using INSERT, UPDATE and DELETE to manage data, indexes and triggers

- Watch **Module 5**: [SQL Server Administration Fundamentals: (50 min)](https://openedx.microsoft.com/embed_player/block-v1:Microsoft+47076+2018_T3+type@azure_media_services+block@7af972cf1d774196954f918ba6be08be) | [YouTube version](https://www.youtube.com/watch?v=dRN42PI1tBc&list=PLIoX3-mcY80hub9r9D9_ltMFW6mdRLLTw&index=5)

    - **Module Description:** SQL Server security, securing database and objects, performing database backups and database restores
    - <details>
        <summary>Video Contents</summary>
        <ul>
        <li>Backup Database [ 27:54 ]</li>
        <li>Restore Database [ 29:45 ]</li>
        </ul>  
      </details>

- [YouTube Playlist (Microsoft Video Courses)](https://www.youtube.com/watch?v=81PWjzfxerE&list=PLc5CkqRjW1BRX-5TI3zT2kJBiq5Uadlz6)
- [YouTube Playlist (Alternative)](https://www.youtube.com/playlist?list=PLIoX3-mcY80hub9r9D9_ltMFW6mdRLLTw)

### RESOURCES

- [Relational Databases](https://docs.microsoft.com/en-us/sql/relational-databases/databases/databases?view=sql-server-ver15)

- [SQLFiddle](http://sqlfiddle.com/): A tool for easy online testing and sharing of database problems and their solutions.   

- [Microsoft SQL Database Fundamentals](https://www.youtube.com/playlist?list=PLc5CkqRjW1BQmPrZXw0i2BRANoM4hCwtz)

### TERMINOLOGY

<details>
    <summary>Database (DB)</summary>
    <p>A database is an organized collection of data, typically stored in electronic format. It allows you to input, manage, organize and retrieve data quickly.</p>
    <p>Traditional databases are organized by records (rows), fields (columns) stored in tables which are stored in the database files.</p>
</details>

<details>
    <summary>DBMS | DataBase Management System</summary>
    <p>Used by users to access the data stored in database files and perform administrative tasks on the databases and objects contained within the database. DBMS can also provide additional functionality like reporting services to help you create, deploy, and manage reports for your organization.
    </p>
</details>

<details>
    <summary>DDL | Data Definition Language</summary>
    <p>DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database.</p>
    <p><strong>Commands: </strong>CREATE, DROP, ALTER, TRUNCATE, COMMENT, RENAME, etc.</p>
    <p><a href="https://www.geeksforgeeks.org/sql-ddl-dql-dml-dcl-tcl-commands/">Reference</a></p>
</details>

<details>
    <summary>DML | Data Manipulation Language</summary>
    <p>The SQL commands that deals with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements.</p>
    <p><strong>Commands: </strong>INSERT, UPDATE, DELETE, etc.</p>
    <p><a href="https://www.geeksforgeeks.org/sql-ddl-dql-dml-dcl-tcl-commands/">Reference</a></p>
</details>

<details>
    <summary>Entity</summary>
    <p>An entity may be defined as a thing capable of an independent existence that can be uniquely identified. An entity is an abstraction from the complexities of a domain. When we speak of an entity, we normally speak of some aspect of the real world that can be distinguished from other aspects of the real world.</p>
    <p>An entity is a thing that exists either physically or logically. An entity may be a physical object such as a house or a car (they exist physically), an event such as a house sale or a car service, or a concept such as a customer transaction or order (they exist logically—as a concept).</p>
    <p>Although the term entity is the one most commonly used, following Chen we should really distinguish between an entity and an entity-type. An entity-type is a category. An entity, strictly speaking, is an instance of a given entity-type. There are usually many instances of an entity-type. Because the term entity-type is somewhat cumbersome, most people tend to use the term entity as a synonym for this term.</p>
    <p>Entities can be thought of as nouns. Examples: a computer, an employee, a song, a mathematical theorem, etc.</p>
    <p><a href="https://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model">Reference</a></p>
</details>

<details>
    <summary>Orphans</summary>
    <p>Records in a Related (child) table that reference records that do not exist in the primary (parent) table <a href="https://youtu.be/oJh5pNhoOLE?t=21">(See video)</a></p>
</details>

<details>
    <summary>RDBMS | Releational DataBase Management System</summary>
    <p>A software system designed to allow the definition, creation, querying, and updating of data stored in relational databases.<br>A few examples of RDBMS include: Microsoft SQL Server, Microsoft Access, and MySQL.</p>
</details>

<details>
    <summary>Relationship</summary>
    <p>A relationship captures how entities are related to one another. Relationships can be thought of as verbs, linking two or more nouns. Examples: an owns relationship between a company and a computer, a supervises relationship between an employee and a department, a performs relationship between an artist and a song, a proves relationship between a mathematician and a conjecture, etc.</p>
    <p><a href="https://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model">Reference</a></p>
</details>

<details>
    <summary>Relational DataBase(s)</summary>
    <p>	A relational DataBase is a collection of tables where the tables are able to talk to each other.<br>In a relational DB the collection of tables of data is formally described and organized according to the relational model. Each table must identify a column or group of columns, called the PRIMARY KEY, to uniquely identify each row. 
</p>
</details>

<details>
    <summary>SSMS | SQL Server Management Studio</summary>
    <p>A GUI used to browse, select and manage SQL Server instances and any of the objects within these SQL Server instances.</p>
</details>

<details>
    <summary>Table</summary>
    <p>A database table is a collection of rows and columns that is used to organize information about <strong>a single topic</strong>. Each row within a table corresponds to a single record and contains several attributes that describe the row. Example of a table stored in a database:</p>
    <table>
        <thead>
            <tr>
                <th>EmployeeID</th>
                <th>LastName</th>
                <th>FirstName</th>
                <th>Department</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>100</td>
                <td>Smith</td>
                <td>Bob</td>
                <td>IT</td>
            </tr>
            <tr>
                <td>101</td>
                <td>Jones</td>
                <td>Susan</td>
                <td>Marketing</td>
            </tr>
            <tr>
                <td>102</td>
                <td>Adams</td>
                <td>John</td>
                <td>Finance</td>
            </tr>
        </tbody>
    </table>
</details>
