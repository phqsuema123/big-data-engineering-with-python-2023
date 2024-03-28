# Big-data-engineering-with-python-2023
Big Data Engineering with Python 2023 course

### Overview
This project involves connecting a database with Cassandra and entering Qur'anic information into the database.

-----

* **Tools**
    * Cassandra
    * Jupyter Lab

* **Installation**
    * Java 8
    * Python v2.7
    * cassandra
    * Python libraries:
        * pandas
        * cassandra
        * re
        * os
        * glob
        * numpy
        * csv
        * matplotlib
        * requests
        * fuzzywuzzy
        * collections
        * nltk

# Methodology

1. **Set up Cassandra**
    * [Install Cassandra](https://phoenixnap.com/kb/install-cassandra-on-windows#ftoc-heading-4)
    * Open Cassandra
        * Can open in terminal or cmd

    ![Cassandra Screenshot](https://github.com/phqsuema123/big-data-engineering-with-python-2023/blob/main/image/Screenshot%202024-03-28%20101429.png?raw=true)

    * Open cqlsh to use Cassandra

    ![Cqlsh Screenshot](https://github.com/phqsuema123/big-data-engineering-with-python-2023/blob/main/image/Screenshot%202024-03-28%20104608.png?raw=true)

2. **Connect Cassandra with Python**
    * `pip install cassandra-driver` to use the cluster module

    ![Install Cassandra Driver Screenshot](https://github.com/phqsuema123/big-data-engineering-with-python-2023/blob/main/image/Screenshot%202024-03-28%20103913.png?raw=true)

3. **Create Keyspace**

    ![Create Keyspace Screenshot](https://github.com/phqsuema123/big-data-engineering-with-python-2023/blob/main/image/Screenshot%202024-03-28%20102116.png?raw=true)

4. **Use Keyspace**

    ![Use Keyspace Screenshot](https://github.com/phqsuema123/big-data-engineering-with-python-2023/blob/main/image/Screenshot%202024-03-28%20102140.png?raw=true)

5. **Create Table**

    ![Create Table Screenshot 1](https://github.com/phqsuema123/big-data-engineering-with-python-2023/blob/main/image/Screenshot%202024-03-28%20102217.png?raw=true)

    ![Create Table Screenshot 2](https://github.com/phqsuema123/big-data-engineering-with-python-2023/blob/main/image/Screenshot%202024-03-28%20102248.png?raw=true)

6. **Extract Data from CSV**

    ![Extract Data Screenshot 1](https://github.com/phqsuema123/big-data-engineering-with-python-2023/blob/main/image/Screenshot%202024-03-28%20102022.png?raw=true)

    ![Extract Data Screenshot 2](https://github.com/phqsuema123/big-data-engineering-with-python-2023/blob/main/image/Screenshot%202024-03-28%20102319.png?raw=true)

7. **Check Table**

    ![Check Table Screenshot 1](https://github.com/phqsuema123/big-data-engineering-with-python-2023/blob/main/image/Screenshot%202024-03-28%20102515.png?raw=true)

    ![Check Table Screenshot 2](https://github.com/phqsuema123/big-data-engineering-with-python-2023/blob/main/image/Screenshot%202024-03-28%20102545.png?raw=true)

8. **Code for Finding the Answers**

    * Code to find Arabic word

    ![Arabic Word Code Screenshot](https://github.com/phqsuema123/big-data-engineering-with-python-2023/blob/main/image/Screenshot%202024-03-28%20102610.png?raw=true)

    * Code for the most similar words

    ![Similar Words Code Screenshot](https://github.com/phqsuema123/big-data-engineering-with-python-2023/blob/main/image/Screenshot%202024-03-28%20102728.png?raw=true)

    * Code to find English word

    ![English Word Code Screenshot](https://github.com/phqsuema123/big-data-engineering-with-python-2023/blob/main/image/Screenshot%202024-03-28%20102652.png?raw=true)

# Questions and Answers

1. **How many times does the phrase الٓمٓ appear in the Quran?**
   - Answer: The phrase 'الٓمٓ' occurs 8 times in the Quran.

2. **How many times does the phrase وَ appear in the Quran?**
   - Answer: The phrase 'وَ' occurs 4758 times in the database.

3. **How many times does the phrase ٱلَّذِينَ appear in the Quran?**
   - Answer: The phrase 'ٱلَّذِينَ' occurs 879 times in the Quran.

4. **What are the most similar words?**
   - Answer: The most similar words in the Tafseer text are:
     - you (Similarity Score: 90)
     - Our (Similarity Score: 90)
     - your (Similarity Score: 90)
     - Your (Similarity Score: 90)
     - here (Similarity Score: 90)
     - You (Similarity Score: 90)
     - our (Similarity Score: 90)
     - Get (Similarity Score: 90)
     - her (Similarity Score: 90)
     - word (Similarity Score: 90)

5. **How many times does the word 'battle' appear in the Quran?**
   - Answer: The word 'battle' appears 6 times.

6. **How many times does the word 'humans' appear in the Quran?**
   - Answer: The word 'humans' appears 12 times.

7. **How many times does the word 'Muslim' appear in the Quran?**
   - Answer: The word 'Muslim' appears 12 times.

8. **How many times does the word 'Merciful' appear in the Quran?**
   - Answer: The word 'Merciful' appears 37 times.

9. **How many times does the word 'peace' appear in the Quran?**
   - Answer: The word 'peace' appears 28 times.

10. **How many times does the word 'fira' appear in the Quran?**
    - Answer: The word 'fira' appears 2 times.

11. **How many times does the word 'pasture' appear in the Quran?**
    - Answer: The word 'pasture' appears 2 times.

12. **How many times does the word 'obeying' appear in the Quran?**
    - Answer: The word 'obeying' appears 2 times.

13. **How many times does the word 'drunkenness' appear in the Quran?**
    - Answer: The word 'drunkenness' appears 1 time.

14. **How many times does the word 'gambling' appear in the Quran?**
    - Answer: The word 'gambling' appears 1 time.

15. **How many times does the word 'patience' appear in the Quran?**
    - Answer: The word 'patience' appears 9 times.

16. **How many times does the word 'prophet' appear in the Quran?**
    - Answer: The word 'prophet' appears 51 times.

17. **How many times does the word 'worship' appear in the Quran?**
    - Answer: The word 'worship' appears 114 times.

18. **How many times does the word 'hell' appear in the Quran?**
    - Answer: The word 'hell' appears 31 times.

19. **How many times does the word 'fire' appear in the Quran?**
    - Answer: The word 'fire' appears 40 times.

20. **How many times does the word 'light' appear in the Quran?**
    - Answer: The word 'light' appears 50 times.
