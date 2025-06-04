# Obong-DSA-Documentation

## MY LEARNING JOURNEY WITH DIGITAL SKILLS AFRICA 

## *Introduction*  

*My journey into the world of data analysis began when I applied to the Digital Skills Africa program with a strong desire to gain practical, in-demand skills in today’s data-driven world. Through this program, I have been equipped with essential tools and knowledge that are foundational to the role of a data analyst.
__As part of my training, I have gained hands-on experience with Microsoft Excel, mastering data entry, cleaning, and analysis using formulas, pivot tables, and charts__. I also learned Structured Query Language (SQL), which has empowered me to retrieve, manipulate, and manage data efficiently from relational databases. Furthermore, I am currently being taught Power BI, a powerful business intelligence tool that can enabled me to visualize data and create interactive dashboards to support data-driven decision-making.
This learning journey has not only deepened my understanding of data but has also strengthened my analytical thinking and problem-solving abilities. I am excited to continue growing in this field and applying my skills to real-world challenges.*

## Used Tools

(1) **Microsoft Excel:** [Download here](https://www.microsoft.com)

# Project 1: Basic Excel Functions

**Goal**: To Demonstrate mastery of foundational Excel functions.

## Skills Demonstrated:
    1. Excel funnctions like: SUM, AVERAGE, MAX, MIN, COUNTA
    2. Conditional functions: SUMIF, AVERAGEIF, MAXIFS, MINIFS, COUNTIF

## See Table 1




![Table 1](https://github.com/user-attachments/assets/c889bca2-4795-4502-b0eb-04b9ccdf2e05)



  
- The Dataset include: Staff data with the following colums:

    (i). Names

    (ii). Company

    (iii). Salary
	
 - **Tasks**:
   
   - Calculate Grand Total
   - Average Salary
   - Highest Salary
   - Lowest Salary
   - Total No of Staff
   - Fourth highest salary
   - Third Lowest salary

  3. Excel Formulas and Objectives to Demonstrate

      (i) SUM Function

     **Task:** Calculate the grand total of salaries across the different Companies.
       - = SUM(D8:D27)
       - = 56,165,334
     
     (ii) Average Fuunction

     **Task:** Calculate Average Salary
       - = Average(D8:D27)
       - = 2,808,267

     (iii) Highest Salary
     
     **Task:** Find highest salary paid.
        - = MAX(D8:D27)
        - = 4,974,390
   
     (iv) Lowest Salary
    
       **Task:** Find lowest salary paid
       - = MIN(D8:D27)
       - = 1,130,642

     (v) Total No of Staff

     **Task:** Calculate total No of staff paid
     - = COUNTA(B8:B27)
     - = 20
      
     (vi) Fourth highest salary
    
     __Task__ Calculate fourth highest salary paid
     - = LARGE(D8:D27)
     - = 4,740,966
      
     (vii) Third Lowest salary 
    
     **Task:** Calculate third lowest salary paid
       - = SMALL(D8:D27)
       - = 1,358,916

     (viii) Bayelsa Total Salary
    
     **Task:** Calculate total Bayelsa salary paid
      - = SUMIF(C8:C27,C8,D8:D27)
      - = 11,164,905

      (ix) Average Oyo Salary

     **Task:** Calculate Average Oyo salary paid
      - = AVERAGEIF(C8:C27,C16,D8:D27)
      - = 1,983,141

       (x) Highest Edo Salary
     
     **Task:** Calculate Highest Edo salary paid
      - = MAXIFS(D8:D27,C8:C27,C16)
      - = 3,028,264
      
       (xi) Lowest Taraba Salary
    
     **Task:** Calculate Lowest Taraba salary paid
      - = MINIFS(D8:D27,C8:C27,C10)
      - = 1,226,444
      
       (xii) Total No of Staff in Nassarawa

      **Task:** Calculate total No of staff in Nassarawa
       - = COUNTIF(C9:C27,C15)
       - = 4

# Project 2: Data Cleaning

**Goal:** Clean a messy dataset to prepare it for analysis.

## Skills Demonstrated:
    1. Trimming spaces
    2. Formatting with Cap locks
    3. Formatting with Lowercase
    4. Handling missing values
    5. Correcting errors (e.g., spelling mistakes)
    6. Standardizing formats

## Tasks:
- Clean the “Date” column into a uniform format.
- Use TRIM, CLEAN, and PROPER functions to standardize text.
- Fill or remove missing values.
- Document before and after cleaning using screenshots or comments.

See Table before and After Cleannning






![Text Cleaning_Before](https://github.com/user-attachments/assets/a9c2911c-af80-48e4-a0b9-1ac1084af6ff)







![Text Cleaning_After](https://github.com/user-attachments/assets/7e5f5e7d-3e1d-434c-8e34-69b1a2bfd513)









# Project 3: IF OR & AND IF Functions

## Goal: Use logical functions to create flexible formulas.

## Skills Demonstrated:
  - Use IF or IFS to assign students remarks (“Promote”, “Repeat”).
    
     - Formula used = IF(AND(G3>=40),"Pass","Fail")
    
  - Use OR to find students who passed at least one subject.
       
     - Formula used = IF(OR(S3>=50,T3>=50),"Promote","Repeat")
           
  - Use AND to flag students who scored above 40 in all subjects
       
     - Formula used = IF(AND(S3>50,T3>50),"Promoted","Repeat")
    
  - Use IF or IFS to assign customer age group
       
     - Formula used IF(N3<=19,"Teeager",IF(N3<=35,"Youth",IF(N3<=45,"Young Adult",IF(N3<=55,"Adult",IF(N3<=70,"Elder","Senior Citize")))))


  
