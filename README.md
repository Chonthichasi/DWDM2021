# DWDM21

### Data Warehouse & Data Mining 2021

ชลธิชา ศาลางาม รหัสนักศึกษา 623020518-7

Group Name :

  กัญญาวีร์ ศรีเทียมเงิน รหัสนักศึกษา 623020511-1
  
  ชลธิชา ศาลางาม รหัสนักศึกษ 623020518-7
  
  สุภาภรณ์ บุตุธรรม รหัสนักศึกษา 623020543-
  
  จิราพร กลบรัตน์ รหัสนักศึกษ 623020762-6
  
  วิกานดา หงษ์บุญมี 623020764-2



# สารบัญ
* บทที่ 1 INTRODUCTION 
  * [Lecture Introduction](https://github.com/Chonthichasi/DWDM2021/blob/main/Chapter1.pdf)
    * Data Mining คืออะไร
    * ทำไมถึงต้องทำ Data Mining
    * Knowledge Discovery (KDD) Process
    * Data Mining in Business Intelligence
    * ตัวอย่างของข้อมูล
 
* บทที่ 2 Getting to Know Your Data
  * Lecture Chapter 2 Getting to know your data ประกอบด้วย 
    * [Lecture Data Objects and Attribute Types](https://github.com/Chonthichasi/DWDM2021/blob/main/Chapter2.pdf)
      * Types of Data Sets
        * Record Data
        * Ordered Data
        * Spatial, image and multimedia Data
      * Important Characteristics of Structured Data
      * Data Objects
      * Attributes
      * Attribute Types
      * Numeric Attribute Types
      * Discrete Attribute
      * Continuous Attribute
      * Basic Statistical Descriptions of Data
 
    * [Lecture Measuring Data Similarity and Dissimilarity](https://github.com/Chonthichasi/DWDM2021/blob/main/02Data.pdf)
      * Similarity, Dissimilarity, and Proximity
      * Data Matrix and Dissimilarity Matrix
      * Standardizing Numeric Data
      * Special Cases of Minkowski Distance

    * [Lecture Binary Distance](https://github.com/Chonthichasi/DWDM2021/blob/main/Chapter1.pdf)
      * Proximity Measure for Binary Attributes
      * Proximity Measure for Categorical Attributes
      * Ordinal Variables
      * Attributes of Mixed Type
      * Cosine Similarity of Two Vectors
     
    * [Basic Python](https://github.com/Chonthichasi/DWDM2021/blob/main/Data101(Chapter2).ipynb)
      * Variables
          * ข้อกำหนดในการตั้งตัวแปร
      * Casting int() float() stri()
      * Data Structure
        * list ()
          * string คือ list ของ ตัวหนังสือ
          * วิธีการสร้าง list แบบที่ 2 list ว่าง
            * เติมค่าลงไปใน list (.append())
            * การชี้ค่าใน list (indexing)
           * list slicing
            * [จุดเริ่มต้น: จุดสุดท้าย: step]
           * list + list
           * format string
           * Loop
              *Nested loop
           * Condition ( if statement )
            * Quiz 1 หา min
            * Homework 3 ตัดเกรด
          * Function
            * Example 1
            * Example 2 ฟังก์ชั่นที่ไม่มี input มีแต่ process กับ output
            * Example 3 ฟังก์ชั่นที่ไม่มี output มีแต่ process กับ input
            * Example 3 ฟังก์ชั่นที่ไม่มี output กับ input มีแต่ process
            * ลักษณะของ input(parameter)
            * Quiz 2
     * [Pandas](https://github.com/Chonthichasi/DWDM2021/blob/main/Data102.ipynb)
       * Read Data
          * .head() .tail()
          * Boxplot
          * Time Series Plot
    * [Visualization](https://github.com/Chonthichasi/DWDM2021/blob/main/Data_Visualization.ipynb)
      * Visualization
        * Box plot
        * Scatter plot
        * Plot
        * Bar chart
          * Grouped Barchart
          * Stacked Barchart
        * Histogram
    * [Distance_Numpy](https://github.com/Chonthichasi/DWDM2021/blob/main/Distance_Numpy.ipynb)
      * Numpy array
        * สร้าง numpy array
          * matrix transpose
        * สร้าง matrix เริ่มต้น (zeros, ones)
        * สร้าง matrix random
           * matix properties
        * Indexing & Slicing
        * Useful functions
        * วนลูปเอง
          * summation
        * Quiz กลุ่ม
       * Distance Matrix
          * Euclidean Distance (L2-norm)
          * Distance function
          * Manhattan Distance (L1-norm)
          * HW11
          * เฉลย HW11
          * Distance of Binary Value
         
  * บทที่ 3 Data Preprocessing
    * [Lecture Chapter 3 Data Preprocessing](https://github.com/Chonthichasi/DWDM2021/blob/main/Chapter3.pdf)
      * Data Cleaning คืออะไร
      * Data Integration คืออะไร
      * Data Reduction คืออะไร
      * Data Transformation และ Data Discretization คืออะไร
      * การจัดการกับ Missing Data ด้วยวิธีต่าง ๆ
    * [Data Preprocessing](https://github.com/Chonthichasi/DWDM2021/blob/main/Data_Preprocessing_(Chapter_3).ipynb)
      * Meta Data (Data ที่ใช้อธิบาย Data)
        * ชี้ข้อมูลในตาราง
          * ชี้แบบธรรมดา ใช้ [ชื่อ column][index]
          * ชี้แบบ .iloc[] (มองข้อมูลเป็น matrix)
        * Missing Values
          * Handling Misiing Value 1 (ลบค่า missing ออกไป) 
          * Quiz 3 ให้หาว่าการทำ dropna() ทำให้ข้อมูลหายไปกี่ %
          * เฉลยตามอาจารย์
          * Handling Misiing Value 1.5 (ลบค่า missing เฉพาะในคอลัมม์ที่เราสนใจออกไป)
          * Quiz 3.1 ให้หาว่าการทำ dropna() แบบเลือก drop เฉพาะคอลลัมม์ที่เราสนใจ (age) ทำให้ข้อมูลหายไปกี่ %
          * Handling Misiing Value 2 (แทนค่าด้วย class ใหม่ (unknown))
          * Handling Misiing Value 3 (แทนค่าด้วย class ใหม่ (ค่าที่เหมาะสม))
          * Handling Misiing Value 4 (แทนค่าด้วย ค่ากลาง)
          * ถ้าเป็น morminal (ตัวหนังสือ) จะใช้ฐานนิยม
        * เติมด้วยช่องว่าง column ใกล้เคียง
          * ถ้าเป็น ordinal เติม Median
          * Handling Misiing Value 5 (แทนค่าด้วย ค่ากลางของ sample ใน class เดียวกัน)
        * Select data by values [PD] คำสั่งแพนด้า
          * ขั้นตอนสร้าง list ของ boolen
          * นำ list ของ boolen มาเลือกในตาราง
          * สร้าง list ของ boolen
          * เราใช้ & (and) และ | (or) ในการรวม list ของ boolen
          * Quiz 4 + การบ้าน
* บทที่ 4 Data Warehousing and On-line Analytical Processing
  * [Lecture Chapter 4 Data Warehousing and On-line Analytical Processing](https://github.com/Chonthichasi/DWDM2021/blob/main/Chapter4.pdf)
    * What is a Data Warehouse?
    * From Tables and Spreadsheets to Data Cubes
    * Conceptual Modeling of Data Warehouses
      * Star Schema: An Example
      * Snowflake Schema: An Example
      * Fact Constellation: An Example
    * Typical OLAP Operations
      * Roll up (drill-up)
      * Drill down (roll down)
      * Slice and dice
      * Pivot (rotate)
      * Drill across
      * Drill through
* บทที่ 5 Association Rules
  * [Lecture Mining Frequent Patterns, Association and Correlations: Basic Concepts and Methods
](https://github.com/Chonthichasi/DWDM2021/blob/main/Chapter5.pdf)
    * Basic Concepts
      * What Is Pattern Discovery?
        * k-Itemsets and Their Supports
        * Frequent Itemsets (Patterns)
        * From Frequent Itemsets to Association Rules
        * Mining Frequent Itemsets and Association Rules
    * Efficient Pattern Mining Methods
      * Apriori Algorithm
        * Apriori Pruning and Scalable Mining Methods
        * A Candidate Generation & Test Approach
        * The Apriori Algorithm
   * [Reduced_marketbasket](https://github.com/Chonthichasi/DWDM2021/blob/main/Chapter_6_Association_Rules.ipynb)
      * ลบ records ที่ถูก cancel ออกไป
      * มีประเทศสาขาของ Supermarket นี้ทั้งหมดกี่ประเทศ
      * HW 13 วาดกราฟสรุปจำนวน items และยอดขายของแต่ละประเทศ
      * เตรียม Data สำหรับ (Frequence Pattern) Association Rule
      * Apriori
        * แปลความหมาย
        * Quiz 7 หา k-itemset ที่มีความน่าสนใจ (โดยพิจารณาลูกค้าเป็นรายคน) พร้อมอธิบายว่าน่าสนใจยังไง
        * แปลความหมายของผลลัพธ์
 
* บทที่ 6 Classification
  * [Lecture Classification: Basic Concepts](https://github.com/Chonthichasi/DWDM2021/blob/main/Chapter6.pdf)
    * Basic Concepts
      * Supervised vs. Unsupervised Learning (1)
      * Supervised vs. Unsupervised Learning (2)
      * Prediction Problems: Classification vs. Numeric Prediction
      * Classification—Model Construction, Validation and Testing
    * Decision Tree Induction
      * An Example
      * Information Gain
    * [Decision Tree](https://github.com/Chonthichasi/DWDM2021/blob/main/Chapter_7_Classification_(Decision_Tree).ipynb)
      * Load Data
      * Train Model
        * import (เรียกใช้อัลกอริทึมที่เราต้องการ)
        * define (กำหนดพารามิเตอร์ให้กับ model)
        * train (ฝึกสอนตัวแบบ)
        * plot tree
      * Evaluation
        * Random
      * Advanced Tree
        * import
        * Define
        * Train
        * TEST
        * Start here
      * HW
        * ต้นไม้ที่ใช้เกณฑ์ Entropy มีความสูงไม่เกิน 4 ชั้น
        * Import
        * Define
        * Train
        * Evaluate
        * Test
        * ต้นไม้ที่ใช้เกณฑ์ Gini มีใบไม่เกิน 25 ใบ
        * Import
        * Define
        * Train
        * Evaluate
        * Test
        * ต้นไม้ที่ใช้เกณฑ์ Entropy และใช้การ split แบบ random
        * Import
        * Define
        * Train
        * Evaluate
        * Test
        * ต้นไม้ที่เราคิดเอง
        * Import
        * Define
        * Train
        * Evaluate
        * Test
        * เลือก T4 แล้ว Train ใหม่ด้วย Training
    * [k-Nearest Neighbor & Neural Networks](https://github.com/Chonthichasi/DWDM2021/blob/main/Chapter_7_Classification_(KNN_NN).ipynb)
      * Load Data
      * Split Data
      * Train Model
        * Import
        * KNN1
        * KNN2
        * KNN3
      * Retain & Evaluate
      * Neural Network
        * Import
        * Define
        * Train-Test
        * ANN2
        * ANN3
    * [Evaluation](https://github.com/Chonthichasi/DWDM2021/blob/main/Chapter_7_Classification_(Evaluation).ipynb)
      * Load data
      * แบ่ง Data
      * สร้าง Model ทำนาย
        * Import
        * Define
        * Train
      * Evaluation
* บทที่ 7 Clustering
  * [Clustering]

* MiniExam 
  * [MiniExam](https://github.com/Chonthichasi/DWDM2021/blob/main/MiniExam.ipynb)
* Group Project
  * [Group Project](https://github.com/Chonthichasi/DWDM2021/blob/main/Project_DWDM.ipynb)
     * Project กลุ่ม
      * รายชื่อสมาชิกในกลุ่ม
      * แหล่งที่มาของข้อมูล
      * ปัญหา
        * ชุดข้อมูลที่ 1 รับเรื่องร้องเรียน/แจ้งเบาะแสยาเสพติด
        * คำอธิบายตาราง
        * ตรวจสอบค่า Missing ของตาราง data_01
      * ชุดข้อมูลที่ 2 ปริมาณของกลางยาเสพติด
        * คำอธิบายตาราง
        * ตรวจสอบค่า Missing ของตาราง data_02
     * ชุดข้อมูลที่ 3 จำนวนคดี ผู้ต้องหาคดียาเสพติด
        * คำอธิบายตาราง
        * ตรวจสอบค่า Missing ของตาราง data_03
     * ข้อมูลชุดที่ 4 ข้อมูลทั่วไปของจังหวัด
        * คำอธิบายตาราง
        * ตรวจสอบค่า Missing ของตาราง data_04
    * เชื่อมต่อตาราง
        * ตรวจสอบค่า Missing ของตาราง 2 ตารางที่เชื่อมต่อกันแล้ว
        * ตรวจสอบค่า Missing ของตาราง 3 ตารางที่เชื่อมต่อกันแล้ว
    * Classification
        * ปัญหา
        * เลือกคอลัมน์ที่ต้องการนำมาใช้งาน
        * Decision Tree
        * KNN
        * Neural Network
    * Evaluation
        * Retain & Evaluation
        * Data_Visualization
* Slide นำเสนอ
* [Slide นำเสนอ](
  
    

