
## Types of NoSql Databases:-
- Document based database.
- Key value stores.
- Column oriented databases.
- Graph based databases.

### Document based databases:-
![Document based database image](https://hevodata.com/learn/nosql-databases-and-its-types-a-guide/#lg=1&slide=0)
- It is a nonrelational databse which stores data in the form of documents rather than in form of rows and columns in a table like in Sql.
- The data format to store data in it is JSON(JavaScript Object Notation), XML(Extensible Markup Language) or BSON(Binary JavaScript Object Notation) documents.
- It allows developers to change thier database structure dynamically according to their needs.
- Example of Document based databases are:- MongoDB, Apache CouchDB.

 Uses:-
- Because of their flexibility in structure, they can be used to design a database for a social media or contact management system where no of data is not fixed.
- They are easy to update so they can be used in places where we need frequent updates.

### Key-value stores:-
![Key-value Database](https://images.datacamp.com/image/upload/v1656083463/Key_Value_Database_No_SQL_4_7ca269cb7a.png)
- It is most simple nosql database which stores data in the database in the form of a key-value pair.
- It is like a table of two columns where first column is the key and the second column is the value.
- Key and value can be of different datatypes, like int,float,double,objects etc independent of each other.
- Example is DynamoDB.

 Uses:-
 - They can be used where simple data needs to stored temporarily, like shopping cart or in cache.

### Column-Oriented Databases:
![Column-Oriented Databases](https://res.cloudinary.com/hevo/image/upload/c_scale,w_448,h_318/f_auto,q_auto/v1686069226/hevo-learn-1/V7KQ9mQD872ll4mxtwVZWNaHNXvhloc_Kro2vT1MBWXwZMqQJ_wE8x1d84HFKIm94k5fN3x5223-9aKxkkVR4jVbx4mTZtpYMIcNOSAC8ZwwsPW0e_itZlewtK_VxpXQgdT1pi36.png?_i=AA)
- Data is stored in a set of columns known as column families.
- Whenever user wants to run query on a small number of columns, he can run particularly on those columns.
- It is working is based on BigTable paper by Google.
- Example is Cassandra databse.

 Uses:-
 - Due to their scalability and compression naure,  they are mostly used for analytical workloads such as business intelligence, data warehouse management,

  ### Graph based Databases:-
  ![Graph based Database](https://images.datacamp.com/image/upload/v1656083461/Graphic_Node_Database_No_SQL_6_7194bb4710.png)
  - It focuses on relationship between the elements.
  - Each element/data is stored in a node, and that node is linked to another data/element.
  - Connection between two nodes ic called link or relationship.
  - Example is OrientDB.
 
 Uses:-
 - They can be used for mining data in social media as each node is conected.
   

## References:-
- [Reference 1 :- Gfg](https://www.geeksforgeeks.org/types-of-nosql-databases/).
- [Reference 2](https://hevodata.com/learn/nosql-databases-and-its-types-a-guide/#s1).
- [Reference 3](https://www.datacamp.com/blog/nosql-databases-what-every-data-scientist-needs-to-know).

      

  
