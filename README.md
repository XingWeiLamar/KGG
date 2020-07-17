# KGG

Knowledge Graph Processor (KGP)
KGP is a simple tool to generate knowledge graph triplets list from the input csv file and replace each entity with a unique index number. 

Run the program by enter “python kgp.py” in the terminal.
Please follow the instruction and enter all the required input information
We use yelp.csv as an example

1.	Enter the file path of yelp.csv
   D:/kgp/yelp.csv
   (Terminal will display all the columns name of the file)
   ![1_meitu_1](https://user-images.githubusercontent.com/67215019/87758829-ce836a80-c7d2-11ea-854f-cf1bcff41636.jpg)
   ![2_meitu_2](https://user-images.githubusercontent.com/67215019/87758858-e0fda400-c7d2-11ea-96cd-67b3eb8b0c68.jpg)

2.	The program will require user to enter the columns number of entities one by one for the KG triplets list
   we enter 9 business_id,  41 city, 20 categories 
  ![3_meitu_5](https://user-images.githubusercontent.com/67215019/87762791-4f456500-c7d9-11ea-9807-0734da89c4a5.jpg) 

3.	Enter the relation name and the two entity column numbers on the left and right in the triplet 
  ![4_meitu_6](https://user-images.githubusercontent.com/67215019/87762796-510f2880-c7d9-11ea-886c-01420df91e67.jpg)
4.	Enter the path of item index file and path of relation index file
   ![5_meitu_7](https://user-images.githubusercontent.com/67215019/87762801-52405580-c7d9-11ea-9f1e-62557bcacf04.jpg)
5.	Enter the type of output KG file(txt or csv) and the path of the output KG file. 
   ![6_meitu_8](https://user-images.githubusercontent.com/67215019/87762807-54a2af80-c7d9-11ea-9778-98cccbab6e69.jpg)
6.	Generate rating file. 
7.	Enter the columns numbers that contains user id, business name and rating score
   ![7_meitu_9](https://user-images.githubusercontent.com/67215019/87762812-566c7300-c7d9-11ea-9d0b-50d014043a2c.jpg)
8.	Enter the path of user index file
   ![8_meitu_10](https://user-images.githubusercontent.com/67215019/87762818-579da000-c7d9-11ea-8e1e-c150ce012fa5.jpg)
9.	Enter the type of output rating file(txt or csv) and the path of the output rating file.
   ![9_meitu_11](https://user-images.githubusercontent.com/67215019/87762830-59676380-c7d9-11ea-9ab8-efd4f319860d.jpg)

Transfer rating file for explicit feedback to implicit feedback.
 
 Run the program by enter ”python irt.py ”
1.	Follow the instruction enter the path of kg file and the path of rating file.
2.	Enter the output paths.

